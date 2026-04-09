---
title: Pdf417Parameters
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: PDF417 参数。
type: docs
weight: 60
url: /zh/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

PDF417 参数。包含 PDF417、MacroPDF417、MicroPDF417 和 GS1MicroPdf417 参数。MacroPDF417 需要两个字段：Pdf417MacroFileID 和 Pdf417MacroSegmentID。其他所有字段为可选。MicroPDF417 在结构化追加模式（与 MacroPDF417 模式相同）下也需要两个字段：Pdf417MacroFileID 和 Pdf417MacroSegmentID。其他所有字段为可选。

这些示例展示了如何在 GS1MicroPdf417 中编码 UCC/EAN-128 非链接模式。

```

 [C#]
 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D 条码模块的高/宽比。 |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | 列数。 |
| [getECIEncoding()](#getECIEncoding--) | 扩展通道解释标识符。 |
| [getEncodeMode()](#getEncodeMode--) | 标识 Pdf417 编码模式。 |
| [getErrorLevel()](#getErrorLevel--) | 获取 BarCode 的错误纠正级别对应的 Pdf417 符号类型，范围从 level0 到 level8，level0 表示无错误纠正信息，level8 表示最佳错误纠正，即更大的图像。 |
| [getMacroCharacters()](#getMacroCharacters--) | 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。 |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | MacroPdf417 条形码收件人名称（可选字段）。 |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | MacroPdf417 条形码校验和（可选字段）。 |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | 扩展通道解释标识符。 |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | MacroPdf417 条形码的文件 ID（必填字段）。 |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417 条形码文件名（可选字段）。 |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417 文件大小（可选字段）。 |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | MacroPdf417 条形码的段 ID（必填字段），起始值为 0，至 MacroSegmentsCount - 1。 |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | MacroPdf417 条形码段计数（可选字段）。 |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | MacroPdf417 条形码发送者名称（可选字段）。 |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | 用于告诉编码器是否在段中添加宏 PDF417 终止符（代码字 922）。 |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | MacroPdf417 条形码时间戳（可选字段）。 |
| [getPdf417CompactionMode()](#getPdf417CompactionMode--) | Pdf417 条码的压缩模式的符号类型。 |
| [getPdf417ECIEncoding()](#getPdf417ECIEncoding--) | 扩展通道解释标识符。 |
| [getPdf417EncodeMode()](#getPdf417EncodeMode--) | 标识 Pdf417 编码模式。 |
| [getPdf417ErrorLevel()](#getPdf417ErrorLevel--) | 获取 BarCode 的错误纠正级别对应的 Pdf417 符号类型，范围从 level0 到 level8，level0 表示无错误纠正信息，level8 表示最佳错误纠正，即更大的图像。 |
| [getPdf417MacroAddressee()](#getPdf417MacroAddressee--) | MacroPdf417 条形码收件人名称（可选字段）。 |
| [getPdf417MacroChecksum()](#getPdf417MacroChecksum--) | MacroPdf417 条形码校验和（可选字段）。 |
| [getPdf417MacroECIEncoding()](#getPdf417MacroECIEncoding--) | 扩展通道解释标识符。 |
| [getPdf417MacroFileID()](#getPdf417MacroFileID--) | MacroPdf417 条形码的文件 ID（必填字段）。 |
| [getPdf417MacroFileName()](#getPdf417MacroFileName--) | MacroPdf417 条形码文件名（可选字段）。 |
| [getPdf417MacroFileSize()](#getPdf417MacroFileSize--) | MacroPdf417 文件大小（可选字段）。 |
| [getPdf417MacroSegmentID()](#getPdf417MacroSegmentID--) | MacroPdf417 条形码的段 ID（必填字段），起始值为 0，至 MacroSegmentsCount - 1。 |
| [getPdf417MacroSegmentsCount()](#getPdf417MacroSegmentsCount--) | MacroPdf417 条形码段计数（可选字段）。 |
| [getPdf417MacroSender()](#getPdf417MacroSender--) | MacroPdf417 条形码发送者名称（可选字段）。 |
| [getPdf417MacroTerminator()](#getPdf417MacroTerminator--) | 用于告诉编码器是否在段中添加宏 PDF417 终止符（代码字 922）。 |
| [getPdf417MacroTimeStamp()](#getPdf417MacroTimeStamp--) | MacroPdf417 条形码时间戳（可选字段）。 |
| [getPdf417Truncate()](#getPdf417Truncate--) | Pdf417 条码的符号类型是否被截断（以减少空间）。 |
| [getRows()](#getRows--) | 行数。 |
| [getTruncate()](#getTruncate--) | Pdf417 条码的符号类型是否被截断（以减少空间）。 |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | 只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置对模式 908 和 909 编码 FNC1，也可以编码 910 和 911，这仅表示识别的 MicroPdf417 可解释为 Code 128。 |
| [isLinked()](#isLinked--) | 定义与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号时编码 906、907、912、913、914、915 \u201cLinked\u201d UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号时编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。 |
| [isReaderInitialization()](#isReaderInitialization--) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D 条码模块的高/宽比。 |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | 只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置对模式 908 和 909 编码 FNC1，也可以编码 910 和 911，这仅表示识别的 MicroPdf417 可解释为 Code 128。 |
| [setColumns(int value)](#setColumns-int-) | 列数。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 扩展通道解释标识符。 |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | 标识 Pdf417 编码模式。 |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | 设置 Pdf417 条码的错误更正级别，范围从 level0 到 level8，level0 表示没有错误更正信息，level8 表示最佳错误更正，即图像更大。 |
| [setLinked(boolean value)](#setLinked-boolean-) | 定义与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号时编码 906、907、912、913、914、915 \u201cLinked\u201d UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号时编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。 |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。 |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | MacroPdf417 条形码收件人名称（可选字段）。 |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | MacroPdf417 条形码校验和（可选字段）。 |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | 扩展通道解释标识符。 |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | MacroPdf417 条形码的文件 ID（必填字段）。 |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417 条形码文件名（可选字段）。 |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417 文件大小（可选字段）。 |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | MacroPdf417 条形码的段 ID（必填字段），起始值为 0，至 MacroSegmentsCount - 1。 |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | MacroPdf417 条形码段计数（可选字段）。 |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | MacroPdf417 条形码发送者名称（可选字段）。 |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | 用于告诉编码器是否在段中添加宏 PDF417 终止符（代码字 922）。 |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | MacroPdf417 条形码时间戳（可选字段）。 |
| [setPdf417CompactionMode(Pdf417CompactionMode value)](#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-) | Pdf417 条码的压缩模式的符号类型。 |
| [setPdf417ECIEncoding(int value)](#setPdf417ECIEncoding-int-) | 扩展通道解释标识符。 |
| [setPdf417EncodeMode(Pdf417EncodeMode value)](#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | 标识 Pdf417 编码模式。 |
| [setPdf417ErrorLevel(Pdf417ErrorLevel value)](#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | 设置 Pdf417 条码的错误更正级别，范围从 level0 到 level8，level0 表示没有错误更正信息，level8 表示最佳错误更正，即图像更大。 |
| [setPdf417MacroAddressee(String value)](#setPdf417MacroAddressee-java.lang.String-) | MacroPdf417 条形码收件人名称（可选字段）。 |
| [setPdf417MacroChecksum(int value)](#setPdf417MacroChecksum-int-) | MacroPdf417 条形码校验和（可选字段）。 |
| [setPdf417MacroECIEncoding(int value)](#setPdf417MacroECIEncoding-int-) | 扩展通道解释标识符。 |
| [setPdf417MacroFileID(int value)](#setPdf417MacroFileID-int-) | MacroPdf417 条形码的文件 ID（必填字段）。 |
| [setPdf417MacroFileName(String value)](#setPdf417MacroFileName-java.lang.String-) | MacroPdf417 条形码文件名（可选字段）。 |
| [setPdf417MacroFileSize(int value)](#setPdf417MacroFileSize-int-) | MacroPdf417 文件大小（可选字段）。 |
| [setPdf417MacroSegmentID(int value)](#setPdf417MacroSegmentID-int-) | MacroPdf417 条形码的段 ID（必填字段），起始值为 0，至 MacroSegmentsCount - 1。 |
| [setPdf417MacroSegmentsCount(int value)](#setPdf417MacroSegmentsCount-int-) | MacroPdf417 条形码段计数（可选字段）。 |
| [setPdf417MacroSender(String value)](#setPdf417MacroSender-java.lang.String-) | MacroPdf417 条形码发送者名称（可选字段）。 |
| [setPdf417MacroTerminator(Pdf417MacroTerminator value)](#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | 用于告诉编码器是否在段中添加宏 PDF417 终止符（代码字 922）。 |
| [setPdf417MacroTimeStamp(LocalDateTime value)](#setPdf417MacroTimeStamp-java.time.LocalDateTime-) | MacroPdf417 条形码时间戳（可选字段）。 |
| [setPdf417Truncate(boolean value)](#setPdf417Truncate-boolean-) | Pdf417 条码的符号类型是否被截断（以减少空间）。 |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [setRows(int value)](#setRows-int-) | 行数。 |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Pdf417 条码的符号类型是否被截断（以减少空间）。 |
| [toString()](#toString--) | 返回此 [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) 的可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


2D 条码模块的高/宽比。

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public final int getColumns()
```


