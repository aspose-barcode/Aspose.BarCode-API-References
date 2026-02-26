---
title: QrParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: QR parameters.
type: docs
weight: 64
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
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getEncodeMode()](#getEncodeMode--) | QR symbology type of BarCode's encoding mode. |
| [getErrorLevel()](#getErrorLevel--) | Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Version of MicroQR Code. |
| [getQrECIEncoding()](#getQrECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getQrEncodeMode()](#getQrEncodeMode--) | QR symbology type of BarCode's encoding mode. |
| [getQrEncodeType()](#getQrEncodeType--) | QR / MicroQR selector mode. |
| [getQrErrorLevel()](#getQrErrorLevel--) | Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. |
| [getQrVersion()](#getQrVersion--) | Version of QR Code.From Version1 to Version40. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Version of RectMicroQR Code. |
| [getStructuredAppend()](#getStructuredAppend--) | QR structured append parameters. |
| [getVersion()](#getVersion--) | Version of QR Code.From Version1 to Version40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Height/Width ratio of 2D BarCode module. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | QR symbology type of BarCode's encoding mode. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | Version of MicroQR Code. |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | QR / MicroQR selector mode. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Version of RectMicroQR Code. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | QR structured append parameters. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Version of QR Code.From Version1 to Version40. |
| [toString()](#toString--) | Returns a human-readable string representation of this [QrParameters](../../com.aspose.barcode.generation/qrparameters). |
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
public final float getAspectRatio()
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Not supported by MicroQR.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. See QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Version of MicroQR Code. From version M1 to version M4. Default value is MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQrECIEncoding() {#getQrECIEncoding--}
```
public final int getQrECIEncoding()
```


Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Not supported by MicroQR.

**Returns:**
int
### getQrEncodeMode() {#getQrEncodeMode--}
```
public final QREncodeMode getQrEncodeMode()
```


QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getQrEncodeType() {#getQrEncodeType--}
```
public final QREncodeType getQrEncodeType()
```


QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR.

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### getQrErrorLevel() {#getQrErrorLevel--}
```
public final QRErrorLevel getQrErrorLevel()
```


Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. See QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public final QRVersion getQrVersion()
```


Version of QR Code.From Version1 to Version40. Default value is QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Version of RectMicroQR Code. From version R7x59 to version R17x139. Default value is RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


QR structured append parameters. Structured append mode is not suppported by MicroQR and RectMicroQR barcodes.

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Version of QR Code.From Version1 to Version40. Default value is QRVersion.Auto.

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


Height/Width ratio of 2D BarCode module.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Not supported by MicroQR.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. See QRErrorLevel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


Version of MicroQR Code. From version M1 to version M4. Default value is MicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setQrEncodeType(QREncodeType value) {#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-}
```
public final void setQrEncodeType(QREncodeType value)
```


QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QREncodeType](../../com.aspose.barcode.generation/qrencodetype) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Version of RectMicroQR Code. From version R7x59 to version R17x139. Default value is RectMicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


QR structured append parameters. Structured append mode is not suppported by MicroQR and RectMicroQR barcodes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Version of QR Code.From Version1 to Version40. Default value is QRVersion.Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this [QrParameters](../../com.aspose.barcode.generation/qrparameters).

**Returns:**
java.lang.String - A string that represents this [QrParameters](../../com.aspose.barcode.generation/qrparameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

