---
title: "QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Speichert Structured‑Append-Informationen eines erkannten QR‑Barcodes."
type: docs
weight: 810
url: /de/nodejs/aspose.barcode/qrextendedparameters/
---

## QRExtendedParameters class

Speichert Structured‑Append-Informationen eines erkannten QR‑Barcodes.

```js
new QRExtendedParameters()
```

**Example:**

```js
//This sample shows how to get QR Structured Append data

let reader = new BarCodeReader("test.png", null,  DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
   console.log("QR Structured Append Index: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodeIndex());
   console.log("QR Structured Append ParityData: " + result.getExtended().getQR().getQRStructuredAppendModeParityData());
}
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [equals(obj)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen QRExtendedParameters-Wert entspricht. |
| [getErrorLevel()](#geterrorlevel) | Reed-Solomon-Fehlerkorrekturstufe des erkannten Barcodes. Von niedrig bis hoch: LevelL, LevelM, LevelQ, LevelH. |
| [getMicroQRVersion()](#getmicroqrversion) | Version des erkannten MicroQR-Codes. Von M1 bis M4. |
| [getQRErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Reed-Solomon-Fehlerkorrekturstufe des erkannten Barcodes. Von niedrig bis hoch: LevelL, LevelM, LevelQ, LevelH. |
| [getQRStructuredAppendModeBarCodeIndex()](#getqrstructuredappendmodebarcodeindex) ~~(deprecated)~~ | Ermittelt den Index des QR Structured Append Mode Barcodes. Der Index beginnt bei 0. Standardwert ist -1. Wert: Die Menge von |
| [getQRStructuredAppendModeBarCodesQuantity()](#getqrstructuredappendmodebarcodesquantity) ~~(deprecated)~~ | Ermittelt die Menge der QR Structured Append Mode Barcodes. Standardwert ist -1. Wert: Die Menge des QR structured appen |
| [getQRStructuredAppendModeParityData()](#getqrstructuredappendmodeparitydata) ~~(deprecated)~~ | Ermittelt die Paritätsdaten des QR Structured Append Mode. Standardwert ist -1. Wert: Der Index des QR Structured Append Mode ba |
| [getQRVersion()](#getqrversion) ~~(deprecated)~~ | Version des erkannten QR-Codes. Von Version1 bis Version40. |
| [getRectMicroQRVersion()](#getrectmicroqrversion) | Version des erkannten RectMicroQR-Codes. Von R7x43 bis R17x139. |
| [getStructuredAppendModeBarCodeIndex()](#getstructuredappendmodebarcodeindex) | Ermittelt den Index des QR Structured Append Mode Barcodes. Der Index beginnt bei 0. Standardwert ist -1. Wert: Die Menge o |
| [getStructuredAppendModeBarCodesQuantity()](#getstructuredappendmodebarcodesquantity) | Ermittelt die Menge der QR Structured Append Mode Barcodes. Standardwert ist -1. Wert: Die Menge des QR structured appe |
| [getStructuredAppendModeParityData()](#getstructuredappendmodeparitydata) | Ermittelt die Paritätsdaten des QR Structured Append Mode. Standardwert ist -1. Wert: Der Index des QR structured append mode b |
| [getVersion()](#getversion) | Version des erkannten QR-Codes. Von Version1 bis Version40. |
| [hashCode()](#hashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [isEmpty()](#isempty) | Testet, ob alle Parameter nur Standardwerte haben. Wert |
| [toString()](#tostring) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses QRExtendedParameters zurück. |

### equals(obj) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen QRExtendedParameters-Wert entspricht.

| Parameter | Beschreibung |
| --- | --- |
| obj | Ein Objektwert zum Vergleich mit dieser Instanz. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getErrorLevel() {#geterrorlevel}

Reed-Solomon-Fehlerkorrekturstufe des erkannten Barcodes. Von niedrig bis hoch: LevelL, LevelM, LevelQ, LevelH.

### getMicroQRVersion() {#getmicroqrversion}

Version des erkannten MicroQR-Codes. Von M1 bis M4.

**Returns:** Version of recognized MicroQR Code. From M1 to M4.

### getQRErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Reed-Solomon-Fehlerkorrekturstufe des erkannten Barcodes. Von niedrig bis hoch: LevelL, LevelM, LevelQ, LevelH.

**Returns:** Reed-Solomon error correction level of recognized barcode.

### getQRStructuredAppendModeBarCodeIndex() {#getqrstructuredappendmodebarcodeindex}

> **Deprecated.** See method description for replacement.

Ermittelt den Index des QR structured append mode Barcodes. Der Index beginnt bei 0. Standardwert ist -1.Wert: Die Menge des QR structured append mode Barcodes.

### getQRStructuredAppendModeBarCodesQuantity() {#getqrstructuredappendmodebarcodesquantity}

> **Deprecated.** See method description for replacement.

Ermittelt die Menge der QR structured append mode Barcodes. Standardwert ist -1.Wert: Die Menge des QR structured append mode Barcodes.

### getQRStructuredAppendModeParityData() {#getqrstructuredappendmodeparitydata}

> **Deprecated.** See method description for replacement.

Ermittelt die Paritätsdaten des QR structured append mode. Standardwert ist -1.Wert: Der Index des QR structured append mode Barcodes.

### getQRVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Version des erkannten QR-Codes. Von Version1 bis Version40.

**Returns:** Version of recognized QR Code

### getRectMicroQRVersion() {#getrectmicroqrversion}

Version des erkannten RectMicroQR-Codes. Von R7x43 bis R17x139.

**Returns:** Version of recognized RectMicroQR Code

### getStructuredAppendModeBarCodeIndex() {#getstructuredappendmodebarcodeindex}

Ermittelt den Index des QR structured append mode Barcodes. Der Index beginnt bei 0. Standardwert ist -1. Wert: Die Menge des QR structured append mode Barcodes.

**Returns:** the index of the QR structured append mode barcode.

### getStructuredAppendModeBarCodesQuantity() {#getstructuredappendmodebarcodesquantity}

Ermittelt die Menge der QR structured append mode Barcodes. Standardwert ist -1. Wert: Die Menge des QR structured append mode Barcodes.

**Returns:** the QR structured append mode barcodes quantity.

### getStructuredAppendModeParityData() {#getstructuredappendmodeparitydata}

Ermittelt die Paritätsdaten des QR structured append mode. Standardwert ist -1. Wert: Der Index des QR structured append mode Barcodes.

**Returns:** the QR structured append mode parity data.

### getVersion() {#getversion}

Version des erkannten QR-Codes. Von Version1 bis Version40.

### hashCode() {#hashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Testet, ob alle Parameter nur Standardwerte haben. Wert

**Returns:** true if all parameters has only default values; otherwise, `false `.

### toString() {#tostring}

Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses QRExtendedParameters zurück.

**Returns:** A string that represents this QRExtendedParameters.
