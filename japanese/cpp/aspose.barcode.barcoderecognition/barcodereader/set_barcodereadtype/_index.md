---
title: "メソッド"
linktitle: "set_BarCodeReadType"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " method. 認識に使用されるバーコードデコードタイプを設定します。C++ で ReadBarCodes を呼び出す前に設定する必要があります。"
type: docs
weight: 1100
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodereader/set_barcodereadtype/
---
## BarCodeReader::set_BarCodeReadType method


認識に使用されるバーコードデコードタイプを設定します。呼び出す前に [ReadBarCodes](../readbarcodes/) を設定する必要があります。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_BarCodeReadType(System::SharedPtr<BaseDecodeType> value)
```

## 備考


このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.BarCodeReadType = new MultiDecodeType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString());
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.BarCodeReadType = New MultiDecodeType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString())
End Using
```

## 関連項目

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
