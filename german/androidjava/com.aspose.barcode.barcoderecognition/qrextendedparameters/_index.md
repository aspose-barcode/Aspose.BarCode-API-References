---
title: "QRExtendedParameters"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Speichert QR Structured Append-Informationen des erkannten Barcodes"
type: docs
weight: 40
url: /de/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Speichert QR Structured Append-Informationen des erkannten Barcodes

Dieses Beispiel zeigt, wie man QR Structured Append-Daten erhält.

```
{
```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)-Wert entspricht. |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Reed-Solomon-Fehlerkorrekturstufe des erkannten Strichcodes. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Version des erkannten MicroQR-Codes. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Version des erkannten RectMicroQR-Codes. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Ermittelt den Index des QR Structured Append-Modus-Strichcodes. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Ermittelt die Anzahl der QR Structured Append-Modus-Strichcodes. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Ermittelt die Paritätsdaten des QR Structured Append-Modus. |
| [getVersion()](#getVersion--) | Version des erkannten QR-Codes. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [isEmpty()](#isEmpty--) | Prüft, ob alle Parameter nur Standardwerte haben. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) zurück. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)-Wert entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein System.Object‑Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  **true**, wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**.
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


Reed-Solomon-Fehlerkorrekturstufe des erkannten Strichcodes. Von niedrig nach hoch: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Version des erkannten MicroQR-Codes. Von M1 bis M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Version des erkannten RectMicroQR-Codes. Von R7x43 bis R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


Liefert den Index des QR structured append mode barcode. Index beginnt bei 0. Standardwert ist -1.

Wert: Die Menge des QR structured append mode barcode.

**Returns:**
int – der Index des QR structured append mode barcode.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Liefert die Menge der QR structured append mode Barcodes. Standardwert ist -1.

Wert: Die Menge des QR structured append mode barcode.

**Returns:**
int – die Menge der QR structured append mode Barcodes.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Liefert die Paritätsdaten des QR structured append mode. Standardwert ist -1.

Wert: Der Index des QR structured append mode barcode.

**Returns:**
int – die Paritätsdaten des QR structured append mode.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Version des erkannten QR-Codes. Von Version1 bis Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32‑Bit vorzeichenbehafteter Integer‑Hashcode.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Prüft, ob alle Parameter nur Standardwerte haben.

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

