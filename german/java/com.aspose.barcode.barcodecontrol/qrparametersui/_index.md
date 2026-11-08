---
title: "QrParametersUI"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "UI-Wrapper für die Klasse com.aspose.barcode.generation.QrParameters."
type: docs
weight: 17
url: /de/java/com.aspose.barcode.barcodecontrol/qrparametersui/
---
**Inheritance:**
java.lang.Object
```
public class QrParametersUI
```

UI-Wrapper für die Klasse com.aspose.barcode.generation.QrParameters.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höhen-/Breitenverhältnis des 2D-BarCode-Moduls. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation Bezeichner. |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) | Liest oder setzt einen Wert, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Barcodes codiert werden sollen. |
| [getEncodeMode()](#getEncodeMode--) | QR‑Symboltyp des Codierungsmodus von BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Level der Reed‑Solomon-Fehlerkorrektur für QR‑, MicroQR‑ und RectMicroQR‑Barcodes. |
| [getMicroQrVersion()](#getMicroQrVersion--) | Version des MicroQR-Codes. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Version des RectMicroQR-Codes. |
| [getVersion()](#getVersion--) | Version des QR-Codes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höhen-/Breitenverhältnis des 2D-BarCode-Moduls. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Extended Channel Interpretation Bezeichner. |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) | Liest oder setzt einen Wert, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Barcodes codiert werden sollen. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | QR‑Symboltyp des Codierungsmodus von BarCode. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Level der Reed‑Solomon-Fehlerkorrektur für QR‑, MicroQR‑ und RectMicroQR‑Barcodes. |
| [setMicroQrVersion(MicroQRVersion value)](#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-) | Version des MicroQR-Codes. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Version des RectMicroQR-Codes. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Version des QR-Codes. |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieser [QrParameters](../../com.aspose.barcode.generation/qrparameters) zurück. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolesch
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Höhen-/Breitenverhältnis des 2D-BarCode-Moduls.

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
public int getECIEncoding()
```


Extended Channel Interpretation Identifiers. Sie werden verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Datenkodierung im Symbol mitzuteilen. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen. Nicht unterstützt von MicroQR.

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public boolean getEncodeGS1SeparatorInByteMode()
```


Liest oder setzt einen Wert, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Barcodes codiert werden sollen.

Wenn false, können GS1‑Trennzeichen gemäß QR‑Spezifikation im alphanumerischen Modus als '%' codiert werden.

Wenn true, werden GS1‑Gruppentrennzeichen im Byte‑Modus als das Zeichen 0x1D codiert, und '%'‑Zeichen werden ebenfalls im Byte‑Modus codiert, um sie als Daten zu erhalten.

Diese Option kann die Kompatibilität mit Decodern verbessern, die byte‑level GS1‑Gruppentrennzeichen erwarten, und verhindert, dass '%'‑Datenzeichen als GS1‑Trennzeichen interpretiert werden.

**Returns:**
boolesch
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


QR‑Symboltyp des Codierungsmodus von BarCode. Standardwert: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Level der Reed‑Solomon-Fehlerkorrektur für QR‑, MicroQR‑ und RectMicroQR‑Barcodes. Von niedrig bis hoch: LevelL, LevelM, LevelQ, LevelH. siehe QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQrVersion() {#getMicroQrVersion--}
```
public final MicroQRVersion getMicroQrVersion()
```


Version des MicroQR-Codes. Von Version M1 bis Version M4. Standardwert ist MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Version des RectMicroQR-Codes. Von Version R7x59 bis Version R17x139. Standardwert ist RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Version des QR-Codes. Von Version1 bis Version40 für QR‑Code und von M1 bis M4 für MicroQr. Standardwert ist QRVersion.Auto.

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


Höhen-/Breitenverhältnis des 2D-BarCode-Moduls.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public void setECIEncoding(int value)
```


Extended Channel Interpretation Identifiers. Sie werden verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Datenkodierung im Symbol mitzuteilen. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen. Nicht unterstützt von MicroQR.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public void setEncodeGS1SeparatorInByteMode(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Barcodes codiert werden sollen.

Wenn false, können GS1‑Trennzeichen gemäß QR‑Spezifikation im alphanumerischen Modus als '%' codiert werden.

Wenn true, werden GS1‑Gruppentrennzeichen im Byte‑Modus als das Zeichen 0x1D codiert, und '%'‑Zeichen werden ebenfalls im Byte‑Modus codiert, um sie als Daten zu erhalten.

Diese Option kann die Kompatibilität mit Decodern verbessern, die byte‑level GS1‑Gruppentrennzeichen erwarten, und verhindert, dass '%'‑Datenzeichen als GS1‑Trennzeichen interpretiert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


QR‑Symboltyp des Codierungsmodus von BarCode. Standardwert: QREncodeMode.Auto.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Level der Reed‑Solomon-Fehlerkorrektur für QR‑, MicroQR‑ und RectMicroQR‑Barcodes. Von niedrig bis hoch: LevelL, LevelM, LevelQ, LevelH. siehe QRErrorLevel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQrVersion(MicroQRVersion value) {#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQrVersion(MicroQRVersion value)
```


Version des MicroQR-Codes. Von Version M1 bis Version M4. Standardwert ist MicroQRVersion.Auto.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Version des RectMicroQR-Codes. Von Version R7x59 bis Version R17x139. Standardwert ist RectMicroQRVersion.Auto.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Version des QR-Codes. Von Version1 bis Version40 für QR‑Code und von M1 bis M4 für MicroQr. Standardwert ist QRVersion.Auto.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieser [QrParameters](../../com.aspose.barcode.generation/qrparameters) zurück.

**Returns:**
java.lang.String - Eine Zeichenkette, die diese [QrParameters](../../com.aspose.barcode.generation/qrparameters) darstellt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

