---
title: "AztecParameters"
second_title: "Aspose.BarCode for Android via Java API 参考"
description: "Aztec 参数。"
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
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 二维条码模块的高宽比。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 获取 ECI 编码。 |
| [getEncodeMode()](#getEncodeMode--) | 获取 Aztec 编码模式。 |
| [getErrorLevel()](#getErrorLevel--) | Aztec 条码的错误更正级别。 |
| [getLayersCount()](#getLayersCount--) | 获取 Aztec 符号的层数。 |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Aztec 条码结构化追加模式的条码 ID。 |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Aztec 条码结构化追加模式的条码数量。 |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Aztec 条码结构化追加模式的文件 ID（可选字段）。 |
| [getSymbolMode()](#getSymbolMode--) | 获取 Aztec 符号模式。 |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程指令。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 二维条码模块的高宽比。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 设置 ECI 编码。 |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | 设置 Aztec 编码模式。 |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Aztec 条码的错误更正级别。 |
| [setLayersCount(int value)](#setLayersCount-int-) | 设置 Aztec 符号的层数。 |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程指令。 |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Aztec 条码结构化追加模式的条码 ID。 |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Aztec 条码结构化追加模式的条码数量。 |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | Aztec 条码结构化追加模式的文件 ID（可选字段）。 |
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


Aztec 条码的错误更正级别。值应在 5 到 95 之间。

**Returns:**
整数
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


Aztec 条码结构化追加模式的条码 ID。条码 ID 应在 1 到条码数量范围内。默认值：0

**Returns:**
整数
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Aztec 条码的结构追加模式的条码计数。条码计数应在 1 到 26 的范围内。默认值：0

**Returns:**
整数
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


Aztec 条码结构追加模式的文件 ID（可选字段）。文件 ID 不应包含空格。默认值：空字符串

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
public final int hashCode()
```




**Returns:**
整数
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

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


设置 ECI 编码。当 AztecEncodeMode 为 Auto 时使用。默认值：ISO-8859-1

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 | ECI 编码。 |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


设置 Aztec 编码模式。默认值：Auto。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | com.aspose.barcode.generation.AztecEncodeMode | 一个 Aztec 编码模式。 |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


Aztec 条码的错误更正级别。值应在 5 到 95 之间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


设置 Aztec 符号的层数。紧凑模式下层数应在 1 到 3 的范围内，完整范围模式下应在 1 到 32 的范围内。默认值：0（自动）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 | Aztec 符号的层数。 |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


用于指示读取器将符号中包含的数据解释为读取器初始化的编程指令。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Aztec 条码结构化追加模式的条码 ID。条码 ID 应在 1 到条码数量范围内。默认值：0

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Aztec 条码的结构追加模式的条码计数。条码计数应在 1 到 26 的范围内。默认值：0

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


Aztec 条码结构追加模式的文件 ID（可选字段）。文件 ID 不应包含空格。默认值：空字符串

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


设置 Aztec 符号模式。默认值：AztecSymbolMode.Auto。

**Parameters:**
| 参数 | 类型 | 描述 |
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

