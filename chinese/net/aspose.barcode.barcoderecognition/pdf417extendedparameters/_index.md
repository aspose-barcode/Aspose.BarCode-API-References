---
title: "类 Pdf417ExtendedParameters"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.Pdf417ExtendedParameters 类。存储已识别条码的 MacroPdf417 元数据"
type: docs
weight: 340
url: /zh/net/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class

存储已识别的条形码的 MacroPdf417 元数据

```csharp
public sealed class Pdf417ExtendedParameters : BaseExtendedParameters
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [IsCode128Emulation](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/iscode128emulation/) { get; } | 标志，指示使用 908、909、910 或 911 Code 128 仿真码字编码的 MicroPdf417 条码。 |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | 测试所有参数是否仅具有默认值 |
| [IsLinked](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/islinked/) { get; } | 标志，指示该条码必须链接到 1D 条码。 |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/isreaderinitialization/) { get; } | 用于指示阅读器将符号中包含的数据解释为用于阅读器初始化的程序。 |
| [MacroPdf417Addressee](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417addressee/) { get; } | Macro PDF417 收件人名称（可选）。 |
| [MacroPdf417Checksum](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417checksum/) { get; } | Macro PDF417 校验和（可选）。 |
| [MacroPdf417FileID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417fileid/) { get; } | 获取条形码的文件 ID，仅在 MacroPdf417 可用。 |
| [MacroPdf417FileName](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filename/) { get; } | Macro PDF417 文件名（可选）。 |
| [MacroPdf417FileSize](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filesize/) { get; } | Macro PDF417 文件大小（可选）。 |
| [MacroPdf417SegmentID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentid/) { get; } | 获取条形码的段 ID，仅在 MacroPdf417 可用。 |
| [MacroPdf417SegmentsCount](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentscount/) { get; } | 获取 macro pdf417 条形码段计数。默认值为 -1。 |
| [MacroPdf417Sender](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417sender/) { get; } | Macro PDF417 发送者名称（可选）。 |
| [MacroPdf417Terminator](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417terminator/) { get; } | 指示该段是否为 Macro PDF417 文件的最后一段。 |
| [MacroPdf417TimeStamp](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417timestamp/) { get; } | Macro PDF417 时间戳（可选）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/equals/)(object) | 返回一个值，指示此实例是否等于指定的 `Pdf417ExtendedParameters` 值。 |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/gethashcode/)() | 返回此实例的哈希码。 |
| override [ToString](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/tostring/)() | 返回此 `Pdf417ExtendedParameters` 的可读字符串表示。 |
| [operator ==](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_equality/) | 返回一个值，指示第一个 `Pdf417ExtendedParameters` 值是否等于第二个。 |
| [operator !=](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_inequality/) | 返回一个值，指示第一个 `Pdf417ExtendedParameters` 值是否不同于第二个。 |

## 示例

此示例展示如何获取 Macro Pdf417 元数据

```csharp
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

### 另见

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


