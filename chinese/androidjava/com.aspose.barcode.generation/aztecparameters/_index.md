---
title: AztecParameters
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: Aztec 参数。
type: docs
weight: 12
url: /zh/androidjava/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

Aztec 参数。
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D 条码模块的高/宽比。 |
| [getAztecEncodeMode()](#getAztecEncodeMode--) | 获取 Aztec 编码模式。 |
| [getAztecErrorLevel()](#getAztecErrorLevel--) | Aztec 条码类型的错误更正级别。 |
| [getAztecSymbolMode()](#getAztecSymbolMode--) | 获取 Aztec 符号模式。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 获取 ECI 编码。 |
| [getEncodeMode()](#getEncodeMode--) | 获取 Aztec 编码模式。 |
| [getErrorLevel()](#getErrorLevel--) | Aztec 条码类型的错误更正级别。 |
| [getLayersCount()](#getLayersCount--) | 获取 Aztec 符号的层数。 |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Aztec 条码的结构追加模式的条形码 ID。 |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Aztec 条码的结构追加模式的条码计数。 |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Aztec 条码的结构追加模式的文件 ID（可选字段）。 |
| [getSymbolMode()](#getSymbolMode--) | 获取 Aztec 符号模式。 |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D 条码模块的高/宽比。 |
| [setAztecEncodeMode(AztecEncodeMode value)](#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | 设置 Aztec 编码模式。 |
| [setAztecErrorLevel(int value)](#setAztecErrorLevel-int-) | Aztec 条码类型的错误更正级别。 |
| [setAztecSymbolMode(AztecSymbolMode value)](#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | 设置 Aztec 符号模式。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 设置 ECI 编码。 |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | 设置 Aztec 编码模式。 |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Aztec 条码类型的错误更正级别。 |
| [setLayersCount(int value)](#setLayersCount-int-) | 设置 Aztec 符号的层数。 |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Aztec 条码的结构追加模式的条形码 ID。 |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Aztec 条码的结构追加模式的条码计数。 |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | Aztec 条码的结构追加模式的文件 ID（可选字段）。 |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | 设置 Aztec 符号模式。 |
| [toString()](#toString--) | 返回此 [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) 的可读字符串表示。 |
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
### getAztecEncodeMode() {#getAztecEncodeMode--}
```
public final AztecEncodeMode getAztecEncodeMode()
```


获取 Aztec 编码模式。默认值：Auto。

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - 一个 Aztec 编码模式。
### getAztecErrorLevel() {#getAztecErrorLevel--}
```
public final int getAztecErrorLevel()
```


Aztec 条码的错误纠正级别。值应在 5 到 95 之间。

**Returns:**
int
### getAztecSymbolMode() {#getAztecSymbolMode--}
```
public final AztecSymbolMode getAztecSymbolMode()
```


获取 Aztec 符号模式。默认值：AztecSymbolMode.Auto。

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
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


获取 ECI 编码。当 AztecEncodeMode 为 Auto 时使用。默认值：ISO-8859-1

**Returns:**
int - ECI 编码。
### getEncodeMode() {#getEncodeMode--}
```
public final AztecEncodeMode getEncodeMode()
```


获取 Aztec 编码模式。默认值：Auto。

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - 一个 Aztec 编码模式。
### getErrorLevel() {#getErrorLevel--}
```
public final int getErrorLevel()
```


Aztec 条码的错误纠正级别。值应在 5 到 95 之间。

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


获取 Aztec 符号的层数。紧凑模式下层数应在 1 到 3 范围内，完整范围模式下应在 1 到 32 范围内。默认值：0（自动）。

**Returns:**
int - Aztec 符号的层数。
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Aztec 条码的结构追加模式的条形码 ID。条形码 ID 应在 1 到条码计数之间。默认值：0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Aztec 条码的结构追加模式的条码计数。条码计数应在 1 到 26 之间。默认值：0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


Aztec 条码的结构追加模式的文件 ID（可选字段）。文件 ID 不应包含空格。默认值：空字符串

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


获取 Aztec 符号模式。默认值：AztecSymbolMode.Auto。

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### setAztecEncodeMode(AztecEncodeMode value) {#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setAztecEncodeMode(AztecEncodeMode value)
```


设置 Aztec 编码模式。默认值：Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.barcode.generation.AztecEncodeMode | 一个 Aztec 编码模式。 |

### setAztecErrorLevel(int value) {#setAztecErrorLevel-int-}
```
public final void setAztecErrorLevel(int value)
```


Aztec 条码的错误纠正级别。值应在 5 到 95 之间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setAztecSymbolMode(AztecSymbolMode value) {#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setAztecSymbolMode(AztecSymbolMode value)
```


设置 Aztec 符号模式。默认值：AztecSymbolMode.Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | 一个 Aztec 符号模式。 |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


设置 ECI 编码。当 AztecEncodeMode 为 Auto 时使用。默认值：ISO-8859-1

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | ECI 编码。 |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


设置 Aztec 编码模式。默认值：Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.barcode.generation.AztecEncodeMode | 一个 Aztec 编码模式。 |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


Aztec 条码的错误纠正级别。值应在 5 到 95 之间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


设置 Aztec 符号的层数。紧凑模式下层数应在 1 到 3 范围内，完整范围模式下应在 1 到 32 范围内。默认值：0（自动）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | Aztec 符号的层数。 |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


用于指示读取器将符号中包含的数据解释为读取器初始化的编程。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Aztec 条码的结构追加模式的条形码 ID。条形码 ID 应在 1 到条码计数之间。默认值：0

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Aztec 条码的结构追加模式的条码计数。条码计数应在 1 到 26 之间。默认值：0

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


Aztec 条码的结构追加模式的文件 ID（可选字段）。文件 ID 不应包含空格。默认值：空字符串

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


设置 Aztec 符号模式。默认值：AztecSymbolMode.Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | 一个 Aztec 符号模式。 |

### toString() {#toString--}
```
public String toString()
```


返回此 [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) 的可读字符串表示。

**Returns:**
java.lang.String - 表示此 [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) 的字符串。
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

