---
title: "method"
linktitle: "ReadBarCodes"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。读取图像中的 BarCodeResults（在 C++ 中）。"
type: docs
weight: 1300
url: /zh/cpp/aspose.barcode.barcoderecognition/barcodereader/readbarcodes/
---
## BarCodeReader::ReadBarCodes method


读取来自图像的 [BarCodeResult](../../barcoderesult/)。

```cpp
System::ArrayPtr<System::SharedPtr<BarCodeResult>> Aspose::BarCode::BarCodeRecognition::BarCodeReader::ReadBarCodes()
```


### ReturnValue

返回图像上识别的 [BarCodeResult](../../barcoderesult/) 数组。如果没有识别到任何内容，则返回空数组。
## 备注


此示例展示了如何使用 [BarCodeReader](../) 读取条码。
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    reader.ReadBarCodes();
    for(int i = 0; reader.FoundCount > i; ++i)
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes[i].CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    reader.ReadBarCodes()
    For i As Integer = 0 To reader.FoundCount - 1 Step 1
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes(i).CodeText)
    Next
End Using

Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```


## 另见

* Class [BarCodeResult](../../barcoderesult/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
