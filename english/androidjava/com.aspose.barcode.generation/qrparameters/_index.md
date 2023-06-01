---
title: QrParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: QR parameters.
type: docs
weight: 50
url: /androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

QR parameters.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Height/Width ratio of 2D BarCode module. |
| [getClass()](#getClass--) |  |
| [getCodeTextEncoding()](#getCodeTextEncoding--) | Gets the encoding of codetext. |
| [getQrECIEncoding()](#getQrECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getQrEncodeMode()](#getQrEncodeMode--) | QR symbology type of BarCode's encoding mode. |
| [getQrEncodeType()](#getQrEncodeType--) | QR / MicroQR selector mode. |
| [getQrErrorLevel()](#getQrErrorLevel--) | Level of Reed-Solomon error correction for QR barcode. |
| [getQrVersion()](#getQrVersion--) | Version of QR Code. |
| [getStructuredAppend()](#getStructuredAppend--) | QR structured append parameters. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Height/Width ratio of 2D BarCode module. |
| [setCodeTextEncoding(Charset value)](#setCodeTextEncoding-java.nio.charset.Charset-) | Sets the encoding of codetext. |
| [setQrECIEncoding(int value)](#setQrECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setQrEncodeMode(QREncodeMode value)](#setQrEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | QR symbology type of BarCode's encoding mode. |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | QR / MicroQR selector mode. |
| [setQrErrorLevel(QRErrorLevel value)](#setQrErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Level of Reed-Solomon error correction for QR barcode. |
| [setQrVersion(QRVersion value)](#setQrVersion-com.aspose.barcode.generation.QRVersion-) | Version of QR Code. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | QR structured append parameters. |
| [toString()](#toString--) | Returns a human-readable string representation of this  QrParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public float getAspectRatio()
```


Height/Width ratio of 2D BarCode module.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeTextEncoding() {#getCodeTextEncoding--}
```
public Charset getCodeTextEncoding()
```


Gets the encoding of codetext. Default value: UTF-8

**Returns:**
java.nio.charset.Charset
### getQrECIEncoding() {#getQrECIEncoding--}
```
public int getQrECIEncoding()
```


Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings.

**Returns:**
int
### getQrEncodeMode() {#getQrEncodeMode--}
```
public QREncodeMode getQrEncodeMode()
```


QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.AUTO.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getQrEncodeType() {#getQrEncodeType--}
```
public QREncodeType getQrEncodeType()
```


QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR.

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### getQrErrorLevel() {#getQrErrorLevel--}
```
public QRErrorLevel getQrErrorLevel()
```


Level of Reed-Solomon error correction for QR barcode. From low to high: LEVEL\_L, LEVEL\_M, LEVEL\_Q, LEVEL\_H. see QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public QRVersion getQrVersion()
```


Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. Default value is QRVersion.AUTO.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public QrStructuredAppendParameters getStructuredAppend()
```


QR structured append parameters.

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
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
public void setAspectRatio(float value)
```


Height/Width ratio of 2D BarCode module.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setCodeTextEncoding(Charset value) {#setCodeTextEncoding-java.nio.charset.Charset-}
```
public void setCodeTextEncoding(Charset value)
```


Sets the encoding of codetext. Default value: UTF-8

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setQrECIEncoding(int value) {#setQrECIEncoding-int-}
```
public void setQrECIEncoding(int value)
```


Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setQrEncodeMode(QREncodeMode value) {#setQrEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public void setQrEncodeMode(QREncodeMode value)
```


QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.AUTO.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setQrEncodeType(QREncodeType value) {#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-}
```
public void setQrEncodeType(QREncodeType value)
```


QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QREncodeType](../../com.aspose.barcode.generation/qrencodetype) |  |

### setQrErrorLevel(QRErrorLevel value) {#setQrErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public void setQrErrorLevel(QRErrorLevel value)
```


Level of Reed-Solomon error correction for QR barcode. From low to high: LEVEL\_L, LEVEL\_M, LEVEL\_Q, LEVEL\_H. see QRErrorLevel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setQrVersion(QRVersion value) {#setQrVersion-com.aspose.barcode.generation.QRVersion-}
```
public void setQrVersion(QRVersion value)
```


Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. Default value is QRVersion.AUTO.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public void setStructuredAppend(QrStructuredAppendParameters value)
```


QR structured append parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this  QrParameters .

**Returns:**
java.lang.String - A string that represents this  QrParameters .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

