---
title: "method"
linktitle: "set_ChecksumValidation"
second_title: "Aspose.BarCode for C++ API 参考"
description: "如何在 C++ 中使用 Aspose::BarCode::BarCodeRecognition::BarcodeSettings 类的 set_ChecksumValidation 方法。"
type: docs
weight: 200
url: /zh/cpp/aspose.barcode.barcoderecognition/barcodesettings/set_checksumvalidation/
---
## BarcodeSettings::set_ChecksumValidation method




```cpp
void Aspose::BarCode::BarCodeRecognition::BarcodeSettings::set_ChecksumValidation(Aspose::BarCode::BarCodeRecognition::ChecksumValidation value)
```

## 备注


在识别 1D 和邮政条码时启用校验和验证。

默认情况下，对于必须包含校验和的符号视为 Yes，对于仅可能包含校验和的符号视为 No。

从不使用校验和：Codabar、PatchCode、Pharmacode、DataLogic2of5

可能使用校验和：Code39 Standard/Extended、Standard2of5、Interleaved2of5、ItalianPost25、Matrix2of5、MSI、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN

始终使用校验和：其余符号

此示例展示 ChecksumValidation 对识别质量和结果的影响
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //校验和已禁用
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
    //校验和已启用
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


在识别 1D 和邮政条码时启用校验和验证。
## 另见

* Enum [ChecksumValidation](../../checksumvalidation/)
* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
