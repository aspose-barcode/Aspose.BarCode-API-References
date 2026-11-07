---
title: "メソッド"
linktitle: "get_ChecksumValidation"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "C++ で Aspose::BarCode::BarCodeRecognition::BarcodeSettings クラスの get_ChecksumValidation メソッドを使用する方法。"
type: docs
weight: 100
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_checksumvalidation/
---
## BarcodeSettings::get_ChecksumValidation method




```cpp
Aspose::BarCode::BarCodeRecognition::ChecksumValidation Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_ChecksumValidation() const
```

## 備考


1D および郵便バーコードの認識時にチェックサム検証を有効にします。

デフォルトは、チェックサムが必須のシンボロジーでは「はい」とみなされ、チェックサムが可能なだけのシンボロジーでは「いいえ」とみなされます。

チェックサムが使用されない: Codabar、PatchCode、Pharmacode、DataLogic2of5

チェックサムが可能: Code39 Standard/Extended、Standard2of5、Interleaved2of5、ItalianPost25、Matrix2of5、MSI、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN

チェックサムが常に使用される: その他のシンボロジー

このサンプルは ChecksumValidation が認識品質と結果に与える影響を示します。
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //チェックサム無効
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //チェックサム有効
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum disabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum enabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```


1D および郵便バーコードの認識時にチェックサム検証を有効にします。
## 関連項目

* Enum [ChecksumValidation](../../checksumvalidation/)
* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