列数。

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


扩展通道解释标识符。用于向条码读取器提供有关在符号中编码数据所使用的引用的详细信息。不适用于 Macro PDF417 文本字段。当前实现包含所有已知的字符集编码。

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


标识 Pdf417 编码模式。默认值：Auto。

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


获取 BarCode 的错误纠正级别对应的 Pdf417 符号类型，范围从 level0 到 level8，level0 表示无错误纠正信息，level8 表示最佳错误纠正，即更大的图像。

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 MicroPdf417 一起使用，并对 916 和 917 MicroPdf417 模式进行编码。默认值：MacroCharacters.None。

这些示例展示了如何在 MicroPdf417 中编码宏字符。

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


MacroPdf417 条码收件人名称（可选字段）。MicroPDF417 条码收件人名称（结构追加模式的可选字段）。

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


MacroPdf417 条码校验和（可选字段）。MicroPDF417 条码校验和（结构追加模式的可选字段）。校验和字段包含使用 CCITT-16 多项式（x^16 + x^12 + x^5 + 1）的 16 位（2 字节）CRC 校验值。

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


扩展通道解释标识符。适用于 Macro PDF417 文本字段。

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


MacroPdf417 条码的文件 ID（必填字段）。MicroPDF417 条码的文件 ID（结构追加模式的必填字段）。

