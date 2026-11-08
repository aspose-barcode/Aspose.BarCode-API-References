---
title: "Pdf417ParametersUI"
second_title: "Aspose.BarCode for Java API Reference"
description: "UI 包装器用于 com.aspose.barcode.generation.Pdf417Parameters 类。"
type: docs
weight: 16
url: /zh/java/com.aspose.barcode.barcodecontrol/pdf417parametersui/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417ParametersUI
```

UI 包装器用于 com.aspose.barcode.generation.Pdf417Parameters 类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D 条码模块的高/宽比。 |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | 列数。 |
| [getECIEncoding()](#getECIEncoding--) | 扩展通道解释标识符。 |
| [getEncodeMode()](#getEncodeMode--) | Pdf417 条码的编码模式的符号类型。 |
| [getErrorLevel()](#getErrorLevel--) | 获取 Pdf417 条码的错误纠正级别的符号类型，范围从 level0 到 level8，level0 表示没有错误纠正信息，level8 表示最佳错误纠正，即更大的图像。 |
| [getMacroCharacters()](#getMacroCharacters--) | Macro Characters 05 和 06 的值用于在特殊模式下获得更紧凑的编码。 |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | MacroPdf417 条码收件人名称（可选字段）。 |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | MacroPdf417 条码校验和（可选字段）。 |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | 扩展通道解释标识符。 |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | 获取宏 Pdf417 条码的文件 ID。 |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417 条码文件名（可选字段）。 |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417 文件大小（可选字段）。 |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | 获取宏 Pdf417 条码的段 ID，范围从 0 开始，到 MacroSegmentsCount - 1。 |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | 获取宏 Pdf417 条码段的数量。 |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | MacroPdf417 条码发送者名称（可选字段）。 |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | 用于告诉编码器是否在段中添加 Macro PDF417 终止符（代码字 922）。 |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | MacroPdf417 条码时间戳（可选字段）。 |
| [getRows()](#getRows--) | 行数。 |
| [getTruncate()](#getTruncate--) | Pdf417 条码的符号类型是否被截断（以减少空间）。 |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | 只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置模式 908 和 909 中编码 FNC1，也可以编码 910 和 911，这仅表示识别的 MicroPdf417 可以解释为 Code 128。 |
| [isLinked()](#isLinked--) | 定义与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号时编码 906、907、912、913、914、915 “Linked” UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号时编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。 |
| [isReaderInitialization()](#isReaderInitialization--) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D 条码模块的高/宽比。 |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | 只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置模式 908 和 909 中编码 FNC1，也可以编码 910 和 911，这仅表示识别的 MicroPdf417 可以解释为 Code 128。 |
| [setColumns(int value)](#setColumns-int-) | 列数。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 扩展通道解释标识符。 |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Pdf417 条码的编码模式的符号类型。 |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | 设置 Pdf417 条码的错误纠正级别的符号类型，范围从 level0 到 level8，level0 表示没有错误纠正信息，level8 表示最佳错误纠正，即更大的图像。 |
| [setLinked(boolean value)](#setLinked-boolean-) | 定义与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号时编码 906、907、912、913、914、915 “Linked” UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号时编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。 |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Macro Characters 05 和 06 的值用于在特殊模式下获得更紧凑的编码。 |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | MacroPdf417 条码收件人名称（可选字段）。 |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | MacroPdf417 条码校验和（可选字段）。 |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | 扩展通道解释标识符。 |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | 设置宏 Pdf417 条码的文件 ID。 |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417 条码文件名（可选字段）。 |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417 文件大小（可选字段）。 |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | 设置宏 Pdf417 条码的段 ID，范围从 0 开始，到 MacroSegmentsCount - 1。 |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | 设置宏 Pdf417 条形码段计数。 |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | MacroPdf417 条码发送者名称（可选字段）。 |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | 用于告诉编码器是否在段中添加 Macro PDF417 终止符（代码字 922）。 |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | MacroPdf417 条码时间戳（可选字段）。 |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [setRows(int value)](#setRows-int-) | 行数。 |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Pdf417 条码的符号类型是否被截断（以减少空间）。 |
| [toString()](#toString--) | 返回此 [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) 的人类可读字符串表示。 |
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


扩展通道解释标识符。它用于向条形码读取器提供有关在符号中对数据进行编码所使用的参考的详细信息。对宏 PDF417 文本字段不适用。当前实现包含所有已知的字符集编码。

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Pdf417 符号类型的 BarCode 编码模式。默认值：Pdf417EncodeMode.Auto。

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


获取 Pdf417 条码的错误纠正级别的符号类型，范围从 level0 到 level8，level0 表示没有错误纠正信息，level8 表示最佳错误纠正，即更大的图像。

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 MicroPdf417 一起使用，并对 916 和 917 MicroPdf417 模式进行编码。默认值：MacroCharacters.None。

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


MacroPdf417 条形码收件人名称（可选字段）。MicroPDF417 条形码收件人名称（结构追加模式的可选字段）

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


MacroPdf417 条形码校验和（可选字段）。MicroPDF417 条形码校验和（结构追加模式的可选字段）校验和字段包含使用 CCITT-16 多项式的 16 位（2 字节）CRC 校验和值。x^16 + x^12 + x^5 + 1

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


扩展通道解释标识符。适用于宏 PDF417 文本字段。

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


获取宏 Pdf417 条形码的文件 ID。用于 MacroPdf417。

**Returns:**
int - 宏 Pdf417 条形码的文件 ID。
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


MacroPdf417 条形码文件名（可选字段）。MicroPDF417 条形码文件名（结构追加模式的可选字段）

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


MacroPdf417 文件大小（可选字段）。MicroPDF417 文件大小（结构追加模式的可选字段）文件大小字段包含整个源文件的字节大小。

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


获取宏 Pdf417 条码的段 ID，范围从 0 开始，到 MacroSegmentsCount - 1。

**Returns:**
int - 宏 Pdf417 条形码的段 ID，范围从 0 到 MacroSegmentsCount - 1。
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


获取宏 Pdf417 条码段的数量。

**Returns:**
int - 宏 Pdf417 条形码段计数。
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


MacroPdf417 条形码发送者名称（可选字段）。MicroPDF417 条形码发送者名称（结构追加模式的可选字段）

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


用于告知编码器是否向段添加宏 PDF417 终止符（代码字 922）。仅适用于宏 PDF417。

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


MacroPdf417 条形码时间戳（可选字段）。MicroPDF417 条形码时间戳（结构追加模式的可选字段）

**Returns:**
java.time.LocalDateTime
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


Pdf417 条码的符号类型是否被截断（以减少空间）。

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


只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置模式 908 和 909 中编码 FNC1，也可以编码 910 和 911，这仅表示识别的 MicroPdf417 可以解释为 Code 128。

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


定义与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号时编码 906、907、912、913、914、915 “Linked” UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号时编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


只能与 MicroPdf417 一起使用，并对 Code 128 仿真模式进行编码。可以在第二位置模式 908 和 909 中编码 FNC1，也可以编码 910 和 911，这仅表示识别的 MicroPdf417 可以解释为 Code 128。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


列数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


扩展通道解释标识符。它用于向条形码读取器提供有关在符号中对数据进行编码所使用的参考的详细信息。对宏 PDF417 文本字段不适用。当前实现包含所有已知的字符集编码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Pdf417 符号类型的 BarCode 编码模式。默认值：Pdf417EncodeMode.Auto。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


设置 Pdf417 条码的错误纠正级别的符号类型，范围从 level0 到 level8，level0 表示没有错误纠正信息，level8 表示最佳错误纠正，即更大的图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Pdf417 符号类型的 BarCode 错误更正级别，范围从 level0 到 level8，level0 表示没有错误更正信息，level8 表示最佳错误更正，导致更大的图像。 |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


定义与 GS1MicroPdf417、MicroPdf417 和 Pdf417 条码的链接模式。使用 GS1MicroPdf417 符号时编码 906、907、912、913、914、915 “Linked” UCC/EAN-128 模式。使用 MicroPdf417 和 Pdf417 符号时编码 918 链接标志，以关联除 EAN.UCC 之外的线性组件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 MicroPdf417 一起使用，并对 916 和 917 MicroPdf417 模式进行编码。默认值：MacroCharacters.None。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


MacroPdf417 条形码收件人名称（可选字段）。MicroPDF417 条形码收件人名称（结构追加模式的可选字段）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


MacroPdf417 条形码校验和（可选字段）。MicroPDF417 条形码校验和（结构追加模式的可选字段）校验和字段包含使用 CCITT-16 多项式的 16 位（2 字节）CRC 校验和值。x^16 + x^12 + x^5 + 1

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


扩展通道解释标识符。适用于宏 PDF417 文本字段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


设置宏 Pdf417 条形码的文件 ID。用于 MacroPdf417。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 宏 Pdf417 条形码的文件 ID。 |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


MacroPdf417 条形码文件名（可选字段）。MicroPDF417 条形码文件名（结构追加模式的可选字段）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


MacroPdf417 文件大小（可选字段）。MicroPDF417 文件大小（结构追加模式的可选字段）文件大小字段包含整个源文件的字节大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


设置宏 Pdf417 条码的段 ID，范围从 0 开始，到 MacroSegmentsCount - 1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 宏 Pdf417 条形码的段 ID，范围从 0 到 MacroSegmentsCount - 1。 |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


设置宏 Pdf417 条形码段计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 宏 Pdf417 条形码段计数。 |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


MacroPdf417 条形码发送者名称（可选字段）。MicroPDF417 条形码发送者名称（结构追加模式的可选字段）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


用于告知编码器是否向段添加宏 PDF417 终止符（代码字 922）。仅适用于宏 PDF417。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


MacroPdf417 条形码时间戳（可选字段）。MicroPDF417 条形码时间戳（结构追加模式的可选字段）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


用于指示读取器将符号中包含的数据解释为读取器初始化的编程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


行数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Pdf417 条码的符号类型是否被截断（以减少空间）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```


返回此 [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此 [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) 的字符串。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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
| arg1 | int |  |

