---
title: "QrParameters"
second_title: "Aspose.BarCode for Java API Reference"
description: "QR 参数。"
type: docs
weight: 62
url: /zh/java/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

QR 参数。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D 条码模块的高/宽比。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 扩展通道解释标识符。 |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) |  |
| [getEncodeMode()](#getEncodeMode--) | 条码编码模式的 QR 符号类型。 |
| [getErrorLevel()](#getErrorLevel--) | QR、MicroQR 和 RectMicroQR 条码的 Reed-Solomon 错误更正级别。 |
| [getMicroQRVersion()](#getMicroQRVersion--) | MicroQR Code 的版本。 |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | RectMicroQR Code 的版本。 |
| [getStructuredAppend()](#getStructuredAppend--) | QR 结构化追加参数。 |
| [getVersion()](#getVersion--) | QR 码的版本。从 Version1 到 Version40。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D 条码模块的高/宽比。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 扩展通道解释标识符。 |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) |  |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | 条码编码模式的 QR 符号类型。 |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | QR、MicroQR 和 RectMicroQR 条码的 Reed-Solomon 错误更正级别。 |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | MicroQR Code 的版本。 |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | RectMicroQR Code 的版本。 |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | QR 结构化追加参数。 |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | QR 码的版本。从 Version1 到 Version40。 |
| [toString()](#toString--) | 返回此 [QrParameters](../../com.aspose.barcode.generation/qrparameters) 的可读字符串表示。 |
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


扩展信道解释标识符。用于向条码阅读器提供有关在符号中编码数据所使用的参考的详细信息。当前实现包含所有已知的字符集编码。MicroQR 不支持。

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public final boolean getEncodeGS1SeparatorInByteMode()
```


获取或设置一个值，指示是否应在 QR 和 RectMicroQR 条码的字节模式下对 GS1 特殊字符进行编码。

如果为 false，则根据 QR 规范，GS1 分隔符可能在字母数字模式下被编码为 '%'.

如果为 true，GS1 组分隔符在字节模式下被编码为 0x1D 字符，且 '%' 字符也在字节模式下编码，以将其保留为数据。

此选项可能提升对期望字节级 GS1 组分隔符的解码器的兼容性，并防止将 '%' 数据字符解释为 GS1 分隔符。

**Returns:**
boolean - 一个值，指示是否应在 QR 和 RectMicroQR 条码的字节模式下对 GS1 特殊字符进行编码。
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


条码编码模式的 QR 符号类型。默认值：QREncodeMode.Auto。

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


QR、MicroQR 和 RectMicroQR 条码的 Reed-Solomon 错误更正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。参见 QRErrorLevel。

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


MicroQR 码的版本。从 M1 版到 M4 版。默认值为 MicroQRVersion.Auto。

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


RectMicroQR 码的版本。从 R7x59 版到 R17x139 版。默认值为 RectMicroQRVersion.Auto。

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


QR 结构化追加参数。结构化追加模式不受 MicroQR 和 RectMicroQR 条码支持。

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


QR 码的版本。从 Version1 到 Version40。默认值为 QRVersion.Auto。

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public final int hashCode()
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


扩展信道解释标识符。用于向条码阅读器提供有关在符号中编码数据所使用的参考的详细信息。当前实现包含所有已知的字符集编码。MicroQR 不支持。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public final void setEncodeGS1SeparatorInByteMode(boolean value)
```


获取或设置一个值，指示是否应在 QR 和 RectMicroQR 条码的字节模式下对 GS1 特殊字符进行编码。

如果为 false，则根据 QR 规范，GS1 分隔符可能在字母数字模式下被编码为 '%'.

如果为 true，GS1 组分隔符在字节模式下被编码为 0x1D 字符，且 '%' 字符也在字节模式下编码，以将其保留为数据。

此选项可能提升对期望字节级 GS1 组分隔符的解码器的兼容性，并防止将 '%' 数据字符解释为 GS1 分隔符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 一个值，指示是否应在 QR 和 RectMicroQR 条码的字节模式下对 GS1 特殊字符进行编码。 |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


条码编码模式的 QR 符号类型。默认值：QREncodeMode.Auto。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


QR、MicroQR 和 RectMicroQR 条码的 Reed-Solomon 错误更正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。参见 QRErrorLevel。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


MicroQR 码的版本。从 M1 版到 M4 版。默认值为 MicroQRVersion.Auto。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


RectMicroQR 码的版本。从 R7x59 版到 R17x139 版。默认值为 RectMicroQRVersion.Auto。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


QR 结构化追加参数。结构化追加模式不受 MicroQR 和 RectMicroQR 条码支持。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


QR 码的版本。从 Version1 到 Version40。默认值为 QRVersion.Auto。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


返回此 [QrParameters](../../com.aspose.barcode.generation/qrparameters) 的可读字符串表示。

**Returns:**
java.lang.String - 表示此 [QrParameters](../../com.aspose.barcode.generation/qrparameters) 的字符串。
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

