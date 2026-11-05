---
title: "Pdf417Parameters"
second_title: "Aspose.BarCode for Android via Java API 参考"
description: "PDF417 参数。"
type: docs
weight: 58
url: /zh/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

PDF417 参数。包含 PDF417、MacroPDF417、MicroPDF417 和 GS1MicroPdf417 参数。MacroPDF417 需要两个字段：Pdf417MacroFileID 和 Pdf417MacroSegmentID。所有其他字段为可选。MicroPDF417 在结构化追加模式（同 MacroPDF417 模式）下需要两个字段：Pdf417MacroFileID 和 Pdf417MacroSegmentID。所有其他字段为可选。

这些示例展示了如何在 GS1MicroPdf417 中编码 UCC/EAN-128 非链接模式。

```

 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(241)123456789012345(241)ABCD123456789012345");
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 二维条码模块的高宽比。 |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | 列数。 |
| [getECIEncoding()](#getECIEncoding--) | 扩展通道解释标识符。 |
| [getEncodeMode()](#getEncodeMode--) | 标识 Pdf417 编码模式。 |
| [getErrorLevel()](#getErrorLevel--) | 获取 Pdf417 条码的错误纠正级别类型，范围从 level0 到 level8，level0 表示没有错误纠正信息，level8 表示最佳错误纠正，即更大的图像。 |
| [getMacroCharacters()](#getMacroCharacters--) | 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | MacroPdf417 条码收件人名称（可选字段）。 |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | MacroPdf417 条码校验和（可选字段）。 |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | 扩展通道解释标识符。 |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | MacroPdf417 条码的文件 ID（必填字段）。 |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417 条码文件名（可选字段）。 |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417 文件大小（可选字段）。 |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | MacroPdf417 条码的段 ID（必填字段），范围从 0 开始，到 MacroSegmentsCount - 1。 |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | MacroPdf417 条码段计数（可选字段）。 |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | MacroPdf417 条码发送者名称（可选字段）。 |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | 用于告知编码器是否在段中添加宏 PDF417 终止符（代码字 922）. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | MacroPdf417 条码时间戳（可选字段）。 |
| [getRows()](#getRows--) | 行数。 |
| [getTruncate()](#getTruncate--) | Pdf417 条码的符号类型是否被截断（以减少空间）。 |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | 只能与 MicroPdf417 一起使用，并编码 Code 128 仿真模式。可以在第二位置编码 FNC1（模式 908 和 909），也可以编码 910 和 911，这仅表示识别的 MicroPdf417 可以解释为 Code 128。 |
| [isLinked()](#isLinked--) | 定义与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号编码 906、907、912、913、914、915 \\u201cLinked\\u201d UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。 |
| [isReaderInitialization()](#isReaderInitialization--) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程指令。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 二维条码模块的高宽比。 |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | 只能与 MicroPdf417 一起使用，并编码 Code 128 仿真模式。可以在第二位置编码 FNC1（模式 908 和 909），也可以编码 910 和 911，这仅表示识别的 MicroPdf417 可以解释为 Code 128。 |
| [setColumns(int value)](#setColumns-int-) | 列数。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 扩展通道解释标识符。 |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | 标识 Pdf417 编码模式。 |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | 设置 Pdf417 条码的错误纠正级别类型，范围从 level0 到 level8，level0 表示没有错误纠正信息，level8 表示最佳错误纠正，即更大的图像。 |
| [setLinked(boolean value)](#setLinked-boolean-) | 定义与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号编码 906、907、912、913、914、915 \\u201cLinked\\u201d UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。 |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | MacroPdf417 条码收件人名称（可选字段）。 |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | MacroPdf417 条码校验和（可选字段）。 |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | 扩展通道解释标识符。 |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | MacroPdf417 条码的文件 ID（必填字段）。 |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417 条码文件名（可选字段）。 |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417 文件大小（可选字段）。 |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | MacroPdf417 条码的段 ID（必填字段），范围从 0 开始，到 MacroSegmentsCount - 1。 |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | MacroPdf417 条码段计数（可选字段）。 |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | MacroPdf417 条码发送者名称（可选字段）。 |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | 用于告知编码器是否在段中添加宏 PDF417 终止符（代码字 922）. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | MacroPdf417 条码时间戳（可选字段）。 |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程指令。 |
| [setRows(int value)](#setRows-int-) | 行数。 |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Pdf417 条码的符号类型是否被截断（以减少空间）。 |
| [toString()](#toString--) | 返回此 [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) 的人类可读字符串表示形式。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


二维条码模块的高宽比。

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
整数
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


扩展通道解释标识符。它用于向条码读取器提供有关在符号中对数据进行编码所使用的引用的详细信息。对 Macro PDF417 文本字段不适用。当前实现包含所有已知的字符集编码。

**Returns:**
整数
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


获取 Pdf417 条码的错误纠正级别类型，范围从 level0 到 level8，level0 表示没有错误纠正信息，level8 表示最佳错误纠正，即更大的图像。

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 MicroPdf417 一起使用，并对 916 和 917 MicroPdf417 模式进行编码。默认值：MacroCharacters.None。

这些示例展示了如何在 MicroPdf417 中编码宏字符。

```

 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_06);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


