---
title: "MaxiCodeParameters"
second_title: "Aspose.BarCode for Android via Java API 参考"
description: "MaxiCode 参数。"
type: docs
weight: 55
url: /zh/androidjava/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

MaxiCode 参数。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 二维条码模块的高宽比。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 获取 ECI 编码。 |
| [getEncodeMode()](#getEncodeMode--) | 获取 MaxiCode 编码模式。 |
| [getMode()](#getMode--) | 获取 MaxiCode 编码模式。 |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | 获取结构化追加模式下的 MaxiCode 条形码 ID。 |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | 获取结构化追加模式下的 MaxiCode 条形码数量。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 二维条码模块的高宽比。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 设置 ECI 编码。 |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | 设置 MaxiCode 编码模式。 |
| [setMode(MaxiCodeMode value)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | 设置 MaxiCode 编码模式。 |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | 设置结构化追加模式下的 MaxiCode 条形码 ID。 |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | 设置结构化追加模式下的 MaxiCode 条形码数量。 |
| [toString()](#toString--) | 返回此 [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) 的人类可读字符串表示。 |
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


获取 ECI 编码。用于 MaxiCodeEncodeMode 为 Auto 时。默认值：ISO-8859-1。

**Returns:**
int - ECI 编码。
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


获取 MaxiCode 编码模式。默认值：Auto。

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public final MaxiCodeMode getMode()
```


获取 MaxiCode 编码模式。

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - a MaxiCode encode mode.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


获取结构化追加模式下的 MaxiCode 条形码 ID。ID 必须在 1 到 8 之间。默认值：0

**Returns:**
int - 结构化追加模式下的 MaxiCode 条形码 ID。
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


获取结构化追加模式下的 MaxiCode 条形码数量。计数必须在 2 到 8 之间（最大条形码数量）。默认值：-1

**Returns:**
int - 结构化追加模式下的 MaxiCode 条形码数量。
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
整数
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


设置 ECI 编码。用于 MaxiCodeEncodeMode 为 Auto 时。默认值：ISO-8859-1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 | ECI 编码。 |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


设置 MaxiCode 编码模式。默认值：Auto。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | 一个 MaxiCode 编码模式。 |

### setMode(MaxiCodeMode value) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public final void setMode(MaxiCodeMode value)
```


设置 MaxiCode 编码模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) | 一个 MaxiCode 编码模式。 |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


设置结构化追加模式下的 MaxiCode 条形码 ID。ID 必须在 1 到 8 之间。默认值：0

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 | 结构化追加模式下的 MaxiCode 条形码 ID。 |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


设置结构化追加模式下的 MaxiCode 条形码数量。计数必须在 2 到 8 之间（最大条形码数量）。默认值：-1

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 | 结构化追加模式下的 MaxiCode 条形码数量。 |

### toString() {#toString--}
```
public String toString()
```


返回此 [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此 [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) 的字符串。
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

