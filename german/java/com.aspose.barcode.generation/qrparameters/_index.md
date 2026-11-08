---
title: "QrParameters"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "QR-Parameter."
type: docs
weight: 62
url: /de/java/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

QR-Parameter.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höhen-/Breitenverhältnis des 2D-BarCode-Moduls. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation Bezeichner. |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) |  |
| [getEncodeMode()](#getEncodeMode--) | QR‑Symboltyp des Codierungsmodus von BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Fehlerkorrektur‑Level des Reed‑Solomon‑Verfahrens für QR-, MicroQR‑ und RectMicroQR‑Barcodes. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Version des MicroQR-Codes. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Version des RectMicroQR-Codes. |
| [getStructuredAppend()](#getStructuredAppend--) | QR Structured Append-Parameter. |
| [getVersion()](#getVersion--) | Version des QR‑Codes. Von Version1 bis Version40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höhen-/Breitenverhältnis des 2D-BarCode-Moduls. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Extended Channel Interpretation Bezeichner. |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) |  |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | QR‑Symboltyp des Codierungsmodus von BarCode. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Fehlerkorrektur‑Level des Reed‑Solomon‑Verfahrens für QR-, MicroQR‑ und RectMicroQR‑Barcodes. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | Version des MicroQR-Codes. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Version des RectMicroQR-Codes. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | QR Structured Append-Parameter. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Version des QR‑Codes. Von Version1 bis Version40. |
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
public final int getECIEncoding()
```


Extended Channel Interpretation Identifiers. Sie werden verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Datenkodierung im Symbol mitzuteilen. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen. Nicht unterstützt von MicroQR.

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public final boolean getEncodeGS1SeparatorInByteMode()
```


Liest oder setzt einen Wert, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Barcodes codiert werden sollen.

Wenn false, können GS1‑Trennzeichen gemäß QR‑Spezifikation im alphanumerischen Modus als '%' codiert werden.

Wenn true, werden GS1‑Gruppentrennzeichen im Byte‑Modus als das Zeichen 0x1D codiert, und '%'‑Zeichen werden ebenfalls im Byte‑Modus codiert, um sie als Daten zu erhalten.

Diese Option kann die Kompatibilität mit Decodern verbessern, die byte‑level GS1‑Gruppentrennzeichen erwarten, und verhindert, dass '%'‑Datenzeichen als GS1‑Trennzeichen interpretiert werden.

**Returns:**
boolean – ein Wert, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Barcodes kodiert werden sollen.
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


Fehlerkorrektur‑Level des Reed‑Solomon‑Verfahrens für QR-, MicroQR‑ und RectMicroQR‑Barcodes. Von niedrig nach hoch: LevelL, LevelM, LevelQ, LevelH. Siehe QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
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
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


QR‑Parameter für strukturiertes Anhängen. Der strukturierte Anfügemodus wird von MicroQR‑ und RectMicroQR‑Barcodes nicht unterstützt.

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Version des QR‑Codes. Von Version1 bis Version40. Standardwert ist QRVersion.Auto.

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


Höhen-/Breitenverhältnis des 2D-BarCode-Moduls.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Extended Channel Interpretation Identifiers. Sie werden verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Datenkodierung im Symbol mitzuteilen. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen. Nicht unterstützt von MicroQR.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public final void setEncodeGS1SeparatorInByteMode(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Barcodes codiert werden sollen.

Wenn false, können GS1‑Trennzeichen gemäß QR‑Spezifikation im alphanumerischen Modus als '%' codiert werden.

Wenn true, werden GS1‑Gruppentrennzeichen im Byte‑Modus als das Zeichen 0x1D codiert, und '%'‑Zeichen werden ebenfalls im Byte‑Modus codiert, um sie als Daten zu erhalten.

Diese Option kann die Kompatibilität mit Decodern verbessern, die byte‑level GS1‑Gruppentrennzeichen erwarten, und verhindert, dass '%'‑Datenzeichen als GS1‑Trennzeichen interpretiert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch | ein Wert, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Barcodes kodiert werden sollen. |

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


Fehlerkorrektur‑Level des Reed‑Solomon‑Verfahrens für QR-, MicroQR‑ und RectMicroQR‑Barcodes. Von niedrig nach hoch: LevelL, LevelM, LevelQ, LevelH. Siehe QRErrorLevel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
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

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


QR‑Parameter für strukturiertes Anhängen. Der strukturierte Anfügemodus wird von MicroQR‑ und RectMicroQR‑Barcodes nicht unterstützt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Version des QR‑Codes. Von Version1 bis Version40. Standardwert ist QRVersion.Auto.

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