**Returns:**
int
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


MacroPdf417 条码文件名（可选字段）。MicroPDF417 条码文件名（结构追加模式的可选字段）。

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


MacroPdf417 文件大小（可选字段）。MicroPDF417 文件大小（结构追加模式的可选字段）。文件大小字段包含整个源文件的字节大小。

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


MacroPdf417 条码的段 ID（必填字段），起始值为 0，至 MacroSegmentsCount - 1。MicroPDF417 条码的段 ID（结构追加模式的必填字段）。

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


MacroPdf417 条码段计数（可选字段）。MicroPDF417 条码段计数（结构追加模式的可选字段）。

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


MacroPdf417 条码发送者名称（可选字段）。MicroPDF417 条码发送者名称（结构追加模式的可选字段）。

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


用于告诉编码器是否在段中添加 Macro PDF417 Terminator（代码字 922）。仅适用于 Macro PDF417。

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


MacroPdf417 条形码时间戳（可选字段）。MicroPDF417 条形码时间戳（结构追加模式的可选字段）

**Returns:**
java.time.LocalDateTime
### getPdf417CompactionMode() {#getPdf417CompactionMode--}
```
public final Pdf417CompactionMode getPdf417CompactionMode()
```


Pdf417 条码符号的压缩模式。默认值：Pdf417CompactionMode.Auto。

**Returns:**
[Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode)
### getPdf417ECIEncoding() {#getPdf417ECIEncoding--}
```
public final int getPdf417ECIEncoding()
```


扩展通道解释标识符。用于向条码读取器提供有关在符号中编码数据所使用的引用的详细信息。不适用于 Macro PDF417 文本字段。当前实现包含所有已知的字符集编码。

**Returns:**
int
### getPdf417EncodeMode() {#getPdf417EncodeMode--}
```
public final Pdf417EncodeMode getPdf417EncodeMode()
```


