---
title: "AztecParameters"
second_title: "Aspose.BarCode for Java API Reference"
description: "Aztec 参数。"
type: docs
weight: 12
url: /zh/java/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

Aztec 参数。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D 条码模块的高/宽比。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 获取 ECI 编码。 |
| [getEncodeMode()](#getEncodeMode--) | 获取 Aztec 编码模式。 |
| [getErrorLevel()](#getErrorLevel--) | Aztec 条形码类型的错误更正级别。 |
| [getLayersCount()](#getLayersCount--) | 获取 Aztec 符号的层数。 |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Aztec 条形码结构追加模式的条码 ID。 |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Aztec 条形码结构追加模式的条码数量。 |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Aztec 条形码结构追加模式的文件 ID（可选字段）。 |
| [getSymbolMode()](#getSymbolMode--) | 获取 Aztec 符号模式。 |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D 条码模块的高/宽比。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 设置 ECI 编码。 |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | 设置 Aztec 编码模式。 |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Aztec 条形码类型的错误更正级别。 |
| [setLayersCount(int value)](#setLayersCount-int-) | 设置 Aztec 符号的层数。 |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Aztec 条形码结构追加模式的条码 ID。 |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Aztec 条形码结构追加模式的条码数量。 |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | Aztec 条形码结构追加模式的文件 ID（可选字段）。 |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | 设置 Aztec 符号模式。 |
| [toString()](#toString--) | 返回此 [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) 的人类可读字符串表示。 |
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


获取 ECI 编码。当 AztecEncodeMode 为 Auto 时使用。默认值：ISO-8859-1。

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


Aztec 条码的结构化追加模式的条码 ID。条码 ID 应在 1 到条码总数之间。默认值：0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Aztec 条码的结构化追加模式的条码数量。条码数量应在 1 到 26 之间。默认值：0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


Aztec 条码的结构化追加模式的文件 ID（可选字段）。文件 ID 不应包含空格。默认值：空字符串

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


获取 Aztec Symbol 模式。默认值：AztecSymbolMode.Auto。

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
### hashCode() {#hashCode--}
```
public final int hashCode()
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


设置 ECI 编码。当 AztecEncodeMode 为 Auto 时使用。默认值：ISO-8859-1

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ECI 编码。 |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


设置 Aztec 编码模式。默认值：Auto。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | com.aspose.barcode.generation.AztecEncodeMode | 一个 Aztec 编码模式。 |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


Aztec 条码的错误纠正级别。值应在 5 到 95 之间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


设置 Aztec 符号的层数。紧凑模式下层数应在 1 到 3 范围内，完整范围模式下应在 1 到 32 范围内。默认值：0（自动）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | Aztec 符号的层数。 |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
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


Aztec 条码的结构化追加模式的条码 ID。条码 ID 应在 1 到条码总数之间。默认值：0

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Aztec 条码的结构化追加模式的条码数量。条码数量应在 1 到 26 之间。默认值：0

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


Aztec 条码的结构化追加模式的文件 ID（可选字段）。文件 ID 不应包含空格。默认值：空字符串

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


设置 Aztec Symbol 模式。默认值：AztecSymbolMode.Auto。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | Aztec Symbol 模式。 |

### toString() {#toString--}
```
public String toString()
```


返回此 [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此 [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) 的字符串。
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

