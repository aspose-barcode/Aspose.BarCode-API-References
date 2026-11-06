---
title: "Aspose::BarCode::Generation::Pdf417Parameters 类"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::Pdf417Parameters 类。PDF417 参数。包含 PDF417、MacroPDF417、MicroPDF417 和 GS1MicroPdf417 参数。MacroPDF417 需要两个字段：Pdf417MacroFileID 和 Pdf417MacroSegmentID。其他所有字段为可选。MicroPDF417 在结构化追加模式（与 MacroPDF417 模式相同）下也需要两个字段：Pdf417MacroFileID 和 Pdf417MacroSegmentID。C++ 中其他所有字段为可选。"
type: docs
weight: 4000
url: /zh/cpp/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class


PDF417 参数。包含 PDF417、MacroPDF417、MicroPDF417 和 GS1MicroPdf417 参数。MacroPDF417 需要两个字段：Pdf417MacroFileID 和 Pdf417MacroSegmentID。其他所有字段为可选。MicroPDF417 在结构化追加模式（与 MacroPDF417 模式相同）下需要两个字段：Pdf417MacroFileID 和 Pdf417MacroSegmentID。其他所有字段为可选。

```cpp
class Pdf417Parameters : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) 模块的高/宽比。 |
| [get_Columns](./get_columns/)() const | 列数。 |
| [get_ECIEncoding](./get_eciencoding/)() const | 扩展通道解释标识符。它用于向条码读取器提供有关在符号中对数据进行编码所使用的参考的详细信息。不适用于 Macro PDF417 文本字段。当前实现包含所有已知的字符集编码。 |
| [get_EncodeMode](./get_encodemode/)() const | 标识 Pdf417 编码模式。默认值：Auto。 |
| [get_ErrorLevel](./get_errorlevel/)() const | 获取 [BarCode](../../aspose.barcode/) 的 Pdf417 符号类型的错误纠正级别，范围从 level0 到 level8，level0 表示无错误纠正信息，level8 表示最佳错误纠正（即更大的图像）。 |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | 只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置模式 908 和 909 中编码 FNC1，还可以编码 910 和 911，这仅表示识别的 MicroPdf417 可被解释为 Code 128。 |
| [get_IsLinked](./get_islinked/)() const | 定义了与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号时，编码 906、907、912、913、914、915 “链接” UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号时，编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。 |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [get_MacroCharacters](./get_macrocharacters/)() const | 宏字符 05 和 06 的值用于在特殊模式下实现更紧凑的编码。只能与 MicroPdf417 一起使用，并对 916 和 917 MicroPdf417 模式进行编码。默认值： [MacroCharacters.None](../barcodeclassifications/)。 |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | MacroPdf417 条码收件人名称（可选字段）。MicroPDF417 条码收件人名称（结构化追加模式的可选字段）。 |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | MacroPdf417 条码校验和（可选字段）。MicroPDF417 条码校验和（结构化追加模式的可选字段）。校验和字段包含使用 CCITT-16 多项式（x^16 + x^12 + x^5 + 1）的 16 位（2 字节）CRC 校验和值。 |
| [get_MacroPdf417ECIEncoding](./get_macropdf417eciencoding/)() const | 扩展通道解释标识符。适用于 Macro PDF417 文本字段。 |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | MacroPdf417 条码的文件 ID（必填字段）。MicroPDF417 条码的文件 ID（结构化追加模式的必填字段）。 |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | MacroPdf417 条码文件名（可选字段）。MicroPDF417 条码文件名（结构化追加模式的可选字段）。 |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | MacroPdf417 文件大小（可选字段）。MicroPDF417 文件大小（结构化追加模式的可选字段）。文件大小字段包含整个源文件的字节数。 |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | MacroPdf417 条码的段 ID（必填字段），范围从 0 到 MacroSegmentsCount - 1。MicroPDF417 条码的段 ID（结构化追加模式的必填字段）。 |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | MacroPdf417 条码段计数（可选字段）。MicroPDF417 条码段计数（结构化追加模式的可选字段）。 |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | MacroPdf417 条码发送者名称（可选字段）。MicroPDF417 条码发送者名称（结构化追加模式的可选字段）。 |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | 用于告知编码器是否向段中添加 Macro PDF417 Terminator（代码字 922）。仅在 Macro PDF417 中适用。 |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | MacroPdf417 条码时间戳（可选字段）。MicroPDF417 条码时间戳（结构化追加模式的可选字段）。 |
| [get_Rows](./get_rows/)() const | 行数。 |
| [get_Truncate](./get_truncate/)() const | Pdf417 符号类型的 [BarCode](../../aspose.barcode/) 是否被截断（以减少空间）。也称为 CompactPDF417。此模式下右行指示符和右停止图案被移除。 |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) 模块的高/宽比。 |
| [set_Columns](./set_columns/)(int32_t) | 列数。 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | 扩展通道解释标识符。它用于向条码读取器提供有关在符号中对数据进行编码所使用的参考的详细信息。不适用于 Macro PDF417 文本字段。当前实现包含所有已知的字符集编码。 |
| [set_EncodeMode](./set_encodemode/)(Pdf417EncodeMode) | 标识 Pdf417 编码模式。默认值：Auto。 |
| [set_ErrorLevel](./set_errorlevel/)(Pdf417ErrorLevel) | 设置 [BarCode](../../aspose.barcode/) 的 Pdf417 符号类型的错误纠正级别，范围从 level0 到 level8，level0 表示没有错误纠正信息，level8 表示最佳错误纠正，即更大的图片。 |
| [set_IsCode128Emulation](./set_iscode128emulation/)(bool) | 只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置模式 908 和 909 中编码 FNC1，还可以编码 910 和 911，这仅表示识别的 MicroPdf417 可被解释为 Code 128。 |
| [set_IsLinked](./set_islinked/)(bool) | 定义了与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号时，编码 906、907、912、913、914、915 “链接” UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号时，编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。 |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | 宏字符 05 和 06 的值用于在特殊模式下实现更紧凑的编码。只能与 MicroPdf417 一起使用，并对 916 和 917 MicroPdf417 模式进行编码。默认值： [MacroCharacters.None](../barcodeclassifications/)。 |
| [set_MacroPdf417Addressee](./set_macropdf417addressee/)(System::String) | MacroPdf417 条码收件人名称（可选字段）。MicroPDF417 条码收件人名称（结构化追加模式的可选字段）。 |
| [set_MacroPdf417Checksum](./set_macropdf417checksum/)(int32_t) | MacroPdf417 条码校验和（可选字段）。MicroPDF417 条码校验和（结构化追加模式的可选字段）。校验和字段包含使用 CCITT-16 多项式（x^16 + x^12 + x^5 + 1）的 16 位（2 字节）CRC 校验和值。 |
| [set_MacroPdf417ECIEncoding](./set_macropdf417eciencoding/)(ECIEncodings) | 扩展通道解释标识符。适用于 Macro PDF417 文本字段。 |
| [set_MacroPdf417FileID](./set_macropdf417fileid/)(int32_t) | MacroPdf417 条码的文件 ID（必填字段）。MicroPDF417 条码的文件 ID（结构化追加模式的必填字段）。 |
| [set_MacroPdf417FileName](./set_macropdf417filename/)(System::String) | MacroPdf417 条码文件名（可选字段）。MicroPDF417 条码文件名（结构化追加模式的可选字段）。 |
| [set_MacroPdf417FileSize](./set_macropdf417filesize/)(int32_t) | MacroPdf417 文件大小（可选字段）。MicroPDF417 文件大小（结构化追加模式的可选字段）。文件大小字段包含整个源文件的字节数。 |
| [set_MacroPdf417SegmentID](./set_macropdf417segmentid/)(int32_t) | MacroPdf417 条码的段 ID（必填字段），范围从 0 到 MacroSegmentsCount - 1。MicroPDF417 条码的段 ID（结构化追加模式的必填字段）。 |
| [set_MacroPdf417SegmentsCount](./set_macropdf417segmentscount/)(int32_t) | MacroPdf417 条码段计数（可选字段）。MicroPDF417 条码段计数（结构化追加模式的可选字段）。 |
| [set_MacroPdf417Sender](./set_macropdf417sender/)(System::String) | MacroPdf417 条码发送者名称（可选字段）。MicroPDF417 条码发送者名称（结构化追加模式的可选字段）。 |
| [set_MacroPdf417Terminator](./set_macropdf417terminator/)(Pdf417MacroTerminator) | 用于告知编码器是否向段中添加 Macro PDF417 Terminator（代码字 922）。仅在 Macro PDF417 中适用。 |
| [set_MacroPdf417TimeStamp](./set_macropdf417timestamp/)(System::DateTime) | MacroPdf417 条码时间戳（可选字段）。MicroPDF417 条码时间戳（结构化追加模式的可选字段）。 |
| [set_Rows](./set_rows/)(int32_t) | 行数。 |
| [set_Truncate](./set_truncate/)(bool) | Pdf417 符号类型的 [BarCode](../../aspose.barcode/) 是否被截断（以减少空间）。也称为 CompactPDF417。此模式下右行指示符和右停止图案被移除。 |
| [ToString](./tostring/)() const override | 返回此 [Pdf417Parameters](./) 的人类可读字符串表示。 |
## 备注


这些示例展示了如何在 GS1MicroPdf417 中编码 UCC/EAN-128 非链接模式。
```cpp
[C#]
//编码 GS1 UCC/EAN-128 非链接模式 905，使用 AI 01（GTIN）。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//编码 GS1 UCC/EAN-128 非链接模式 903、904，使用任意 AI。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
