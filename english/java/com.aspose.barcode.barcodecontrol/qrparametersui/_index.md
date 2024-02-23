---
title: QrParametersUI
second_title: Aspose.BarCode for Java API Reference
description: UI wrapper for com.aspose.barcode.generation.QrParameters class.
type: docs
weight: 17
url: /java/com.aspose.barcode.barcodecontrol/qrparametersui/
---
**Inheritance:**
java.lang.Object
```
public class QrParametersUI
```

UI wrapper for com.aspose.barcode.generation.QrParameters class.
## Fields

| Field | Description |
| --- | --- |
| [microQrVersion](#microQrVersion) |  |
| [rectMicroQrVersion](#rectMicroQrVersion) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Height/Width ratio of 2D BarCode module. |
| [getClass()](#getClass--) |  |
| [getCodeTextEncoding()](#getCodeTextEncoding--) | Gets the encoding of codetext. |
| [getMicroQrVersion()](#getMicroQrVersion--) | Version of MicroQR Code. |
| [getQrEncodeMode()](#getQrEncodeMode--) | QR symbology type of BarCode's encoding mode. |
| [getQrEncodeType()](#getQrEncodeType--) | QR / MicroQR selector mode. |
| [getQrErrorLevel()](#getQrErrorLevel--) | Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcodes. |
| [getQrVersion()](#getQrVersion--) | Version of QR Code. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Version of RectMicroQR Code. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Height/Width ratio of 2D BarCode module. |
| [setCodeTextEncoding(Charset value)](#setCodeTextEncoding-java.nio.charset.Charset-) | Sets the encoding of codetext. |
| [setMicroQrVersion(MicroQRVersion microQrVersion)](#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-) | Version of MicroQR Code. |
| [setQrEncodeMode(QREncodeMode value)](#setQrEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | QR symbology type of BarCode's encoding mode. |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | QR / MicroQR selector mode. |
| [setQrErrorLevel(QRErrorLevel value)](#setQrErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcodes. |
| [setQrVersion(QRVersion value)](#setQrVersion-com.aspose.barcode.generation.QRVersion-) | Version of QR Code. |
| [setRectMicroQrVersion(RectMicroQRVersion rectMicroQrVersion)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Version of RectMicroQR Code. |
| [toString()](#toString--) | Returns a human-readable string representation of this QrParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### microQrVersion {#microQrVersion}
```
public MicroQRVersion microQrVersion
```


### rectMicroQrVersion {#rectMicroQrVersion}
```
public RectMicroQRVersion rectMicroQrVersion
```


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


Gets the encoding of codetext.

**Returns:**
java.nio.charset.Charset
### getMicroQrVersion() {#getMicroQrVersion--}
```
public MicroQRVersion getMicroQrVersion()
```


Version of MicroQR Code. From version M1 to version M4. Default value is MicroQRVersion.AUTO.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
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


Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcodes. From low to high: LevelL, LevelM, LevelQ, LevelH. see QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public QRVersion getQrVersion()
```


Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. Default value is QRVersion.AUTO.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public RectMicroQRVersion getRectMicroQrVersion()
```


Version of RectMicroQR Code. From version R7x59 to version R17x139. Default value is RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
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


Sets the encoding of codetext.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setMicroQrVersion(MicroQRVersion microQrVersion) {#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public void setMicroQrVersion(MicroQRVersion microQrVersion)
```


Version of MicroQR Code. From version M1 to version M4. Default value is MicroQRVersion.AUTO.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| microQrVersion | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

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


Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcodes. From low to high: LevelL, LevelM, LevelQ, LevelH. see QRErrorLevel.

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

### setRectMicroQrVersion(RectMicroQRVersion rectMicroQrVersion) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public void setRectMicroQrVersion(RectMicroQRVersion rectMicroQrVersion)
```


Version of RectMicroQR Code. From version R7x59 to version R17x139. Default value is RectMicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectMicroQrVersion | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this QrParameters .

**Returns:**
java.lang.String - A string that represents this QrParameters .
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

