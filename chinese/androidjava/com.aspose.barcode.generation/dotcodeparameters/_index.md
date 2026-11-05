---
title: "DotCodeParameters"
second_title: "Aspose.BarCode for Android via Java API 参考"
description: "DotCode 参数。"
type: docs
weight: 35
url: /zh/androidjava/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

DotCode 参数。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 二维条码模块的高宽比。 |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | 标识列数。 |
| [getECIEncoding()](#getECIEncoding--) | 标识 ECI 编码。 |
| [getEncodeMode()](#getEncodeMode--) | 标识 DotCode 编码模式。 |
| [getRows()](#getRows--) | 标识行数。 |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | 标识 DotCode 结构化追加模式条码的 ID。 |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | 标识 DotCode 结构化追加模式条码的数量。 |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | 指示代码是否用于指示读取器将以下数据解释为条码读取器的初始化或重新编程指令。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 二维条码模块的高宽比。 |
| [setColumns(int value)](#setColumns-int-) | 标识列数。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 标识 ECI 编码。 |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | 标识 DotCode 编码模式。 |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | 指示代码是否用于指示读取器将以下数据解释为条码读取器的初始化或重新编程指令。 |
| [setRows(int value)](#setRows-int-) | 标识行数。 |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | 标识 DotCode 结构化追加模式条码的 ID。 |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | 标识 DotCode 结构化追加模式条码的数量。 |
| [toString()](#toString--) | 返回此 [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) 的人类可读字符串表示。 |
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


标识列数。DotCode 符号的行数与列数之和必须为奇数。列数必须至少为 5。默认值：-1

**Returns:**
整数
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


标识 ECI 编码。当 DotCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1

**Returns:**
整数
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


标识 DotCode 编码模式。默认值：Auto。

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


标识行数。DotCode 符号的行数与列数之和必须为奇数。行数必须至少为 5。默认值：-1

**Returns:**
整数
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


标识 DotCode 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。默认值为 -1。

**Returns:**
整数
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


标识 DotCode 结构化追加模式条码的数量。默认值为 -1。数量必须在 1 到 35 之间。

**Returns:**
整数
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


指示代码是否用于指示读取器将以下数据解释为条码读取器的初始化或重新编程指令。默认值为 false。

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

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


标识列数。DotCode 符号的行数与列数之和必须为奇数。列数必须至少为 5。默认值：-1

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


标识 ECI 编码。当 DotCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


标识 DotCode 编码模式。默认值：Auto。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


指示代码是否用于指示读取器将以下数据解释为条码读取器的初始化或重新编程指令。默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


标识行数。DotCode 符号的行数与列数之和必须为奇数。行数必须至少为 5。默认值：-1

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


标识 DotCode 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。默认值为 -1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


标识 DotCode 结构化追加模式条码的数量。默认值为 -1。数量必须在 1 到 35 之间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### toString() {#toString--}
```
public String toString()
```


返回此 [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此 [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) 的字符串。
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

