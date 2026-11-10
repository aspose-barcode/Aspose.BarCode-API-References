---
title: "类 Pdf417ParametersUI"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Windows.Forms.Pdf417ParametersUI 类。Pdf417Parameters 类的 UI 包装器"
type: docs
weight: 1860
url: /zh/net/aspose.barcode.windows.forms/pdf417parametersui/
---
## Pdf417ParametersUI class

UI 包装器用于 [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/) 类。

```csharp
public class Pdf417ParametersUI
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AspectRatio](../../aspose.barcode.windows.forms/pdf417parametersui/aspectratio/) { get; set; } | 2D 条码模块的高/宽比。 |
| [Columns](../../aspose.barcode.windows.forms/pdf417parametersui/columns/) { get; set; } | 列数。 |
| [ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/eciencoding/) { get; set; } | 扩展信道解释标识符。它用于向条码阅读器提供有关在符号中对数据进行编码所使用的参考的详细信息。未应用于 Macro PDF417 文本字段。当前实现包含所有已知的字符集编码。 |
| [EncodeMode](../../aspose.barcode.windows.forms/pdf417parametersui/encodemode/) { get; set; } | 条码的编码模式的 Pdf417 符号类型。默认值：Pdf417EncodeMode.Auto。 |
| [ErrorLevel](../../aspose.barcode.windows.forms/pdf417parametersui/errorlevel/) { get; set; } | 获取或设置条码错误更正级别的 Pdf417 符号类型，范围从 level0 到 level8，level0 表示无错误更正信息，level8 表示最佳错误更正，即更大的图像。 |
| [IsCode128Emulation](../../aspose.barcode.windows.forms/pdf417parametersui/iscode128emulation/) { get; set; } | 只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置编码 FNC1（模式 908 和 909），还可以编码 910 和 911，这仅表示识别的 MicroPdf417 可解释为 Code 128。 |
| [IsLinked](../../aspose.barcode.windows.forms/pdf417parametersui/islinked/) { get; set; } | 定义与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号编码 906、907、912、913、914、915 “链接” UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。 |
| [IsReaderInitialization](../../aspose.barcode.windows.forms/pdf417parametersui/isreaderinitialization/) { get; set; } | 用于指示阅读器将符号中包含的数据解释为用于阅读器初始化的程序。 |
| [MacroCharacters](../../aspose.barcode.windows.forms/pdf417parametersui/macrocharacters/) { get; set; } | 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 MicroPdf417 一起使用，并对 916 和 917 MicroPdf417 模式进行编码。默认值：MacroCharacters.None。 |
| [MacroPdf417Addressee](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417addressee/) { get; set; } | MacroPdf417 条码收件人名称（可选字段）。MicroPDF417 条码收件人名称（结构追加模式的可选字段） |
| [MacroPdf417Checksum](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417checksum/) { get; set; } | MacroPdf417 条码校验和（可选字段）。MicroPDF417 条码校验和（结构追加模式的可选字段）校验和字段包含使用 CCITT-16 多项式的 16 位（2 字节）CRC 校验和值。x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417eciencoding/) { get; set; } | 扩展通道解释标识符。适用于 Macro PDF417 文本字段。 |
| [MacroPdf417FileID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417fileid/) { get; set; } | 获取或设置宏 Pdf417 条码的文件 ID。用于 MacroPdf417。 |
| [MacroPdf417FileName](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filename/) { get; set; } | MacroPdf417 条码文件名（可选字段）。MicroPDF417 条码文件名（结构追加模式的可选字段） |
| [MacroPdf417FileSize](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filesize/) { get; set; } | MacroPdf417 文件大小（可选字段）。MicroPDF417 文件大小（结构化追加模式的可选字段）文件大小字段包含整个源文件的字节大小。 |
| [MacroPdf417SegmentID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentid/) { get; set; } | 获取或设置宏 Pdf417 条形码的段 ID，范围从 0 到 MacroSegmentsCount - 1。 |
| [MacroPdf417SegmentsCount](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentscount/) { get; set; } | 获取或设置宏 Pdf417 条形码的段计数。 |
| [MacroPdf417Sender](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417sender/) { get; set; } | MacroPdf417 条形码发送者名称（可选字段）。MicroPDF417 条形码发送者名称（结构化追加模式的可选字段） |
| [MacroPdf417Terminator](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417terminator/) { get; set; } | 用于告知编码器是否在段中添加 Macro PDF417 终止符（代码字 922）。仅适用于 Macro PDF417。 |
| [MacroPdf417TimeStamp](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417timestamp/) { get; set; } | MacroPdf417 条形码时间戳（可选字段）。MicroPDF417 条形码时间戳（结构化追加模式的可选字段） |
| [Rows](../../aspose.barcode.windows.forms/pdf417parametersui/rows/) { get; set; } | 行数。 |
| [Truncate](../../aspose.barcode.windows.forms/pdf417parametersui/truncate/) { get; set; } | 条码的 Pdf417 符号类型是否被截断（以减少空间）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/pdf417parametersui/tostring/)() | 返回此 [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/) 的可读字符串表示。 |

### 另见

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


