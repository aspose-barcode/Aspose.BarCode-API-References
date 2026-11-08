---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode for Java API Reference"
description: "DataMatrix 参数。"
type: docs
weight: 32
url: /zh/java/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

DataMatrix 参数。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D 条码模块的高/宽比。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 获取 ECI 编码。 |
| [getEccType()](#getEccType--) | 获取 Datamatrix ECC 类型。 |
| [getEncodeMode()](#getEncodeMode--) | Datamatrix 条码的编码模式。 |
| [getMacroCharacters()](#getMacroCharacters--) | Macro Characters 05 和 06 的值用于在特殊模式下获得更紧凑的编码。 |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Datamatrix 条码结构化追加模式的条码 ID。 |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Datamatrix 条码的结构追加模式的条码计数。 |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Datamatrix 条码的结构追加模式的文件 ID。 |
| [getVersion()](#getVersion--) | 获取 Datamatrix 符号大小。 |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D 条码模块的高/宽比。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 设置 ECI 编码。 |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | 设置 Datamatrix ECC 类型。 |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Datamatrix 条码的编码模式。 |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Macro Characters 05 和 06 的值用于在特殊模式下获得更紧凑的编码。 |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Datamatrix 条码结构化追加模式的条码 ID。 |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Datamatrix 条码的结构追加模式的条码计数。 |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | Datamatrix 条码的结构追加模式的文件 ID。 |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | 设置 Datamatrix 符号大小。 |
| [toString()](#toString--) | 返回此 [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) 的可读字符串表示。 |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


获取 ECI 编码。用于 EncodeMode 为 Auto 时。默认值：ISO-8859-1。

**Returns:**
int - ECI 编码。
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


获取 Datamatrix ECC 类型。默认值：DataMatrixEccType.Ecc200。

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Datamatrix 条码的编码模式。默认值：EncodeMode.Auto。

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 DataMatrixEccType.Ecc200 或 DataMatrixEccType.EccAuto 一起使用。不能与 EncodeTypes.GS1DataMatrix 一起使用。默认值：MacroCharacters.None。

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Datamatrix 条码的结构追加模式的条码 ID。默认值：0。

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Datamatrix 条码的结构追加模式的条码计数。默认值：0。

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


Datamatrix 条码的结构追加模式的文件 ID。默认值：0。

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


获取 Datamatrix 符号大小。默认值：Version.Auto。

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
```


用于指示读取器将符号中包含的数据解释为读取器初始化的编程。默认值：false。

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

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


设置 ECI 编码。用于 EncodeMode 为 Auto 时。默认值：ISO-8859-1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ECI 编码。 |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


设置 Datamatrix ECC 类型。默认值：DataMatrixEccType.Ecc200。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | 一个 Datamatrix ECC 类型。 |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix 条码的编码模式。默认值：EncodeMode.Auto。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 DataMatrixEccType.Ecc200 或 DataMatrixEccType.EccAuto 一起使用。不能与 EncodeTypes.GS1DataMatrix 一起使用。默认值：MacroCharacters.None。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


用于指示读取器将符号中包含的数据解释为读取器初始化的编程。默认值：false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Datamatrix 条码的结构追加模式的条码 ID。默认值：0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Datamatrix 条码的结构追加模式的条码计数。默认值：0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Datamatrix 条码的结构追加模式的文件 ID。默认值：0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


设置 Datamatrix 符号大小。默认值：Version.Auto。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | 一个 Datamatrix 符号大小。 |

### toString() {#toString--}
```
public String toString()
```


返回此 [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) 的可读字符串表示。

**Returns:**
java.lang.String - 表示此 [DataMatrixParameters](../../com.aspose.barcode/generation/datamatrixparameters) 的字符串。
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

