---
title: QrParameters
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: QR 参数。
type: docs
weight: 64
url: /zh/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

QR 参数。
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D 条码模块的高/宽比。 |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 扩展通道解释标识符。 |
| [getEncodeMode()](#getEncodeMode--) | 条码编码模式的 QR 符号类型。 |
| [getErrorLevel()](#getErrorLevel--) | QR、MicroQR 和 RectMicroQR 条码的 Reed-Solomon 错误纠正级别。 |
| [getMicroQRVersion()](#getMicroQRVersion--) | MicroQR 码的版本。 |
| [getQrECIEncoding()](#getQrECIEncoding--) | 扩展通道解释标识符。 |
| [getQrEncodeMode()](#getQrEncodeMode--) | 条码编码模式的 QR 符号类型。 |
| [getQrEncodeType()](#getQrEncodeType--) | QR / MicroQR 选择模式。 |
| [getQrErrorLevel()](#getQrErrorLevel--) | QR、MicroQR 和 RectMicroQR 条码的 Reed-Solomon 错误纠正级别。 |
| [getQrVersion()](#getQrVersion--) | QR 码的版本。从 Version1 到 Version40。 |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | RectMicroQR 码的版本。 |
| [getStructuredAppend()](#getStructuredAppend--) | QR 结构化追加参数。 |
| [getVersion()](#getVersion--) | QR 码的版本。从 Version1 到 Version40。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D 条码模块的高/宽比。 |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 扩展通道解释标识符。 |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | 条码编码模式的 QR 符号类型。 |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | QR、MicroQR 和 RectMicroQR 条码的 Reed-Solomon 错误纠正级别。 |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | MicroQR 码的版本。 |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | QR / MicroQR 选择模式。 |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | RectMicroQR 码的版本。 |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | QR 结构化追加参数。 |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | QR 码的版本。从 Version1 到 Version40。 |
| [toString()](#toString--) | 返回此 [QrParameters](../../com.aspose.barcode.generation/qrparameters) 的人类可读字符串表示。 |
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


扩展信道解释标识符。用于告诉条码阅读器有关在符号中对数据进行编码所使用的引用的详细信息。当前实现包含所有已知的字符集编码。MicroQR 不支持。

**Returns:**
int
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


QR、MicroQR 和 RectMicroQR 条形码的 Reed-Solomon 错误更正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。参见 QRErrorLevel。

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


MicroQR 码的版本。从 M1 版到 M4 版。默认值为 MicroQRVersion.Auto。

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQrECIEncoding() {#getQrECIEncoding--}
```
public final int getQrECIEncoding()
```


扩展信道解释标识符。用于告诉条码阅读器有关在符号中对数据进行编码所使用的引用的详细信息。当前实现包含所有已知的字符集编码。MicroQR 不支持。

**Returns:**
int
### getQrEncodeMode() {#getQrEncodeMode--}
```
public final QREncodeMode getQrEncodeMode()
```


条码编码模式的 QR 符号类型。默认值：QREncodeMode.Auto。

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getQrEncodeType() {#getQrEncodeType--}
```
public final QREncodeType getQrEncodeType()
```


QR / MicroQR 选择模式。对标准 QR 符号选择 ForceQR，对 MicroQR 选择 Auto。

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### getQrErrorLevel() {#getQrErrorLevel--}
```
public final QRErrorLevel getQrErrorLevel()
```


QR、MicroQR 和 RectMicroQR 条形码的 Reed-Solomon 错误更正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。参见 QRErrorLevel。

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public final QRVersion getQrVersion()
```


QR 码的版本。从 Version1 到 Version40。默认值为 QRVersion.Auto。

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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


QR 结构化追加参数。MicroQR 和 RectMicroQR 条形码不支持结构化追加模式。

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


扩展信道解释标识符。用于告诉条码阅读器有关在符号中对数据进行编码所使用的引用的详细信息。当前实现包含所有已知的字符集编码。MicroQR 不支持。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


条码编码模式的 QR 符号类型。默认值：QREncodeMode.Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


QR、MicroQR 和 RectMicroQR 条形码的 Reed-Solomon 错误更正级别。从低到高：LevelL、LevelM、LevelQ、LevelH。参见 QRErrorLevel。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


MicroQR 码的版本。从 M1 版到 M4 版。默认值为 MicroQRVersion.Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setQrEncodeType(QREncodeType value) {#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-}
```
public final void setQrEncodeType(QREncodeType value)
```


QR / MicroQR 选择模式。对标准 QR 符号选择 ForceQR，对 MicroQR 选择 Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [QREncodeType](../../com.aspose.barcode.generation/qrencodetype) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


RectMicroQR 码的版本。从 R7x59 版到 R17x139 版。默认值为 RectMicroQRVersion.Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


QR 结构化追加参数。MicroQR 和 RectMicroQR 条形码不支持结构化追加模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


QR 码的版本。从 Version1 到 Version40。默认值为 QRVersion.Auto。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


返回此 [QrParameters](../../com.aspose.barcode.generation/qrparameters) 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此 [QrParameters](../../com.aspose.barcode.generation/qrparameters) 的字符串。
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

