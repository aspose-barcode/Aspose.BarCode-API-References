---
title: QrParameters
second_title: Aspose.BarCode für Android via Java API-Referenz
description: QR-Parameter.
type: docs
weight: 64
url: /de/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

QR-Parameter.
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höhe/Breite-Verhältnis des 2D-Barcode-Moduls. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation Bezeichner. |
| [getEncodeMode()](#getEncodeMode--) | QR‑Symboltyp des Kodierungsmodus des Barcodes. |
| [getErrorLevel()](#getErrorLevel--) | Stufe der Reed‑Solomon‑Fehlerkorrektur für QR-, MicroQR‑ und RectMicroQR‑Barcodes. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Version des MicroQR-Codes. |
| [getQrECIEncoding()](#getQrECIEncoding--) | Extended Channel Interpretation Bezeichner. |
| [getQrEncodeMode()](#getQrEncodeMode--) | QR‑Symboltyp des Kodierungsmodus des Barcodes. |
| [getQrEncodeType()](#getQrEncodeType--) | Auswahlmodus für QR / MicroQR. |
| [getQrErrorLevel()](#getQrErrorLevel--) | Stufe der Reed‑Solomon‑Fehlerkorrektur für QR-, MicroQR‑ und RectMicroQR‑Barcodes. |
| [getQrVersion()](#getQrVersion--) | Version des QR‑Codes. Von Version 1 bis Version 40. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Version des RectMicroQR-Codes. |
| [getStructuredAppend()](#getStructuredAppend--) | QR Structured Append-Parameter. |
| [getVersion()](#getVersion--) | Version des QR‑Codes. Von Version 1 bis Version 40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höhe/Breite-Verhältnis des 2D-Barcode-Moduls. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Extended Channel Interpretation Bezeichner. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | QR‑Symboltyp des Kodierungsmodus des Barcodes. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Stufe der Reed‑Solomon‑Fehlerkorrektur für QR-, MicroQR‑ und RectMicroQR‑Barcodes. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | Version des MicroQR-Codes. |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | Auswahlmodus für QR / MicroQR. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Version des RectMicroQR-Codes. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | QR Structured Append-Parameter. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Version des QR‑Codes. Von Version 1 bis Version 40. |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [QrParameters](../../com.aspose.barcode.generation/qrparameters) zurück. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Höhe/Breite-Verhältnis des 2D-Barcode-Moduls.

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


Extended Channel Interpretation‑Bezeichner. Sie werden verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Die aktuelle Implementierung umfasst alle bekannten Zeichensatzkodierungen. Nicht unterstützt von MicroQR.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


QR‑Symboltyp des Kodierungsmodus des Barcodes. Standardwert: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Level der Reed-Solomon-Fehlerkorrektur für QR-, MicroQR- und RectMicroQR-Barcodes. Von niedrig nach hoch: LevelL, LevelM, LevelQ, LevelH. Siehe QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Version des MicroQR-Codes. Von Version M1 bis Version M4. Standardwert ist MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQrECIEncoding() {#getQrECIEncoding--}
```
public final int getQrECIEncoding()
```


Extended Channel Interpretation‑Bezeichner. Sie werden verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Die aktuelle Implementierung umfasst alle bekannten Zeichensatzkodierungen. Nicht unterstützt von MicroQR.

**Returns:**
int
### getQrEncodeMode() {#getQrEncodeMode--}
```
public final QREncodeMode getQrEncodeMode()
```


QR‑Symboltyp des Kodierungsmodus des Barcodes. Standardwert: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getQrEncodeType() {#getQrEncodeType--}
```
public final QREncodeType getQrEncodeType()
```


QR-/MicroQR-Auswahlmodus. Wählen Sie ForceQR für Standard-QR‑Symbole, Auto für MicroQR.

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### getQrErrorLevel() {#getQrErrorLevel--}
```
public final QRErrorLevel getQrErrorLevel()
```


Level der Reed-Solomon-Fehlerkorrektur für QR-, MicroQR- und RectMicroQR-Barcodes. Von niedrig nach hoch: LevelL, LevelM, LevelQ, LevelH. Siehe QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public final QRVersion getQrVersion()
```


Version des QR-Codes. Von Version1 bis Version40. Standardwert ist QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Version des RectMicroQR-Codes. Von Version R7x59 bis Version R17x139. Standardwert ist RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


QR Structured Append-Parameter. Der Structured Append‑Modus wird von MicroQR- und RectMicroQR-Barcodes nicht unterstützt.

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Version des QR-Codes. Von Version1 bis Version40. Standardwert ist QRVersion.Auto.

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


Höhe/Breite-Verhältnis des 2D-Barcode-Moduls.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Extended Channel Interpretation‑Bezeichner. Sie werden verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Die aktuelle Implementierung umfasst alle bekannten Zeichensatzkodierungen. Nicht unterstützt von MicroQR.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


QR‑Symboltyp des Kodierungsmodus des Barcodes. Standardwert: QREncodeMode.Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Level der Reed-Solomon-Fehlerkorrektur für QR-, MicroQR- und RectMicroQR-Barcodes. Von niedrig nach hoch: LevelL, LevelM, LevelQ, LevelH. Siehe QRErrorLevel.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


Version des MicroQR-Codes. Von Version M1 bis Version M4. Standardwert ist MicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setQrEncodeType(QREncodeType value) {#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-}
```
public final void setQrEncodeType(QREncodeType value)
```


QR-/MicroQR-Auswahlmodus. Wählen Sie ForceQR für Standard-QR‑Symbole, Auto für MicroQR.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [QREncodeType](../../com.aspose.barcode.generation/qrencodetype) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Version des RectMicroQR-Codes. Von Version R7x59 bis Version R17x139. Standardwert ist RectMicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


QR Structured Append-Parameter. Der Structured Append‑Modus wird von MicroQR- und RectMicroQR-Barcodes nicht unterstützt.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Version des QR-Codes. Von Version1 bis Version40. Standardwert ist QRVersion.Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [QrParameters](../../com.aspose.barcode.generation/qrparameters) zurück.

**Returns:**
java.lang.String – Eine Zeichenkette, die dieses [QrParameters](../../com.aspose.barcode.generation/qrparameters) darstellt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

