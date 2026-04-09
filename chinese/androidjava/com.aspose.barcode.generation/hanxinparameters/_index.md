---
title: HanXinParameters
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: Han Xin 参数。
type: docs
weight: 50
url: /zh/androidjava/com.aspose.barcode.generation/hanxinparameters/
---
**Inheritance:**
java.lang.Object
```
public class HanXinParameters
```

Han Xin 参数。
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 扩展通道解释标识符。 |
| [getEncodeMode()](#getEncodeMode--) | HanXin 编码模式。 |
| [getErrorLevel()](#getErrorLevel--) | Han Xin 条码的 Reed-Solomon 错误更正级别。 |
| [getHanXinECIEncoding()](#getHanXinECIEncoding--) | 扩展通道解释标识符。 |
| [getHanXinEncodeMode()](#getHanXinEncodeMode--) | HanXin 编码模式。 |
| [getHanXinErrorLevel()](#getHanXinErrorLevel--) | Han Xin 条码的 Reed-Solomon 错误更正级别。 |
| [getHanXinVersion()](#getHanXinVersion--) | HanXin Code 的版本。 |
| [getVersion()](#getVersion--) | HanXin Code 的版本。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 扩展通道解释标识符。 |
| [setEncodeMode(HanXinEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-) | HanXin 编码模式。 |
| [setErrorLevel(HanXinErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-) | Han Xin 条码的 Reed-Solomon 错误更正级别。 |
| [setVersion(HanXinVersion value)](#setVersion-com.aspose.barcode.generation.HanXinVersion-) | HanXin Code 的版本。 |
| [toString()](#toString--) | 返回此 [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) 的人类可读字符串表示。 |
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


扩展通道解释标识符。它用于向条码阅读器提供有关在符号中对数据进行编码所使用的参考的详细信息。当前实现包含所有已知的字符集编码。

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final HanXinEncodeMode getEncodeMode()
```


HanXin 编码模式。默认值：EncodeMode.Mixed。

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final HanXinErrorLevel getErrorLevel()
```


Han Xin 条码的 Reed-Solomon 错误更正级别。从低到高：L1、L2、L3、L4。参见 ErrorLevel。

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getHanXinECIEncoding() {#getHanXinECIEncoding--}
```
public final int getHanXinECIEncoding()
```


扩展通道解释标识符。它用于向条码阅读器提供有关在符号中对数据进行编码所使用的参考的详细信息。当前实现包含所有已知的字符集编码。

**Returns:**
int
### getHanXinEncodeMode() {#getHanXinEncodeMode--}
```
public final HanXinEncodeMode getHanXinEncodeMode()
```


HanXin 编码模式。默认值：EncodeMode.Mixed。

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getHanXinErrorLevel() {#getHanXinErrorLevel--}
```
public final HanXinErrorLevel getHanXinErrorLevel()
```


Han Xin 条码的 Reed-Solomon 错误更正级别。从低到高：L1、L2、L3、L4。参见 ErrorLevel。

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getHanXinVersion() {#getHanXinVersion--}
```
public final HanXinVersion getHanXinVersion()
```


HanXin Code 的版本。Han Xin 码的版本范围从 Version01 到 Version84。默认值为 Version.Auto。

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
### getVersion() {#getVersion--}
```
public final HanXinVersion getVersion()
```


HanXin Code 的版本。Han Xin 码的版本范围从 Version01 到 Version84。默认值为 Version.Auto。

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
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




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


扩展通道解释标识符。它用于向条码阅读器提供有关在符号中对数据进行编码所使用的参考的详细信息。当前实现包含所有已知的字符集编码。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setEncodeMode(HanXinEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-}
```
public final void setEncodeMode(HanXinEncodeMode value)
```


HanXin 编码模式。默认值：EncodeMode.Mixed。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode) |  |

### setErrorLevel(HanXinErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-}
```
public final void setErrorLevel(HanXinErrorLevel value)
```


Han Xin 条码的 Reed-Solomon 错误更正级别。从低到高：L1、L2、L3、L4。参见 ErrorLevel。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel) |  |

### setVersion(HanXinVersion value) {#setVersion-com.aspose.barcode.generation.HanXinVersion-}
```
public final void setVersion(HanXinVersion value)
```


HanXin Code 的版本。Han Xin 码的版本范围从 Version01 到 Version84。默认值为 Version.Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [HanXinVersion](../../com.aspose.barcode.generation/hanxinversion) |  |

### toString() {#toString--}
```
public String toString()
```


返回此 [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此 [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) 的字符串。
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

