---
title: "类 Pdf417Parameters"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.Pdf417Parameters 类。PDF417 参数。包含 PDF417、MacroPDF417、MicroPDF417 和 GS1MicroPdf417 参数。MacroPDF417 需要两个字段 Pdf417MacroFileID 和 Pdf417MacroSegmentID。所有其他字段为可选。MicroPDF417 在结构化追加模式下与 MacroPDF417 模式相同，需要两个字段 Pdf417MacroFileID 和 Pdf417MacroSegmentID。所有其他字段为可选。"
type: docs
weight: 1570
url: /zh/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

PDF417 参数。包含 PDF417、MacroPDF417、MicroPDF417 和 GS1MicroPdf417 参数。MacroPDF417 需要两个字段：Pdf417MacroFileID 和 Pdf417MacroSegmentID。其他所有字段为可选。MicroPDF417 在结构化追加模式（同 MacroPDF417 模式）下需要两个字段：Pdf417MacroFileID 和 Pdf417MacroSegmentID。其他所有字段为可选。

```csharp
public class Pdf417Parameters
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio/) { get; set; } | 2D 条码模块的高/宽比。 |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns/) { get; set; } | 列数。 |
| [ECIEncoding](../../aspose.barcode.generation/pdf417parameters/eciencoding/) { get; set; } | 扩展信道解释标识符。它用于向条码阅读器提供有关在符号中对数据进行编码所使用的参考的详细信息。未应用于 Macro PDF417 文本字段。当前实现包含所有已知的字符集编码。 |
| [EncodeMode](../../aspose.barcode.generation/pdf417parameters/encodemode/) { get; set; } | 标识 Pdf417 编码模式。默认值：Auto。 |
| [ErrorLevel](../../aspose.barcode.generation/pdf417parameters/errorlevel/) { get; set; } | 获取或设置条码错误更正级别的 Pdf417 符号类型，范围从 level0 到 level8，level0 表示无错误更正信息，level8 表示最佳错误更正，即更大的图像。 |
| [IsCode128Emulation](../../aspose.barcode.generation/pdf417parameters/iscode128emulation/) { get; set; } | 只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置编码 FNC1（模式 908 和 909），还可以编码 910 和 911，这仅表示识别的 MicroPdf417 可解释为 Code 128。 |
| [IsLinked](../../aspose.barcode.generation/pdf417parameters/islinked/) { get; set; } | 定义与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号编码 906、907、912、913、914、915 “链接” UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。 |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization/) { get; set; } | 用于指示阅读器将符号中包含的数据解释为用于阅读器初始化的程序。 |
| [MacroCharacters](../../aspose.barcode.generation/pdf417parameters/macrocharacters/) { get; set; } | 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 MicroPdf417 一起使用，并对 916 和 917 MicroPdf417 模式进行编码。默认值：MacroCharacters.None。 |
| [MacroPdf417Addressee](../../aspose.barcode.generation/pdf417parameters/macropdf417addressee/) { get; set; } | MacroPdf417 条码收件人名称（可选字段）。MicroPDF417 条码收件人名称（结构追加模式的可选字段） |
| [MacroPdf417Checksum](../../aspose.barcode.generation/pdf417parameters/macropdf417checksum/) { get; set; } | MacroPdf417 条码校验和（可选字段）。MicroPDF417 条码校验和（结构追加模式的可选字段）校验和字段包含使用 CCITT-16 多项式的 16 位（2 字节）CRC 校验和值。x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/macropdf417eciencoding/) { get; set; } | 扩展通道解释标识符。适用于 Macro PDF417 文本字段。 |
| [MacroPdf417FileID](../../aspose.barcode.generation/pdf417parameters/macropdf417fileid/) { get; set; } | MacroPdf417 条码的文件 ID（必填字段）。MicroPDF417 条码的文件 ID（结构化追加模式下的必填字段） |
| [MacroPdf417FileName](../../aspose.barcode.generation/pdf417parameters/macropdf417filename/) { get; set; } | MacroPdf417 条码文件名（可选字段）。MicroPDF417 条码文件名（结构追加模式的可选字段） |
| [MacroPdf417FileSize](../../aspose.barcode.generation/pdf417parameters/macropdf417filesize/) { get; set; } | MacroPdf417 文件大小（可选字段）。MicroPDF417 文件大小（结构化追加模式的可选字段）文件大小字段包含整个源文件的字节大小。 |
| [MacroPdf417SegmentID](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentid/) { get; set; } | MacroPdf417 条码的段 ID（必填字段），范围从 0 到 MacroSegmentsCount - 1。MicroPDF417 条码的段 ID（结构化追加模式下的必填字段） |
| [MacroPdf417SegmentsCount](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentscount/) { get; set; } | MacroPdf417 条码段计数（可选字段）。MicroPDF417 条码段计数（结构化追加模式下的可选字段） |
| [MacroPdf417Sender](../../aspose.barcode.generation/pdf417parameters/macropdf417sender/) { get; set; } | MacroPdf417 条形码发送者名称（可选字段）。MicroPDF417 条形码发送者名称（结构化追加模式的可选字段） |
| [MacroPdf417Terminator](../../aspose.barcode.generation/pdf417parameters/macropdf417terminator/) { get; set; } | 用于告知编码器是否在段中添加 Macro PDF417 终止符（代码字 922）。仅适用于 Macro PDF417。 |
| [MacroPdf417TimeStamp](../../aspose.barcode.generation/pdf417parameters/macropdf417timestamp/) { get; set; } | MacroPdf417 条形码时间戳（可选字段）。MicroPDF417 条形码时间戳（结构化追加模式的可选字段） |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows/) { get; set; } | 行数。 |
| [Truncate](../../aspose.barcode.generation/pdf417parameters/truncate/) { get; set; } | 指示条码的 Pdf417 符号类型是否被截断（以减少空间）。也称为 CompactPDF417。在此模式下，右行指示符和右停止图案被移除。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring/)() | 返回此 `Pdf417Parameters` 的可读字符串表示。 |

## 示例

这些示例展示如何在 GS1MicroPdf417 中编码 UCC/EAN-128 非链接模式

```csharp
[C#]
//使用 AI 01（GTIN）编码 GS1 UCC/EAN-128 非链接模式 905
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//使用任意 AI 编码 GS1 UCC/EAN-128 非链接模式 903、904
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


