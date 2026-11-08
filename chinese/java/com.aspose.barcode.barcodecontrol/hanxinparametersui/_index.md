---
title: "HanXinParametersUI"
second_title: "Aspose.BarCode for Java API Reference"
description: 
type: docs
weight: 15
url: /zh/java/com.aspose.barcode.barcodecontrol/hanxinparametersui/
---
**Inheritance:**
java.lang.Object
```
public class HanXinParametersUI
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 扩展通道解释标识符。 |
| [getEncodeMode()](#getEncodeMode--) | HanXin 条码的编码模式的符号类型。 |
| [getErrorLevel()](#getErrorLevel--) | HanXin 条码的 Reed-Solomon 错误更正级别。 |
| [getVersion()](#getVersion--) | HanXin 代码的版本。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 扩展通道解释标识符。 |
| [setEncodeMode(HanXinEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-) | HanXin 条码的编码模式的符号类型。 |
| [setErrorLevel(HanXinErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-) | HanXin 条码的 Reed-Solomon 错误更正级别。 |
| [setVersion(HanXinVersion value)](#setVersion-com.aspose.barcode.generation.HanXinVersion-) | HanXin 代码的版本。 |
| [toString()](#toString--) | 返回此 [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) 的人类可读字符串表示。 |
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


扩展通道解释标识符。它用于向条码读取器提供有关在符号中编码数据所使用的参考的详细信息。当前实现包含所有已知的字符集编码。

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final HanXinEncodeMode getEncodeMode()
```


HanXin 条码的编码模式的符号类型。默认值：EncodeMode.Auto。

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final HanXinErrorLevel getErrorLevel()
```


HanXin 条码的 Reed-Solomon 错误更正级别。从低到高：L1 - L4。参见 ErrorLevel。

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getVersion() {#getVersion--}
```
public final HanXinVersion getVersion()
```


HanXin 码的版本。从 Version01 到 Version84。默认值为 Version.Auto。

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


扩展通道解释标识符。它用于向条码读取器提供有关在符号中编码数据所使用的参考的详细信息。当前实现包含所有已知的字符集编码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setEncodeMode(HanXinEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-}
```
public final void setEncodeMode(HanXinEncodeMode value)
```


HanXin 条码的编码模式的符号类型。默认值：EncodeMode.Auto。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode) |  |

### setErrorLevel(HanXinErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-}
```
public final void setErrorLevel(HanXinErrorLevel value)
```


HanXin 条码的 Reed-Solomon 错误更正级别。从低到高：L1 - L4。参见 ErrorLevel。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel) |  |

### setVersion(HanXinVersion value) {#setVersion-com.aspose.barcode.generation.HanXinVersion-}
```
public final void setVersion(HanXinVersion value)
```


HanXin 码的版本。从 Version01 到 Version84。默认值为 Version.Auto。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [HanXinVersion](../../com.aspose.barcode.generation/hanxinversion) |  |

### toString() {#toString--}
```
public String toString()
```


返回此 [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) 的人类可读字符串表示。

**Returns:**
java.lang.String - 一个表示此 [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) 的字符串。
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