MacroPdf417 条码收件人名称（可选字段）。MicroPDF417 条码收件人名称（结构追加模式的可选字段）

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


MacroPdf417 条码校验和（可选字段）。MicroPDF417 条码校验和（结构追加模式的可选字段）校验和字段包含使用 CCITT-16 多项式的 16 位（2 字节）CRC 校验和值。x^16 + x^12 + x^5 + 1

**Returns:**
整数
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


扩展通道解释标识符。适用于 Macro PDF417 文本字段。

**Returns:**
整数
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


MacroPdf417 条码的文件 ID（必填字段）。MicroPDF417 条码的文件 ID（结构追加模式的必填字段）

**Returns:**
整数
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


MacroPdf417 条码文件名（可选字段）。MicroPDF417 条码文件名（结构追加模式的可选字段）

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


MacroPdf417 文件大小（可选字段）。MicroPDF417 文件大小（结构追加模式的可选字段）文件大小字段包含整个源文件的字节大小。

**Returns:**
整数
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


MacroPdf417 条码的段 ID（必填字段），范围从 0 到 MacroSegmentsCount - 1。MicroPDF417 条码的段 ID（结构追加模式的必填字段）

**Returns:**
整数
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


MacroPdf417 条码段计数（可选字段）。MicroPDF417 条码段计数（结构追加模式的可选字段）

**Returns:**
整数
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


MacroPdf417 条码发送者名称（可选字段）。MicroPDF417 条码发送者名称（结构追加模式的可选字段）

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


用于告知编码器是否在段中添加 Macro PDF417 Terminator（代码字 922）。仅适用于 Macro PDF417。

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


MacroPdf417 条码时间戳（可选字段）。MicroPDF417 条码时间戳（结构追加模式的可选字段）

**Returns:**
java.time.LocalDateTime
### getRows() {#getRows--}
```
public final int getRows()
```


行数。

**Returns:**
整数
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


Pdf417 条码符号类型是否被截断（以减少空间）。也称为 CompactPDF417。在此模式下，右行指示器和右停止图案被移除。

**Returns:**
布尔
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
整数
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


只能与 MicroPdf417 一起使用，并编码 Code 128 仿真模式。可以在第二位置编码 FNC1（模式 908 和 909），也可以编码 910 和 911，这仅表示识别的 MicroPdf417 可以解释为 Code 128。

这些示例展示了如何在第二位置使用或不使用 FNC1 编码 Code 128 仿真模式。这样 MicroPdf417 可以被解码为 Code 128 条码。

```

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a1222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "991222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
 
```

**Returns:**
布尔
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


定义与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号编码 906、907、912、913、914、915 \\u201cLinked\\u201d UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。

