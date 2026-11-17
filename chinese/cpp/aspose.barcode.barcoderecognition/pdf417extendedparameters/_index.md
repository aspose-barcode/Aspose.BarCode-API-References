---
title: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters 类"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters 类。存储已识别条码的 MacroPdf417 元数据（在 C++ 中）。"
type: docs
weight: 2800
url: /zh/cpp/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class


存储已识别条码的 MacroPdf417 元数据

```cpp
class Pdf417ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | 标志，指示使用 908、909、910 或 911 Code 128 仿真码字编码的 MicroPdf417 条码。 |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** 是否所有参数仅具有默认值 |
| [get_IsLinked](./get_islinked/)() const | 标志，指示该条码必须链接到一维条码。 |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Macro PDF417 收件人名称（可选）。 |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Macro PDF417 校验和（可选）。 |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | 获取条码的文件 ID，仅在 MacroPdf417 中可用。 |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Macro PDF417 文件名（可选）。 |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Macro PDF417 文件大小（可选）。 |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | 获取条码的段 ID，仅在 MacroPdf417 中可用。 |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | 获取 macro pdf417 条码段计数。默认值为 -1。 |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Macro PDF417 发件人名称（可选）。 |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | 指示该段是否为 Macro PDF417 文件的最后一段。 |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Macro PDF417 时间戳（可选）。 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [ToString](./tostring/)() const override | 返回此 [Pdf417ExtendedParameters](./) 的人类可读字符串表示。 |
## 备注


此示例展示如何获取 Macro Pdf417 元数据。
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345"))
{
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1;
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MacroPdf417))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID);
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount);
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.MacroPdf417, "12345")
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.MacroPdf417)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID)
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount)
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID)
    Next
End Using
```

## 另见

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
