---
title: DataMatrixParameters
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: DataMatrix 参数。
type: docs
weight: 34
url: /zh/androidjava/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

DataMatrix 参数。
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D 条码模块的高/宽比。 |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | 列数。 |
| [getDataMatrixEcc()](#getDataMatrixEcc--) | 获取 Datamatrix ECC 类型。 |
| [getDataMatrixEncodeMode()](#getDataMatrixEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixVersion()](#getDataMatrixVersion--) | 获取 Datamatrix 符号大小。 |
| [getECIEncoding()](#getECIEncoding--) | 获取 ECI 编码。 |
| [getEccType()](#getEccType--) | 获取 Datamatrix ECC 类型。 |
| [getEncodeMode()](#getEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getMacroCharacters()](#getMacroCharacters--) | 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。 |
| [getRows()](#getRows--) | 行数。 |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Datamatrix 条码的结构化追加模式的条码 ID。 |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Datamatrix 条码的结构化追加模式的条码数量。 |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Datamatrix 条码的结构化追加模式的文件 ID。 |
| [getVersion()](#getVersion--) | 获取 Datamatrix 符号大小。 |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D 条码模块的高/宽比。 |
| [setColumns(int value)](#setColumns-int-) | 列数。 |
| [setDataMatrixEcc(DataMatrixEccType value)](#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-) | 设置 Datamatrix ECC 类型。 |
| [setDataMatrixEncodeMode(DataMatrixEncodeMode value)](#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixVersion(DataMatrixVersion value)](#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-) | 设置 Datamatrix 符号大小。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 设置 ECI 编码。 |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | 设置 Datamatrix ECC 类型。 |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。 |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [setRows(int value)](#setRows-int-) | 行数。 |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Datamatrix 条码的结构化追加模式的条码 ID。 |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Datamatrix 条码的结构化追加模式的条码数量。 |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | Datamatrix 条码的结构化追加模式的文件 ID。 |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | 设置 Datamatrix 符号大小。 |
| [toString()](#toString--) | 返回此 [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) 的人类可读字符串表示。 |
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
### getDataMatrixEcc() {#getDataMatrixEcc--}
```
public final DataMatrixEccType getDataMatrixEcc()
```


获取 Datamatrix ECC 类型。默认值：DataMatrixEccType.Ecc200。

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getDataMatrixEncodeMode() {#getDataMatrixEncodeMode--}
```
public final DataMatrixEncodeMode getDataMatrixEncodeMode()
```


Datamatrix 条码的编码模式。默认值：EncodeMode.Auto。

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getDataMatrixVersion() {#getDataMatrixVersion--}
```
public final DataMatrixVersion getDataMatrixVersion()
```


获取 Datamatrix 符号大小。默认值：Version.Auto。

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


获取 ECI 编码。当 EncodeMode 为 Auto 时使用。默认值：ISO-8859-1。

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
### getRows() {#getRows--}
```
public final int getRows()
```


行数。

**Returns:**
int
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Datamatrix 条码的结构化追加模式的条码 ID。默认值：0。

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Datamatrix 条码的结构化追加模式的条码数量。默认值：0。

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


Datamatrix 条码的结构化追加模式的文件 ID。默认值：0。

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
public native int hashCode()
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


列数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setDataMatrixEcc(DataMatrixEccType value) {#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setDataMatrixEcc(DataMatrixEccType value)
```


设置 Datamatrix ECC 类型。默认值：DataMatrixEccType.Ecc200。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | Datamatrix ECC 类型。 |

### setDataMatrixEncodeMode(DataMatrixEncodeMode value) {#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setDataMatrixEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix 条码的编码模式。默认值：EncodeMode.Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setDataMatrixVersion(DataMatrixVersion value) {#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setDataMatrixVersion(DataMatrixVersion value)
```


设置 Datamatrix 符号大小。默认值：Version.Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | Datamatrix 符号大小。 |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


设置 ECI 编码。当 EncodeMode 为 Auto 时使用。默认值：ISO-8859-1。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | ECI 编码。 |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


设置 Datamatrix ECC 类型。默认值：DataMatrixEccType.Ecc200。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | Datamatrix ECC 类型。 |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix 条码的编码模式。默认值：EncodeMode.Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 DataMatrixEccType.Ecc200 或 DataMatrixEccType.EccAuto 一起使用。不能与 EncodeTypes.GS1DataMatrix 一起使用。默认值：MacroCharacters.None。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


用于指示读取器将符号中包含的数据解释为读取器初始化的编程。默认值：false。

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

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Datamatrix 条码的结构化追加模式的条码 ID。默认值：0。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Datamatrix 条码的结构化追加模式的条码数量。默认值：0。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Datamatrix 条码的结构化追加模式的文件 ID。默认值：0。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


设置 Datamatrix 符号大小。默认值：Version.Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | Datamatrix 符号大小。 |

### toString() {#toString--}
```
public String toString()
```


返回此 [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此 [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) 的字符串。
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