这些示例展示了如何在 GS1MicroPdf417 中编码 \"Linked\" UCC/EAN-128 模式，以及在 MicroPdf417 和 Pdf417 条码中编码链接标志 (918)。

```

```

**Returns:**
布尔
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


用于指示读取器将符号中包含的数据解释为读取器初始化的编程指令。

**Returns:**
布尔
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


二维条码模块的高宽比。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


只能与 MicroPdf417 一起使用，并编码 Code 128 仿真模式。可以在第二位置编码 FNC1（模式 908 和 909），也可以编码 910 和 911，这仅表示识别的 MicroPdf417 可以解释为 Code 128。

这些示例展示了如何在第二位置使用或不使用 FNC1 编码 Code 128 仿真模式。这样 MicroPdf417 可以被解码为 Code 128 条码。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


列数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


扩展通道解释标识符。它用于向条码读取器提供有关在符号中对数据进行编码所使用的引用的详细信息。对 Macro PDF417 文本字段不适用。当前实现包含所有已知的字符集编码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


标识 Pdf417 编码模式。默认值：Auto。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


设置 Pdf417 条码的错误纠正级别类型，范围从 level0 到 level8，level0 表示没有错误纠正信息，level8 表示最佳错误纠正，即更大的图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Pdf417 条码的错误纠正级别范围从 level0 到 level8，level0 表示没有错误纠正信息，level8 表示最佳错误纠正，意味着更大的图像。 |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


定义与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号编码 906、907、912、913、914、915 \\u201cLinked\\u201d UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。

这些示例展示了如何在 GS1MicroPdf417 中编码 \"Linked\" UCC/EAN-128 模式，以及在 MicroPdf417 和 Pdf417 条码中编码链接标志 (918)。

```

 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(13)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(15)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(17)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(10)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(21)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked modes 906, 907 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(240)123456789012345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());
 
```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 MicroPdf417 一起使用，并对 916 和 917 MicroPdf417 模式进行编码。默认值：MacroCharacters.None。

这些示例展示了如何在 MicroPdf417 中编码宏字符。

```

```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


MacroPdf417 条码收件人名称（可选字段）。MicroPDF417 条码收件人名称（结构追加模式的可选字段）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


MacroPdf417 条码校验和（可选字段）。MicroPDF417 条码校验和（结构追加模式的可选字段）校验和字段包含使用 CCITT-16 多项式的 16 位（2 字节）CRC 校验和值。x^16 + x^12 + x^5 + 1

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


扩展通道解释标识符。适用于 Macro PDF417 文本字段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


MacroPdf417 条码的文件 ID（必填字段）。MicroPDF417 条码的文件 ID（结构追加模式的必填字段）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


MacroPdf417 条码文件名（可选字段）。MicroPDF417 条码文件名（结构追加模式的可选字段）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


MacroPdf417 文件大小（可选字段）。MicroPDF417 文件大小（结构追加模式的可选字段）文件大小字段包含整个源文件的字节大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


MacroPdf417 条码的段 ID（必填字段），范围从 0 到 MacroSegmentsCount - 1。MicroPDF417 条码的段 ID（结构追加模式的必填字段）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


MacroPdf417 条码段计数（可选字段）。MicroPDF417 条码段计数（结构追加模式的可选字段）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


MacroPdf417 条码发送者名称（可选字段）。MicroPDF417 条码发送者名称（结构追加模式的可选字段）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


用于告知编码器是否在段中添加 Macro PDF417 Terminator（代码字 922）。仅适用于 Macro PDF417。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


MacroPdf417 条码时间戳（可选字段）。MicroPDF417 条码时间戳（结构追加模式的可选字段）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


用于指示读取器将符号中包含的数据解释为读取器初始化的编程指令。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


行数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Pdf417 条码符号类型是否被截断（以减少空间）。也称为 CompactPDF417。在此模式下，右行指示器和右停止图案被移除。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### toString() {#toString--}
```
public String toString()
```


返回此 [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) 的人类可读字符串表示形式。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | 整数 |  |

