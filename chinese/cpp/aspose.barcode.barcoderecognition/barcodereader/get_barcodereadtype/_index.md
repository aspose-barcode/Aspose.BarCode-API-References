---
title: "method"
linktitle: "get_BarCodeReadType"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。获取用于识别的条码解码类型。必须在 C++ 中调用 ReadBarCodes 之前设置。"
type: docs
weight: 1000
url: /zh/cpp/aspose.barcode.barcoderecognition/barcodereader/get_barcodereadtype/
---
## BarCodeReader::get_BarCodeReadType method


获取用于识别的条码解码类型。必须在调用 [ReadBarCodes](../readbarcodes/) 之前设置。

```cpp
System::SharedPtr<BaseDecodeType> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_BarCodeReadType()
```

## 备注


此示例展示了如何检测 Code39 和 Code128 条码。
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

## 另见

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
