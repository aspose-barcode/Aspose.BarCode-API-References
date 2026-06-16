---
title: QRExtendedParameters
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Speichert QR‑Structured‑Append‑Informationen des erkannten Strichcodes
type: docs
weight: 42
url: /de/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Speichert QR‑Structured‑Append‑Informationen des erkannten Strichcodes

Dieses Beispiel zeigt, wie man QR Structured Append-Daten erhält.

```
{
```
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) Wert entspricht. |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Reed-Solomon-Fehlerkorrekturlevel des erkannten Barcodes. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Version des erkannten MicroQR-Codes. |
| [getQRErrorLevel()](#getQRErrorLevel--) | Reed-Solomon-Fehlerkorrekturlevel des erkannten Barcodes. |
| [getQRStructuredAppendModeBarCodeIndex()](#getQRStructuredAppendModeBarCodeIndex--) | Liefert den Index des QR Structured Append-Modus-Barcodes. |
| [getQRStructuredAppendModeBarCodesQuantity()](#getQRStructuredAppendModeBarCodesQuantity--) | Liefert die Menge der QR Structured Append-Modus-Barcodes. |
| [getQRStructuredAppendModeParityData()](#getQRStructuredAppendModeParityData--) | Ruft die Paritätsdaten des QR Structured Append‑Modus ab. |
| [getQRVersion()](#getQRVersion--) | Version des erkannten QR‑Codes. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Version des erkannten RectMicroQR‑Codes. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Liefert den Index des QR Structured Append-Modus-Barcodes. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Liefert die Menge der QR Structured Append-Modus-Barcodes. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Ruft die Paritätsdaten des QR Structured Append‑Modus ab. |
| [getVersion()](#getVersion--) | Version des erkannten QR‑Codes. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [isEmpty()](#isEmpty--) | Prüft, ob alle Parameter nur Standardwerte haben |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(QRExtendedParameters first, QRExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Gibt einen Wert zurück, der angibt, ob der erste [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)-Wert dem zweiten entspricht. |
| [op_Inequality(QRExtendedParameters first, QRExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Gibt einen Wert zurück, der angibt, ob der erste [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)-Wert vom zweiten abweicht. |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) zurück. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) Wert entspricht.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein System.Object-Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  **true**  wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Reed‑Solomon-Fehlerkorrekturstufe des erkannten Barcodes. Von niedrig nach hoch: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Version des erkannten MicroQR‑Codes. Von M1 bis M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQRErrorLevel() {#getQRErrorLevel--}
```
public final QRErrorLevel getQRErrorLevel()
```


Reed‑Solomon-Fehlerkorrekturstufe des erkannten Barcodes. Von niedrig nach hoch: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQRStructuredAppendModeBarCodeIndex() {#getQRStructuredAppendModeBarCodeIndex--}
```
public final int getQRStructuredAppendModeBarCodeIndex()
```


Ruft den Index des QR Structured Append‑Modus‑Barcodes ab. Der Index beginnt bei 0. Standardwert ist -1.

Wert: Die Menge des QR Structured Append‑Modus‑Barcodes.

**Returns:**
int – der Index des QR Structured Append‑Modus‑Barcodes.
### getQRStructuredAppendModeBarCodesQuantity() {#getQRStructuredAppendModeBarCodesQuantity--}
```
public final int getQRStructuredAppendModeBarCodesQuantity()
```


Ruft die Menge der QR Structured Append‑Modus‑Barcodes ab. Standardwert ist -1.

Wert: Die Menge des QR Structured Append‑Modus‑Barcodes.

**Returns:**
int – die Menge der QR Structured Append‑Modus‑Barcodes.
### getQRStructuredAppendModeParityData() {#getQRStructuredAppendModeParityData--}
```
public final int getQRStructuredAppendModeParityData()
```


Ruft die Paritätsdaten des QR Structured Append‑Modus ab. Standardwert ist -1.

Wert: Der Index des QR Structured Append‑Modus‑Barcodes.

**Returns:**
int – die Paritätsdaten des QR Structured Append‑Modus.
### getQRVersion() {#getQRVersion--}
```
public final QRVersion getQRVersion()
```


Version des erkannten QR‑Codes. Von Version1 bis Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Version des erkannten RectMicroQR‑Codes. Von R7x43 bis R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


Ruft den Index des QR Structured Append‑Modus‑Barcodes ab. Der Index beginnt bei 0. Standardwert ist -1.

Wert: Die Menge des QR Structured Append‑Modus‑Barcodes.

**Returns:**
int – der Index des QR Structured Append‑Modus‑Barcodes.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Ruft die Menge der QR Structured Append‑Modus‑Barcodes ab. Standardwert ist -1.

Wert: Die Menge des QR Structured Append‑Modus‑Barcodes.

**Returns:**
int – die Menge der QR Structured Append‑Modus‑Barcodes.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Ruft die Paritätsdaten des QR Structured Append‑Modus ab. Standardwert ist -1.

Wert: Der Index des QR Structured Append‑Modus‑Barcodes.

**Returns:**
int – die Paritätsdaten des QR Structured Append‑Modus.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Version des erkannten QR‑Codes. Von Version1 bis Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32-Bit vorzeichenbehafteter Ganzzahl-Hashcode.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Prüft, ob alle Parameter nur Standardwerte haben

Wert: Gibt **true** zurück, wenn alle Parameter nur Standardwerte haben; andernfalls **false**.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(QRExtendedParameters first, QRExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Equality(QRExtendedParameters first, QRExtendedParameters second)
```


Gibt einen Wert zurück, der angibt, ob der erste [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)-Wert dem zweiten entspricht.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Ein erster zu vergleichender Wert |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Ein zweiter zu vergleichender Wert |

**Returns:**
boolean -  **true**  wenn der erste denselben Wert wie der zweite hat; andernfalls **false**.
### op_Inequality(QRExtendedParameters first, QRExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Inequality(QRExtendedParameters first, QRExtendedParameters second)
```


Gibt einen Wert zurück, der angibt, ob der erste [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)-Wert vom zweiten abweicht.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Ein erster zu vergleichender Wert |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Ein zweiter zu vergleichender Wert |

**Returns:**
boolean -  **true**  wenn der erste einen anderen Wert als der zweite hat; andernfalls **false**.
### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) zurück.

**Returns:**
java.lang.String – Eine Zeichenkette, die dieses [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) darstellt.
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

