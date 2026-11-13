---
title: "Pdf417Parameters"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.generation/pdf417parameters/
---

## Pdf417Parameters class

PDF417 参数。包含 PDF417、MacroPDF417、MicroPDF417 和 GS1MicroPdf417 参数。<br/>            MacroPDF417 需要两个字段：Pdf417MacroFileID 和 Pdf417MacroSegmentID。其他字段均为可选。<br/>            在结构化追加模式下的 MicroPDF417（与 MacroPDF417 模式相同）需要两个字段：Pdf417MacroFileID 和 Pdf417MacroSegmentID。其他字段均为可选。

Pdf417Parameters 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| encode_mode | 标识 Pdf417 编码模式。<br/>            默认值：Auto。 |
| error_level | 获取或设置 BarCode 的 Pdf417 符号错误纠正级别<br/>            范围从 level0 到 level8，level0 表示没有错误纠正信息，<br/>            level8 表示最佳错误纠正，即更大的图像。 |
| truncate | 指示 BarCode 的 Pdf417 符号是否被截断（以减少空间）。<br/>            也称为 CompactPDF417。此模式下右行指示器和右停止图案被移除。 |
| 列 | 列计数。 |
| 行 | 行计数。 |
| aspect_ratio | 2D 条码模块的高/宽比例。 |
| macro_pdf_417_file_id | MacroPdf417 条码的文件 ID（必填字段）。<br/>            MicroPDF417 条码的文件 ID（结构化追加模式下的必填字段） |
| macro_pdf_417_segment_id | MacroPdf417 条码的段 ID（必填字段），范围从 0 到 MacroSegmentsCount - 1。<br/>            MicroPDF417 条码的段 ID（结构化追加模式下的必填字段） |
| macro_pdf_417_segments_count | MacroPdf417 条码的段计数（可选字段）。<br/>            MicroPDF417 条码的段计数（结构化追加模式下的可选字段） |
| macro_pdf_417_file_name | MacroPdf417 条码的文件名（可选字段）。<br/>            MicroPDF417 条码的文件名（结构化追加模式下的可选字段） |
| macro_pdf_417_time_stamp | MacroPdf417 条码的时间戳（可选字段）。<br/>            MicroPDF417 条码的时间戳（结构化追加模式下的可选字段） |
| macro_pdf_417_sender | MacroPdf417 条码的发送者名称（可选字段）。<br/>            MicroPDF417 条码的发送者名称（结构化追加模式下的可选字段） |
| macro_pdf_417_addressee | MacroPdf417 条码的收件人名称（可选字段）。<br/>            MicroPDF417 条码的收件人名称（结构化追加模式下的可选字段） |
| macro_pdf_417_file_size | MacroPdf417 文件大小（可选字段）。<br/>            MicroPDF417 文件大小（结构追加模式的可选字段）<br/>            文件大小字段包含整个源文件的字节数。 |
| macro_pdf_417_checksum | MacroPdf417 条形码校验和（可选字段）。<br/>            MicroPDF417 条形码校验和（结构追加模式的可选字段）<br/>            校验和字段包含使用 CCITT-16 多项式的 16 位（2 字节）CRC 校验和值。x^16 + x^12 + x^5 + 1 |
| eci_encoding | 扩展通道解释标识符。它用于向条码阅读器提供有关用于在符号中编码数据的引用的详细信息<br/>            不适用于 Macro PDF417 文本字段。<br/>            当前实现包含所有已知的字符集编码。 |
| macro_pdf_417eci_encoding | 扩展通道解释标识符。适用于 Macro PDF417 文本字段。 |
| macro_pdf_417_terminator | 用于告知编码器是否向段中添加宏 PDF417 终止符（代码字 922）。<br/>            仅适用于宏 PDF417。 |
| is_reader_initialization | 用于指示读取器将符号中包含的数据<br/>            解释为读取器初始化的编程。 |
| macro_characters | 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。<br/>            只能与 MicroPdf417 一起使用，并对 916 和 917 MicroPdf417 模式进行编码<br/>            默认值：MacroCharacters.None。 |
| is_linked | 定义与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式<br/>            使用 GS1MicroPdf417 符号编码 906、907、912、913、914、915 “链接” UCC/EAN-128 模式<br/>            使用 MicroPdf417 和 Pdf417 符号编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件 |
| is_code_128_emulation | 只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码<br/>            可以在第二位置模式 908 和 909 中编码 FNC1，也可以编码 910 和 911，这仅表示已识别的 MicroPdf417 可以解释为 Code 128 |

### 另见

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

