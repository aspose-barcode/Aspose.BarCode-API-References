---
title: "Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "PDF417 参数。"
type: docs
weight: 770
url: /zh/nodejs/aspose.barcode/pdf417parameters/
---

## Pdf417Parameters class

PDF417 参数。包含 PDF417、MacroPDF417、MicroPDF417 和 GS1MicroPdf417 参数。MacroPDF417 需要两个字段：Pdf417MacroFileID 和 Pdf417MacroSegmentID。所有其他字段为可选。MicroPDF417 在结构化追加模式（与 MacroPDF417 模式相同）下也需要两个字段：Pdf417MacroFileID 和 Pdf417MacroSegmentID。所有其他字段为可选。这些示例展示了如何在 GS1MicroPdf417 中编码 UCC/EAN-128 非链接模式。

```js
new Pdf417Parameters()
```

**Example:**

```js
# Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log( result.getCodeText());
}
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | 2D 条形码模块的高宽比。 |
| [getColumns()](#getcolumns) | 列数。 |
| [getECIEncoding()](#geteciencoding) | 扩展通道解释标识符。用于向条码读取器提供有关所使用参考的详细信息。 |
| [getEncodeMode()](#getencodemode) | 标识 Pdf417 编码模式。默认值：Auto。 |
| [getErrorLevel()](#geterrorlevel) | 获取 BarCode 的 Pdf417 符号类型的错误纠正级别，范围从 level0 到 level8，level0 表示无错误纠正。 |
| [getMacroCharacters()](#getmacrocharacters) | 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 Micro 一起使用。 |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | MacroPdf417 条码收件人名称（可选字段）。MicroPDF417 条码收件人名称（结构化 A 的可选字段） |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | MacroPdf417 条码校验和（可选字段）。MicroPDF417 条码校验和（结构化追加模式的可选字段） |
| [getMacroPdf417ECIEncoding()](#getmacropdf417eciencoding) | 扩展通道解释标识符。适用于 Macro PDF417 文本字段。 |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | MacroPdf417 条码的文件 ID（必填字段）。MicroPDF417 条码的文件 ID（结构化追加模式的必填字段） |
| [getMacroPdf417FileName()](#getmacropdf417filename) | MacroPdf417 条码文件名（可选字段）。MicroPDF417 条码文件名（结构化追加模式的可选字段） |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | MacroPdf417 文件大小（可选字段）。MicroPDF417 文件大小（结构化追加模式的可选字段）文件大小 |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | MacroPdf417 条码的段 ID（必填字段），范围从 0 到 MacroSegmentsCount - 1。MicroPDF417 条码的 |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | MacroPdf417 条码段计数（可选字段）。MicroPDF417 条码段计数（结构化 A 的可选字段） |
| [getMacroPdf417Sender()](#getmacropdf417sender) | MacroPdf417 条码发送者名称（可选字段）。MicroPDF417 条码发送者名称（结构化追加的可选字段） |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | 用于告知编码器是否在段中添加 Macro PDF417 终止符（codeword 922）。仅在 Macro PD 中适用。 |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | MacroPdf417 条码时间戳（可选字段）。MicroPDF417 条码时间戳（结构化追加模式的可选字段） |
| [getPdf417CompactionMode()](#getpdf417compactionmode) | Pdf417 条码的压缩模式符号类型。默认值：Pdf417CompactionMode.AUTO。 |
| [getPdf417ECIEncoding()](#getpdf417eciencoding) ~~(deprecated)~~ | 扩展通道解释标识符。用于向条码读取器提供有关所使用参考的详细信息。 |
| [getPdf417EncodeMode()](#getpdf417encodemode) | 标识 Pdf417 编码模式。默认值：Auto。 |
| [getPdf417ErrorLevel()](#getpdf417errorlevel) ~~(deprecated)~~ | 获取 BarCode 的 Pdf417 符号类型的错误纠正级别，范围从 level0 到 level8，level0 表示无错误纠正。 |
| [getPdf417MacroAddressee()](#getpdf417macroaddressee) ~~(deprecated)~~ | 获取宏 Pdf417 条码收件人名称。 |
| [getPdf417MacroChecksum()](#getpdf417macrochecksum) ~~(deprecated)~~ | 获取宏 Pdf417 条码校验和。 |
| [getPdf417MacroECIEncoding()](#getpdf417macroeciencoding) ~~(deprecated)~~ | 扩展通道解释标识符。适用于 Macro PDF417 文本字段。 |
| [getPdf417MacroFileID()](#getpdf417macrofileid) ~~(deprecated)~~ | 获取宏 Pdf417 条码的文件 ID。用于 MacroPdf417。 |
| [getPdf417MacroFileName()](#getpdf417macrofilename) ~~(deprecated)~~ | 获取宏 Pdf417 条码文件名。 |
| [getPdf417MacroFileSize()](#getpdf417macrofilesize) ~~(deprecated)~~ | 获取宏 Pdf417 文件大小。 |
| [getPdf417MacroSegmentID()](#getpdf417macrosegmentid) ~~(deprecated)~~ | 获取宏 Pdf417 条码的段 ID，范围从 0 到 MacroSegmentsCount - 1。 |
| [getPdf417MacroSegmentsCount()](#getpdf417macrosegmentscount) ~~(deprecated)~~ | 获取宏 Pdf417 条码段计数。 |
| [getPdf417MacroSender()](#getpdf417macrosender) ~~(deprecated)~~ | 获取宏 Pdf417 条码发送者名称。 |
| [getPdf417MacroTerminator()](#getpdf417macroterminator) ~~(deprecated)~~ | 用于告知编码器是否在段中添加 Macro PDF417 终止符（codeword 922）。仅在 Macro PD 中适用。 |
| [getPdf417MacroTimeStamp()](#getpdf417macrotimestamp) ~~(deprecated)~~ | 获取宏 Pdf417 条码时间戳。 |
| [getPdf417Truncate()](#getpdf417truncate) ~~(deprecated)~~ | Pdf417 条码的符号类型是否被截断（以减少空间）。 |
| [getRows()](#getrows) | 行数。 |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | 标识 DotCode 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。 |
| [getTruncate()](#gettruncate) | Pdf417 条码的符号类型是否被截断（以减少空间）。也称为 CompactPDF417。右行指示器 |
| [isCode128Emulation()](#iscode128emulation) | 只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置对模式 908 等进行 FNC1 编码 |
| [isLinked()](#islinked) | 定义了与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式，GS1MicroPdf417 符号编码 906、907 |
| [isReaderInitialization()](#isreaderinitialization) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程 |
| [setAspectRatio()](#setaspectratio) | 2D 条形码模块的高宽比。 |
| [setCode128Emulation()](#setcode128emulation) | 只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置对模式 908 等进行 FNC1 编码 |
| [setColumns()](#setcolumns) | 列数。 |
| [setECIEncoding()](#seteciencoding) | 扩展通道解释标识符。用于向条码读取器提供有关所使用参考的详细信息。 |
| [setEncodeMode()](#setencodemode) | 标识 Pdf417 编码模式。默认值：Auto。 |
| [setErrorLevel(value)](#seterrorlevel) | 设置条码的 Pdf417 符号类型的错误纠正级别，范围从 level0 到 level8，level0 表示没有错误纠正 |
| [setLinked()](#setlinked) | 定义了与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式，GS1MicroPdf417 符号编码 906、907 |
| [setMacroCharacters()](#setmacrocharacters) | 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 Micro 一起使用。 |
| [setMacroPdf417Addressee()](#setmacropdf417addressee) | MacroPdf417 条码收件人名称（可选字段）。MicroPDF417 条码收件人名称（结构化 A 的可选字段） |
| [setMacroPdf417Checksum()](#setmacropdf417checksum) | MacroPdf417 条码校验和（可选字段）。MicroPDF417 条码校验和（结构化追加模式的可选字段） |
| [setMacroPdf417ECIEncoding()](#setmacropdf417eciencoding) | 扩展通道解释标识符。适用于 Macro PDF417 文本字段。 |
| [setMacroPdf417FileID()](#setmacropdf417fileid) | MacroPdf417 条码的文件 ID（必填字段）。MicroPDF417 条码的文件 ID（结构化追加模式的必填字段） |
| [setMacroPdf417FileName()](#setmacropdf417filename) | MacroPdf417 条码文件名（可选字段）。MicroPDF417 条码文件名（结构化追加模式的可选字段） |
| [setMacroPdf417FileSize()](#setmacropdf417filesize) | MacroPdf417 文件大小（可选字段）。MicroPDF417 文件大小（结构化追加模式的可选字段）文件大小 |
| [setMacroPdf417SegmentID()](#setmacropdf417segmentid) | MacroPdf417 条码的段 ID（必填字段），范围从 0 到 MacroSegmentsCount - 1。MicroPDF417 条码的 |
| [setMacroPdf417SegmentsCount()](#setmacropdf417segmentscount) | MacroPdf417 条码段计数（可选字段）。MicroPDF417 条码段计数（结构化 A 的可选字段） |
| [setMacroPdf417Sender()](#setmacropdf417sender) | MacroPdf417 条码发送者名称（可选字段）。MicroPDF417 条码发送者名称（结构化追加的可选字段） |
| [setMacroPdf417Terminator()](#setmacropdf417terminator) | 用于告知编码器是否在段中添加 Macro PDF417 终止符（codeword 922）。仅在 Macro PD 中适用。 |
| [setMacroPdf417TimeStamp()](#setmacropdf417timestamp) | MacroPdf417 条码时间戳（可选字段）。MicroPDF417 条码时间戳（结构化追加模式的可选字段） |
| [setPdf417CompactionMode()](#setpdf417compactionmode) | Pdf417 条码的压缩模式符号类型。默认值：Pdf417CompactionMode.AUTO。 |
| [setPdf417ECIEncoding()](#setpdf417eciencoding) ~~(deprecated)~~ | 扩展通道解释标识符。用于向条码读取器提供有关所使用参考的详细信息。 |
| [setPdf417EncodeMode()](#setpdf417encodemode) ~~(deprecated)~~ | 标识 Pdf417 编码模式。默认值：Auto。 |
| [setPdf417ErrorLevel()](#setpdf417errorlevel) ~~(deprecated)~~ | 设置条码的 Pdf417 符号类型的错误纠正级别，范围从 level0 到 level8，level0 表示没有错误纠正 |
| [setPdf417MacroAddressee()](#setpdf417macroaddressee) ~~(deprecated)~~ | 设置宏 Pdf417 条码的收件人名称。 |
| [setPdf417MacroChecksum(value)](#setpdf417macrochecksum) ~~(deprecated)~~ | 设置宏 Pdf417 条码的校验和。 |
| [setPdf417MacroECIEncoding()](#setpdf417macroeciencoding) ~~(deprecated)~~ | 扩展通道解释标识符。适用于 Macro PDF417 文本字段。 |
| [setPdf417MacroFileID()](#setpdf417macrofileid) ~~(deprecated)~~ | 设置宏 Pdf417 条码的文件 ID。用于 MacroPdf417。 |
| [setPdf417MacroFileName()](#setpdf417macrofilename) ~~(deprecated)~~ | 设置宏 Pdf417 条码的文件名。 |
| [setPdf417MacroFileSize(value)](#setpdf417macrofilesize) ~~(deprecated)~~ | 设置宏 Pdf417 文件大小。 |
| [setPdf417MacroSegmentID()](#setpdf417macrosegmentid) ~~(deprecated)~~ | 设置宏 Pdf417 条码的段 ID，起始值为 0，至 MacroSegmentsCount - 1。 |
| [setPdf417MacroSegmentsCount()](#setpdf417macrosegmentscount) ~~(deprecated)~~ | 设置宏 Pdf417 条码的段计数。 |
| [setPdf417MacroSender()](#setpdf417macrosender) ~~(deprecated)~~ | 设置宏 Pdf417 条码的发送者名称。 |
| [setPdf417MacroTerminator()](#setpdf417macroterminator) ~~(deprecated)~~ | 用于告知编码器是否在段中添加 Macro PDF417 终止符（codeword 922）。仅在 Macro PD 中适用。 |
| [setPdf417MacroTimeStamp()](#setpdf417macrotimestamp) ~~(deprecated)~~ | 设置宏 Pdf417 条码的时间戳。 |
| [setPdf417Truncate()](#setpdf417truncate) ~~(deprecated)~~ | Pdf417 条码的符号类型是否被截断（以减少空间）。 |
| [setReaderInitialization(value)](#setreaderinitialization) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程 |
| [setRows()](#setrows) | 行数。 |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | 标识 DotCode 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。 |
| [setTruncate()](#settruncate) | Pdf417 条码的符号类型是否被截断（以减少空间）。也称为 CompactPDF417。右行指示器 |
| [toString()](#tostring) | 返回此 Pdf417Parameters 的可读字符串表示。 |

### getAspectRatio() {#getaspectratio}

2D 条形码模块的高宽比。

### getColumns() {#getcolumns}

列数。

### getECIEncoding() {#geteciencoding}

扩展通道解释标识符。它用于向条码读取器提供关于在符号中编码数据所使用的参考的详细信息。不适用于 Macro PDF417 文本字段。当前实现包含所有已知的字符集编码。

### getEncodeMode() {#getencodemode}

标识 Pdf417 编码模式。默认值：Auto。

### getErrorLevel() {#geterrorlevel}

获取条码的 Pdf417 符号类型的错误纠正级别，范围从 level0 到 level8，level0 表示没有错误纠正信息，level8 表示最佳错误纠正，这会导致更大的图像。

**Returns:** Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### getMacroCharacters() {#getmacrocharacters}

宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 MicroPdf417 一起使用，并编码 916 和 917 MicroPdf417 模式。默认值：MacroCharacters.None。这些示例展示了如何在 MicroPdf417 中编码宏字符。

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### getMacroPdf417Addressee() {#getmacropdf417addressee}

MacroPdf417 条码的收件人名称（可选字段）。MicroPDF417 条码的收件人名称（结构追加模式的可选字段）

### getMacroPdf417Checksum() {#getmacropdf417checksum}

MacroPdf417 条码的校验和（可选字段）。MicroPDF417 条码的校验和（结构追加模式的可选字段）校验和字段包含使用 CCITT-16 多项式（x^16 + x^12 + x^5 + 1）的 16 位（2 字节）CRC 校验和值。

### getMacroPdf417ECIEncoding() {#getmacropdf417eciencoding}

扩展通道解释标识符。适用于 Macro PDF417 文本字段。

### getMacroPdf417FileID() {#getmacropdf417fileid}

MacroPdf417 条码的文件 ID（必填字段）。MicroPDF417 条码的文件 ID（结构追加模式的必填字段）

### getMacroPdf417FileName() {#getmacropdf417filename}

MacroPdf417 条码的文件名（可选字段）。MicroPDF417 条码的文件名（结构追加模式的可选字段）

### getMacroPdf417FileSize() {#getmacropdf417filesize}

MacroPdf417 文件大小（可选字段）。MicroPDF417 文件大小（结构追加模式的可选字段）文件大小字段包含整个源文件的字节大小。

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

MacroPdf417 条码的段 ID（必填字段），起始值为 0，至 MacroSegmentsCount - 1。MicroPDF417 条码的段 ID（结构追加模式的必填字段）

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

MacroPdf417 条码的段计数（可选字段）。MicroPDF417 条码的段计数（结构追加模式的可选字段）

### getMacroPdf417Sender() {#getmacropdf417sender}

MacroPdf417 条码的发送者名称（可选字段）。MicroPDF417 条码的发送者名称（结构追加模式的可选字段）

### getMacroPdf417Terminator() {#getmacropdf417terminator}

用于告诉编码器是否在段中添加 Macro PDF417 终止符（代码字 922）。仅适用于 Macro PDF417。

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

MacroPdf417 条形码时间戳（可选字段）。MicroPDF417 条形码时间戳（结构追加模式的可选字段）

### getPdf417CompactionMode() {#getpdf417compactionmode}

Pdf417 条码的压缩模式符号类型。默认值：Pdf417CompactionMode.AUTO。

### getPdf417ECIEncoding() {#getpdf417eciencoding}

> **Deprecated.** See method description for replacement.

扩展通道解释标识符。它用于向条码阅读器提供有关在符号中对数据进行编码所使用的参考的详细信息。当前实现包括所有已知的字符集编码。

### getPdf417EncodeMode() {#getpdf417encodemode}

标识 Pdf417 编码模式。默认值：Auto。

### getPdf417ErrorLevel() {#getpdf417errorlevel}

> **Deprecated.** See method description for replacement.

获取条码的 Pdf417 符号类型的错误纠正级别，范围从 level0 到 level8，level0 表示没有错误纠正信息，level8 表示最佳错误纠正，这会导致更大的图像。

### getPdf417MacroAddressee() {#getpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

获取宏 Pdf417 条码收件人名称。

### getPdf417MacroChecksum() {#getpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

获取宏 Pdf417 条码校验和。

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

### getPdf417MacroECIEncoding() {#getpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

扩展通道解释标识符。适用于 Macro PDF417 文本字段。

### getPdf417MacroFileID() {#getpdf417macrofileid}

> **Deprecated.** See method description for replacement.

获取宏 Pdf417 条码的文件 ID。用于 MacroPdf417。

### getPdf417MacroFileName() {#getpdf417macrofilename}

> **Deprecated.** See method description for replacement.

获取宏 Pdf417 条码文件名。

### getPdf417MacroFileSize() {#getpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

获取宏 Pdf417 文件大小。

**Returns:** The file size field contains the size in bytes of the entire source file.

### getPdf417MacroSegmentID() {#getpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

获取宏 Pdf417 条码的段 ID，范围从 0 到 MacroSegmentsCount - 1。

### getPdf417MacroSegmentsCount() {#getpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

获取宏 Pdf417 条码段计数。

### getPdf417MacroSender() {#getpdf417macrosender}

> **Deprecated.** See method description for replacement.

获取宏 Pdf417 条码发送者名称。

### getPdf417MacroTerminator() {#getpdf417macroterminator}

> **Deprecated.** See method description for replacement.

用于告诉编码器是否在段中添加 Macro PDF417 终止符（代码字 922）。仅适用于 Macro PDF417。

### getPdf417MacroTimeStamp() {#getpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

获取宏 Pdf417 条码时间戳。

### getPdf417Truncate() {#getpdf417truncate}

> **Deprecated.** See method description for replacement.

Pdf417 条码的符号类型是否被截断（以减少空间）。

### getRows() {#getrows}

行数。

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

标识 DotCode 结构追加模式条形码的 ID。ID 从 1 开始，且必须小于或等于条形码数量。默认值为 -1。

### getTruncate() {#gettruncate}

指示 BarCode 的 Pdf417 符号类型是否被截断（以减少空间）。也称为 CompactPDF417。在此模式下，右行指示符和右停止图案被移除。

### isCode128Emulation() {#iscode128emulation}

只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置对模式 908 和 909 编码 FNC1，也可以编码 910 和 911，这仅表示识别的 MicroPdf417 可以解释为 Code 128。这些示例展示了如何在第二位置使用或不使用 FNC1 来编码 Code 128 仿真模式。通过这种方式，MicroPdf417 可以被解码为 Code 128 条形码。

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### isLinked() {#islinked}

定义了与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条形码的链接模式。使用 GS1MicroPdf417 符号可编码 906、907、912、913、914、915 “链接” UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号可编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。这些示例展示了如何在 GS1MicroPdf417 中编码 “链接” UCC/EAN-128 模式，以及在 MicroPdf417 和 Pdf417 条形码中编码链接标志 (918)。

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### isReaderInitialization() {#isreaderinitialization}

用于指示读取器将符号中包含的数据解释为读取器初始化的编程

**Returns:** boolean value

### setAspectRatio() {#setaspectratio}

2D 条形码模块的高宽比。

### setCode128Emulation() {#setcode128emulation}

只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置对模式 908 和 909 编码 FNC1，也可以编码 910 和 911，这仅表示识别的 MicroPdf417 可以解释为 Code 128。这些示例展示了如何在第二位置使用或不使用 FNC1 来编码 Code 128 仿真模式。通过这种方式，MicroPdf417 可以被解码为 Code 128 条形码。

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### setColumns() {#setcolumns}

列数。

### setECIEncoding() {#seteciencoding}

扩展通道解释标识符。它用于向条码读取器提供关于在符号中编码数据所使用的参考的详细信息。不适用于 Macro PDF417 文本字段。当前实现包含所有已知的字符集编码。

### setEncodeMode() {#setencodemode}

标识 Pdf417 编码模式。默认值：Auto。

### setErrorLevel(value) {#seterrorlevel}

设置 BarCode 的 Pdf417 符号的错误更正级别，范围从 level0 到 level8，level0 表示没有错误更正信息，level8 表示最佳错误更正，即更大的图像。

| 参数 | 描述 |
| --- | --- |
| 值 | BarCode 的 Pdf417 符号的错误更正级别，范围从 level0 到 level8，level0 表示没有错误更正信息，level8 表示最佳错误更正，即更大的图像。 |

### setLinked() {#setlinked}

定义了与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条形码的链接模式。使用 GS1MicroPdf417 符号可编码 906、907、912、913、914、915 “链接” UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号可编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。这些示例展示了如何在 GS1MicroPdf417 中编码 “链接” UCC/EAN-128 模式，以及在 MicroPdf417 和 Pdf417 条形码中编码链接标志 (918)。

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### setMacroCharacters() {#setmacrocharacters}

宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 MicroPdf417 一起使用，并编码 916 和 917 MicroPdf417 模式。默认值：MacroCharacters.None。这些示例展示了如何在 MicroPdf417 中编码宏字符。

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### setMacroPdf417Addressee() {#setmacropdf417addressee}

MacroPdf417 条码的收件人名称（可选字段）。MicroPDF417 条码的收件人名称（结构追加模式的可选字段）

### setMacroPdf417Checksum() {#setmacropdf417checksum}

MacroPdf417 条码的校验和（可选字段）。MicroPDF417 条码的校验和（结构追加模式的可选字段）校验和字段包含使用 CCITT-16 多项式（x^16 + x^12 + x^5 + 1）的 16 位（2 字节）CRC 校验和值。

### setMacroPdf417ECIEncoding() {#setmacropdf417eciencoding}

扩展通道解释标识符。适用于 Macro PDF417 文本字段。

### setMacroPdf417FileID() {#setmacropdf417fileid}

MacroPdf417 条码的文件 ID（必填字段）。MicroPDF417 条码的文件 ID（结构追加模式的必填字段）

### setMacroPdf417FileName() {#setmacropdf417filename}

MacroPdf417 条码的文件名（可选字段）。MicroPDF417 条码的文件名（结构追加模式的可选字段）

### setMacroPdf417FileSize() {#setmacropdf417filesize}

MacroPdf417 文件大小（可选字段）。MicroPDF417 文件大小（结构追加模式的可选字段）文件大小字段包含整个源文件的字节大小。

### setMacroPdf417SegmentID() {#setmacropdf417segmentid}

MacroPdf417 条码的段 ID（必填字段），起始值为 0，至 MacroSegmentsCount - 1。MicroPDF417 条码的段 ID（结构追加模式的必填字段）

### setMacroPdf417SegmentsCount() {#setmacropdf417segmentscount}

MacroPdf417 条码的段计数（可选字段）。MicroPDF417 条码的段计数（结构追加模式的可选字段）

### setMacroPdf417Sender() {#setmacropdf417sender}

MacroPdf417 条码的发送者名称（可选字段）。MicroPDF417 条码的发送者名称（结构追加模式的可选字段）

### setMacroPdf417Terminator() {#setmacropdf417terminator}

用于告诉编码器是否在段中添加 Macro PDF417 终止符（代码字 922）。仅适用于 Macro PDF417。

### setMacroPdf417TimeStamp() {#setmacropdf417timestamp}

MacroPdf417 条形码时间戳（可选字段）。MicroPDF417 条形码时间戳（结构追加模式的可选字段）

### setPdf417CompactionMode() {#setpdf417compactionmode}

Pdf417 条码的压缩模式符号类型。默认值：Pdf417CompactionMode.AUTO。

### setPdf417ECIEncoding() {#setpdf417eciencoding}

> **Deprecated.** See method description for replacement.

扩展通道解释标识符。它用于向条码阅读器提供有关在符号中对数据进行编码所使用的参考的详细信息。当前实现包括所有已知的字符集编码。

### setPdf417EncodeMode() {#setpdf417encodemode}

> **Deprecated.** See method description for replacement.

标识 Pdf417 编码模式。默认值：Auto。

### setPdf417ErrorLevel() {#setpdf417errorlevel}

> **Deprecated.** See method description for replacement.

设置 BarCode 的 Pdf417 符号的错误更正级别，范围从 level0 到 level8，level0 表示没有错误更正信息，level8 表示最佳错误更正，即更大的图像。

### setPdf417MacroAddressee() {#setpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

设置宏 Pdf417 条码的收件人名称。

### setPdf417MacroChecksum(value) {#setpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

设置宏 Pdf417 条码的校验和。

| 参数 | 描述 |
| --- | --- |
| 值 | 校验和字段包含使用 CCITT-16 多项式的 16 位（2 字节）CRC 校验和值。 |

### setPdf417MacroECIEncoding() {#setpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

扩展通道解释标识符。适用于 Macro PDF417 文本字段。

### setPdf417MacroFileID() {#setpdf417macrofileid}

> **Deprecated.** See method description for replacement.

设置宏 Pdf417 条码的文件 ID。用于 MacroPdf417。

### setPdf417MacroFileName() {#setpdf417macrofilename}

> **Deprecated.** See method description for replacement.

设置宏 Pdf417 条码的文件名。

### setPdf417MacroFileSize(value) {#setpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

设置宏 Pdf417 文件大小。

| 参数 | 描述 |
| --- | --- |
| 值 | 文件大小字段包含整个源文件的字节大小。 |

### setPdf417MacroSegmentID() {#setpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

设置宏 Pdf417 条码的段 ID，起始值为 0，至 MacroSegmentsCount - 1。

### setPdf417MacroSegmentsCount() {#setpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

设置宏 Pdf417 条码的段计数。

### setPdf417MacroSender() {#setpdf417macrosender}

> **Deprecated.** See method description for replacement.

设置宏 Pdf417 条码的发送者名称。

### setPdf417MacroTerminator() {#setpdf417macroterminator}

> **Deprecated.** See method description for replacement.

用于告诉编码器是否在段中添加 Macro PDF417 终止符（代码字 922）。仅适用于 Macro PDF417。

### setPdf417MacroTimeStamp() {#setpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

设置宏 Pdf417 条码的时间戳。

### setPdf417Truncate() {#setpdf417truncate}

> **Deprecated.** See method description for replacement.

Pdf417 条码的符号类型是否被截断（以减少空间）。

### setReaderInitialization(value) {#setreaderinitialization}

用于指示读取器将符号中包含的数据解释为读取器初始化的编程

| 参数 | 描述 |
| --- | --- |
| 值 |  |

### setRows() {#setrows}

行数。

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

标识 DotCode 结构追加模式条形码的 ID。ID 从 1 开始，且必须小于或等于条形码数量。默认值为 -1。

### setTruncate() {#settruncate}

指示 BarCode 的 Pdf417 符号类型是否被截断（以减少空间）。也称为 CompactPDF417。在此模式下，右行指示符和右停止图案被移除。

### toString() {#tostring}

返回此 Pdf417Parameters 的可读字符串表示。

**Returns:** A string that represents this Pdf417Parameters.
