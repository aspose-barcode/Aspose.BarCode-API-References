---
title: MaxiCodeParameters
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: MaxiCode 参数。
type: docs
weight: 57
url: /zh/androidjava/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

MaxiCode 参数。
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D 条码模块的高/宽比。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 获取 ECI 编码。 |
| [getEncodeMode()](#getEncodeMode--) | 获取 MaxiCode 编码模式。 |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | 获取 MaxiCode 编码模式。 |
| [getMaxiCodeMode()](#getMaxiCodeMode--) | 获取 MaxiCode 编码模式。 |
| [getMaxiCodeStructuredAppendModeBarcodeId()](#getMaxiCodeStructuredAppendModeBarcodeId--) | 获取结构化追加模式下的 MaxiCode 条形码 ID。 |
| [getMaxiCodeStructuredAppendModeBarcodesCount()](#getMaxiCodeStructuredAppendModeBarcodesCount--) | 获取结构化追加模式下的 MaxiCode 条形码计数。 |
| [getMode()](#getMode--) | 获取 MaxiCode 编码模式。 |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | 获取结构化追加模式下的 MaxiCode 条形码 ID。 |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | 获取结构化追加模式下的 MaxiCode 条形码计数。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D 条码模块的高/宽比。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 设置 ECI 编码。 |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | 设置 MaxiCode 编码模式。 |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | 设置 MaxiCode 编码模式。 |
| [setMaxiCodeMode(int value)](#setMaxiCodeMode-int-) | 设置 MaxiCode 编码模式。 |
| [setMaxiCodeStructuredAppendModeBarcodeId(int value)](#setMaxiCodeStructuredAppendModeBarcodeId-int-) | 在结构化追加模式下设置 MaxiCode 条形码 ID。 |
| [setMaxiCodeStructuredAppendModeBarcodesCount(int value)](#setMaxiCodeStructuredAppendModeBarcodesCount-int-) | 在结构化追加模式下设置 MaxiCode 条形码数量。 |
| [setMode(int value)](#setMode-int-) | 设置 MaxiCode 编码模式。 |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | 在结构化追加模式下设置 MaxiCode 条形码 ID。 |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | 在结构化追加模式下设置 MaxiCode 条形码数量。 |
| [toString()](#toString--) | 返回此 [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) 的可读字符串表示。 |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


获取 ECI 编码。当 MaxiCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1

**Returns:**
int - ECI 编码。
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


获取 MaxiCode 编码模式。默认值：Auto。

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


获取 MaxiCode 编码模式。默认值：Auto。

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeMode() {#getMaxiCodeMode--}
```
public final int getMaxiCodeMode()
```


获取 MaxiCode 编码模式。

**Returns:**
int - 一个 MaxiCode 编码模式。
### getMaxiCodeStructuredAppendModeBarcodeId() {#getMaxiCodeStructuredAppendModeBarcodeId--}
```
public final int getMaxiCodeStructuredAppendModeBarcodeId()
```


在结构化追加模式下获取 MaxiCode 条形码 ID。ID 必须在 1 到 8 之间。默认值：0

**Returns:**
int - 一个结构化追加模式下的 MaxiCode 条形码 ID。
### getMaxiCodeStructuredAppendModeBarcodesCount() {#getMaxiCodeStructuredAppendModeBarcodesCount--}
```
public final int getMaxiCodeStructuredAppendModeBarcodesCount()
```


在结构化追加模式下获取 MaxiCode 条形码数量。计数必须在 2 到 8 之间（最大条形码数量）。默认值：-1

**Returns:**
int - 一个结构化追加模式下的 MaxiCode 条形码计数。
### getMode() {#getMode--}
```
public final int getMode()
```


获取 MaxiCode 编码模式。

**Returns:**
int - 一个 MaxiCode 编码模式。
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


在结构化追加模式下获取 MaxiCode 条形码 ID。ID 必须在 1 到 8 之间。默认值：0

**Returns:**
int - 一个结构化追加模式下的 MaxiCode 条形码 ID。
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


在结构化追加模式下获取 MaxiCode 条形码数量。计数必须在 2 到 8 之间（最大条形码数量）。默认值：-1

**Returns:**
int - 一个结构化追加模式下的 MaxiCode 条形码计数。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


设置 ECI 编码。当 MaxiCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | ECI 编码。 |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


设置 MaxiCode 编码模式。默认值：Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | 一个 MaxiCode 编码模式。 |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


设置 MaxiCode 编码模式。默认值：Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | 一个 MaxiCode 编码模式。 |

### setMaxiCodeMode(int value) {#setMaxiCodeMode-int-}
```
public final void setMaxiCodeMode(int value)
```


设置 MaxiCode 编码模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 一个 MaxiCode 编码模式。 |

### setMaxiCodeStructuredAppendModeBarcodeId(int value) {#setMaxiCodeStructuredAppendModeBarcodeId-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodeId(int value)
```


在结构化追加模式下设置 MaxiCode 条形码 ID。ID 必须在 1 到 8 之间。默认值：0

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 结构化追加模式下的 MaxiCode 条形码 ID。 |

### setMaxiCodeStructuredAppendModeBarcodesCount(int value) {#setMaxiCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodesCount(int value)
```


在结构化追加模式下设置 MaxiCode 条形码数量。计数必须在 2 到 8 之间（最大条形码数量）。默认值：-1

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 在结构化追加模式下的 MaxiCode 条形码计数。 |

### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


设置 MaxiCode 编码模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 一个 MaxiCode 编码模式。 |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


在结构化追加模式下设置 MaxiCode 条形码 ID。ID 必须在 1 到 8 之间。默认值：0

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 结构化追加模式下的 MaxiCode 条形码 ID。 |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


在结构化追加模式下设置 MaxiCode 条形码数量。计数必须在 2 到 8 之间（最大条形码数量）。默认值：-1

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 在结构化追加模式下的 MaxiCode 条形码计数。 |

### toString() {#toString--}
```
public String toString()
```


返回此 [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) 的可读字符串表示。

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