标识 Pdf417 编码模式。默认值：Auto。

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getPdf417ErrorLevel() {#getPdf417ErrorLevel--}
```
public final Pdf417ErrorLevel getPdf417ErrorLevel()
```


获取 BarCode 的错误纠正级别对应的 Pdf417 符号类型，范围从 level0 到 level8，level0 表示无错误纠正信息，level8 表示最佳错误纠正，即更大的图像。

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getPdf417MacroAddressee() {#getPdf417MacroAddressee--}
```
public final String getPdf417MacroAddressee()
```


MacroPdf417 条码收件人名称（可选字段）。MicroPDF417 条码收件人名称（结构追加模式的可选字段）。

**Returns:**
java.lang.String
### getPdf417MacroChecksum() {#getPdf417MacroChecksum--}
```
public final int getPdf417MacroChecksum()
```


MacroPdf417 条码校验和（可选字段）。MicroPDF417 条码校验和（结构追加模式的可选字段）。校验和字段包含使用 CCITT-16 多项式（x^16 + x^12 + x^5 + 1）的 16 位（2 字节）CRC 校验值。

**Returns:**
int
### getPdf417MacroECIEncoding() {#getPdf417MacroECIEncoding--}
```
public final int getPdf417MacroECIEncoding()
```


扩展通道解释标识符。适用于 Macro PDF417 文本字段。

**Returns:**
int
### getPdf417MacroFileID() {#getPdf417MacroFileID--}
```
public final int getPdf417MacroFileID()
```


MacroPdf417 条码的文件 ID（必填字段）。MicroPDF417 条码的文件 ID（结构追加模式的必填字段）。

**Returns:**
int
### getPdf417MacroFileName() {#getPdf417MacroFileName--}
```
public final String getPdf417MacroFileName()
```


MacroPdf417 条码文件名（可选字段）。MicroPDF417 条码文件名（结构追加模式的可选字段）。

**Returns:**
java.lang.String
### getPdf417MacroFileSize() {#getPdf417MacroFileSize--}
```
public final int getPdf417MacroFileSize()
```


MacroPdf417 文件大小（可选字段）。MicroPDF417 文件大小（结构追加模式的可选字段）。文件大小字段包含整个源文件的字节大小。

**Returns:**
int
### getPdf417MacroSegmentID() {#getPdf417MacroSegmentID--}
```
public final int getPdf417MacroSegmentID()
```


MacroPdf417 条码的段 ID（必填字段），起始值为 0，至 MacroSegmentsCount - 1。MicroPDF417 条码的段 ID（结构追加模式的必填字段）。

**Returns:**
int
### getPdf417MacroSegmentsCount() {#getPdf417MacroSegmentsCount--}
```
public final int getPdf417MacroSegmentsCount()
```


MacroPdf417 条码段计数（可选字段）。MicroPDF417 条码段计数（结构追加模式的可选字段）。

**Returns:**
int
### getPdf417MacroSender() {#getPdf417MacroSender--}
```
public final String getPdf417MacroSender()
```


MacroPdf417 条码发送者名称（可选字段）。MicroPDF417 条码发送者名称（结构追加模式的可选字段）。

**Returns:**
java.lang.String
### getPdf417MacroTerminator() {#getPdf417MacroTerminator--}
```
public final Pdf417MacroTerminator getPdf417MacroTerminator()
```


用于告诉编码器是否在段中添加 Macro PDF417 Terminator（代码字 922）。仅适用于 Macro PDF417。

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getPdf417MacroTimeStamp() {#getPdf417MacroTimeStamp--}
```
public final LocalDateTime getPdf417MacroTimeStamp()
```


MacroPdf417 条形码时间戳（可选字段）。MicroPDF417 条形码时间戳（结构追加模式的可选字段）

**Returns:**
java.time.LocalDateTime
### getPdf417Truncate() {#getPdf417Truncate--}
```
public final boolean getPdf417Truncate()
```


Pdf417 条码符号是否被截断（以减少空间）。也称为 CompactPDF417。在此模式下，右行指示器和右停止图案被移除。

**Returns:**
boolean
### getRows() {#getRows--}
```
public final int getRows()
```


行数。

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


Pdf417 条码符号是否被截断（以减少空间）。也称为 CompactPDF417。在此模式下，右行指示器和右停止图案被移除。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置对模式 908 和 909 编码 FNC1，也可以编码 910 和 911，这仅表示识别的 MicroPdf417 可解释为 Code 128。

这些示例展示了如何在第二位使用或不使用 FNC1 来编码 Code 128 仿真模式。通过这种方式，MicroPdf417 可以被解码为 Code 128 条码。

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


定义与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号时编码 906、907、912、913、914、915 \u201cLinked\u201d UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号时编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。

这些示例展示了如何在 GS1MicroPdf417 中编码 “Linked” UCC/EAN-128 模式，以及在 MicroPdf417 和 Pdf417 条码中使用链接标志 (918)。

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


用于指示读取器将符号中包含的数据解释为读取器初始化的编程。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


2D 条码模块的高/宽比。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置对模式 908 和 909 编码 FNC1，也可以编码 910 和 911，这仅表示识别的 MicroPdf417 可解释为 Code 128。

这些示例展示了如何在第二位使用或不使用 FNC1 来编码 Code 128 仿真模式。通过这种方式，MicroPdf417 可以被解码为 Code 128 条码。

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


列数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


扩展通道解释标识符。用于向条码读取器提供有关在符号中编码数据所使用的引用的详细信息。不适用于 Macro PDF417 文本字段。当前实现包含所有已知的字符集编码。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


标识 Pdf417 编码模式。默认值：Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


设置 Pdf417 条码的错误更正级别，范围从 level0 到 level8，level0 表示没有错误更正信息，level8 表示最佳错误更正，即图像更大。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Pdf417 条码符号的错误纠正级别范围从 level0 到 level8，level0 表示没有错误纠正信息，level8 表示最佳错误纠正，这会导致更大的图像。 |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


定义与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号时编码 906、907、912、913、914、915 \u201cLinked\u201d UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号时编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。

这些示例展示了如何在 GS1MicroPdf417 中编码 “Linked” UCC/EAN-128 模式，以及在 MicroPdf417 和 Pdf417 条码中使用链接标志 (918)。

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 MicroPdf417 一起使用，并对 916 和 917 MicroPdf417 模式进行编码。默认值：MacroCharacters.None。

这些示例展示了如何在 MicroPdf417 中编码宏字符。

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


MacroPdf417 条码收件人名称（可选字段）。MicroPDF417 条码收件人名称（结构追加模式的可选字段）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


MacroPdf417 条码校验和（可选字段）。MicroPDF417 条码校验和（结构追加模式的可选字段）。校验和字段包含使用 CCITT-16 多项式（x^16 + x^12 + x^5 + 1）的 16 位（2 字节）CRC 校验值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


扩展通道解释标识符。适用于 Macro PDF417 文本字段。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


MacroPdf417 条码的文件 ID（必填字段）。MicroPDF417 条码的文件 ID（结构追加模式的必填字段）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


MacroPdf417 条码文件名（可选字段）。MicroPDF417 条码文件名（结构追加模式的可选字段）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


MacroPdf417 文件大小（可选字段）。MicroPDF417 文件大小（结构追加模式的可选字段）。文件大小字段包含整个源文件的字节大小。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


MacroPdf417 条码的段 ID（必填字段），起始值为 0，至 MacroSegmentsCount - 1。MicroPDF417 条码的段 ID（结构追加模式的必填字段）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


MacroPdf417 条码段计数（可选字段）。MicroPDF417 条码段计数（结构追加模式的可选字段）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


MacroPdf417 条码发送者名称（可选字段）。MicroPDF417 条码发送者名称（结构追加模式的可选字段）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


用于告诉编码器是否在段中添加 Macro PDF417 Terminator（代码字 922）。仅适用于 Macro PDF417。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


MacroPdf417 条形码时间戳（可选字段）。MicroPDF417 条形码时间戳（结构追加模式的可选字段）

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.time.LocalDateTime |  |

### setPdf417CompactionMode(Pdf417CompactionMode value) {#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-}
```
public final void setPdf417CompactionMode(Pdf417CompactionMode value)
```


Pdf417 条码符号的压缩模式。默认值：Pdf417CompactionMode.Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode) |  |

### setPdf417ECIEncoding(int value) {#setPdf417ECIEncoding-int-}
```
public final void setPdf417ECIEncoding(int value)
```


扩展通道解释标识符。用于向条码读取器提供有关在符号中编码数据所使用的引用的详细信息。不适用于 Macro PDF417 文本字段。当前实现包含所有已知的字符集编码。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPdf417EncodeMode(Pdf417EncodeMode value) {#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setPdf417EncodeMode(Pdf417EncodeMode value)
```


标识 Pdf417 编码模式。默认值：Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setPdf417ErrorLevel(Pdf417ErrorLevel value) {#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setPdf417ErrorLevel(Pdf417ErrorLevel value)
```


设置 Pdf417 条码的错误更正级别，范围从 level0 到 level8，level0 表示没有错误更正信息，level8 表示最佳错误更正，即图像更大。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Pdf417 条码符号的错误纠正级别范围从 level0 到 level8，level0 表示没有错误纠正信息，level8 表示最佳错误纠正，这会导致更大的图像。 |

### setPdf417MacroAddressee(String value) {#setPdf417MacroAddressee-java.lang.String-}
```
public final void setPdf417MacroAddressee(String value)
```


MacroPdf417 条码收件人名称（可选字段）。MicroPDF417 条码收件人名称（结构追加模式的可选字段）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPdf417MacroChecksum(int value) {#setPdf417MacroChecksum-int-}
```
public final void setPdf417MacroChecksum(int value)
```


MacroPdf417 条码校验和（可选字段）。MicroPDF417 条码校验和（结构追加模式的可选字段）。校验和字段包含使用 CCITT-16 多项式（x^16 + x^12 + x^5 + 1）的 16 位（2 字节）CRC 校验值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPdf417MacroECIEncoding(int value) {#setPdf417MacroECIEncoding-int-}
```
public final void setPdf417MacroECIEncoding(int value)
```


扩展通道解释标识符。适用于 Macro PDF417 文本字段。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPdf417MacroFileID(int value) {#setPdf417MacroFileID-int-}
```
public final void setPdf417MacroFileID(int value)
```


MacroPdf417 条码的文件 ID（必填字段）。MicroPDF417 条码的文件 ID（结构追加模式的必填字段）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPdf417MacroFileName(String value) {#setPdf417MacroFileName-java.lang.String-}
```
public final void setPdf417MacroFileName(String value)
```


MacroPdf417 条码文件名（可选字段）。MicroPDF417 条码文件名（结构追加模式的可选字段）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPdf417MacroFileSize(int value) {#setPdf417MacroFileSize-int-}
```
public final void setPdf417MacroFileSize(int value)
```


MacroPdf417 文件大小（可选字段）。MicroPDF417 文件大小（结构追加模式的可选字段）。文件大小字段包含整个源文件的字节大小。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPdf417MacroSegmentID(int value) {#setPdf417MacroSegmentID-int-}
```
public final void setPdf417MacroSegmentID(int value)
```


MacroPdf417 条码的段 ID（必填字段），起始值为 0，至 MacroSegmentsCount - 1。MicroPDF417 条码的段 ID（结构追加模式的必填字段）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPdf417MacroSegmentsCount(int value) {#setPdf417MacroSegmentsCount-int-}
```
public final void setPdf417MacroSegmentsCount(int value)
```


MacroPdf417 条码段计数（可选字段）。MicroPDF417 条码段计数（结构追加模式的可选字段）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPdf417MacroSender(String value) {#setPdf417MacroSender-java.lang.String-}
```
public final void setPdf417MacroSender(String value)
```


MacroPdf417 条码发送者名称（可选字段）。MicroPDF417 条码发送者名称（结构追加模式的可选字段）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPdf417MacroTerminator(Pdf417MacroTerminator value) {#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setPdf417MacroTerminator(Pdf417MacroTerminator value)
```


用于告诉编码器是否在段中添加 Macro PDF417 Terminator（代码字 922）。仅适用于 Macro PDF417。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setPdf417MacroTimeStamp(LocalDateTime value) {#setPdf417MacroTimeStamp-java.time.LocalDateTime-}
```
public final void setPdf417MacroTimeStamp(LocalDateTime value)
```


MacroPdf417 条形码时间戳（可选字段）。MicroPDF417 条形码时间戳（结构追加模式的可选字段）

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.time.LocalDateTime |  |

### setPdf417Truncate(boolean value) {#setPdf417Truncate-boolean-}
```
public final void setPdf417Truncate(boolean value)
```


Pdf417 条码符号是否被截断（以减少空间）。也称为 CompactPDF417。在此模式下，右行指示器和右停止图案被移除。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


用于指示读取器将符号中包含的数据解释为读取器初始化的编程。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


行数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Pdf417 条码符号是否被截断（以减少空间）。也称为 CompactPDF417。在此模式下，右行指示器和右停止图案被移除。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### toString() {#toString--}
```
public String toString()
```


返回此 [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) 的可读字符串表示。

**Returns:**
java.lang.String - 表示此 [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) 的字符串。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

