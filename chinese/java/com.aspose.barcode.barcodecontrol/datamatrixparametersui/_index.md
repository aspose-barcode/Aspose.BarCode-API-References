---
title: "DataMatrixParametersUI"
second_title: "Aspose.BarCode for Java API Reference"
description: "UI 包装器用于 com.aspose.barcode.generation.DataMatrixParameters 类。"
type: docs
weight: 14
url: /zh/java/com.aspose.barcode.barcodecontrol/datamatrixparametersui/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParametersUI
```

UI 包装器用于 com.aspose.barcode.generation.DataMatrixParameters 类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D 条码模块的高/宽比。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 获取 ECI 编码。 |
| [getEccType()](#getEccType--) | 获取 Datamatrix ECC 类型。 |
| [getEncodeMode()](#getEncodeMode--) | Datamatrix 条码的编码模式。 |
| [getMacroCharacters()](#getMacroCharacters--) | 首位宏字符的协议（仅限 ECC 200）。 |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | 结构化追加模式的条码 ID。 |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | 结构化追加模式的条码数量。 |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | 结构化追加模式的文件 ID。 |
| [getVersion()](#getVersion--) | DataMatrix 符号大小。 |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D 条码模块的高/宽比。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 设置 ECI 编码。 |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | 设置 Datamatrix ECC 类型。 |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Datamatrix 条码的编码模式。 |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | 首位宏字符的协议（仅限 ECC 200）。 |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | 结构化追加模式的条码 ID。 |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | 结构化追加模式的条码数量。 |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | 结构化追加模式的文件 ID。 |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | DataMatrix 符号大小。 |
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


获取 ECI 编码。用于 EncodeMode 为 Auto 时。

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


首位宏字符的协议（仅限 ECC 200）。

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


结构化追加模式的条码 ID。

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


结构化追加模式的条码数量。

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


结构化追加模式的文件 ID。

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


DataMatrix 符号大小。

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
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

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


设置 ECI 编码。用于 EncodeMode 为 Auto 时。

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


首位宏字符的协议（仅限 ECC 200）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


用于指示读取器将符号中包含的数据解释为读取器初始化的编程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


结构化追加模式的条码 ID。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


结构化追加模式的条码数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


结构化追加模式的文件 ID。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


DataMatrix 符号大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) |  |

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

