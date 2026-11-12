---
title: "QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Slaat QR Structured Append-informatie van een herkende barcode op"
type: docs
weight: 810
url: /nl/nodejs/aspose.barcode/qrextendedparameters/
---

## QRExtendedParameters class

Slaat QR Structured Append-informatie van een herkende barcode op

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

| Naam | Beschrijving |
| --- | --- |
| [equals(obj)](#equals) | Retourneert een waarde die aangeeft of dit exemplaar gelijk is aan een opgegeven QRExtendedParameters-waarde. |
| [getErrorLevel()](#geterrorlevel) | Reed-Solomon-foutcorrectieniveau van herkende barcode. Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH. |
| [getMicroQRVersion()](#getmicroqrversion) | Versie van herkende MicroQR-code. Van M1 tot M4. |
| [getQRErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Reed-Solomon-foutcorrectieniveau van herkende barcode. Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH. |
| [getQRStructuredAppendModeBarCodeIndex()](#getqrstructuredappendmodebarcodeindex) ~~(deprecated)~~ | Haalt de index op van de QR gestructureerde append-modus barcode. Index begint bij 0. Standaardwaarde is -1. Waarde: De hoeveelheid van |
| [getQRStructuredAppendModeBarCodesQuantity()](#getqrstructuredappendmodebarcodesquantity) ~~(deprecated)~~ | Haalt de hoeveelheid QR gestructureerde append-modus barcodes op. Standaardwaarde is -1. Waarde: De hoeveelheid van de QR gestructureerde appen |
| [getQRStructuredAppendModeParityData()](#getqrstructuredappendmodeparitydata) ~~(deprecated)~~ | Haalt de pariteitsgegevens van de QR gestructureerde append-modus op. Standaardwaarde is -1. Waarde: De index van de QR gestructureerde append-modus ba |
| [getQRVersion()](#getqrversion) ~~(deprecated)~~ | Versie van herkende QR-code. Van Version1 tot Version40. |
| [getRectMicroQRVersion()](#getrectmicroqrversion) | Versie van herkende RectMicroQR-code. Van R7x43 tot R17x139. |
| [getStructuredAppendModeBarCodeIndex()](#getstructuredappendmodebarcodeindex) | Haalt de index op van de QR gestructureerde append-modus barcode. Index begint bij 0. Standaardwaarde is -1. Waarde: De hoeveelheid o |
| [getStructuredAppendModeBarCodesQuantity()](#getstructuredappendmodebarcodesquantity) | Haalt de hoeveelheid QR gestructureerde append-modus barcodes op. Standaardwaarde is -1. Waarde: De hoeveelheid van de QR gestructureerde appe |
| [getStructuredAppendModeParityData()](#getstructuredappendmodeparitydata) | Haalt de pariteitsgegevens van de QR gestructureerde append-modus op. Standaardwaarde is -1. Waarde: De index van de QR gestructureerde append-modus b |
| [getVersion()](#getversion) | Versie van herkende QR-code. Van Version1 tot Version40. |
| [hashCode()](#hashcode) | Retourneert de hashcode voor deze instantie. |
| [isEmpty()](#isempty) | Test of alle parameters alleen standaardwaarden hebben Waarde |
| [toString()](#tostring) | Retourneert een menselijk leesbare tekenreeksrepresentatie van dit QRExtendedParameters. |

### equals(obj) {#equals}

Retourneert een waarde die aangeeft of dit exemplaar gelijk is aan een opgegeven QRExtendedParameters-waarde.

| Parameter | Beschrijving |
| --- | --- |
| obj | Een objectwaarde om te vergelijken met dit exemplaar. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getErrorLevel() {#geterrorlevel}

Reed-Solomon-foutcorrectieniveau van herkende barcode. Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH.

### getMicroQRVersion() {#getmicroqrversion}

Versie van herkende MicroQR-code. Van M1 tot M4.

**Returns:** Version of recognized MicroQR Code. From M1 to M4.

### getQRErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Reed-Solomon-foutcorrectieniveau van herkende barcode. Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH.

**Returns:** Reed-Solomon error correction level of recognized barcode.

### getQRStructuredAppendModeBarCodeIndex() {#getqrstructuredappendmodebarcodeindex}

> **Deprecated.** See method description for replacement.

Haalt de index op van de QR structured append mode barcode. Index begint bij 0. Standaardwaarde is -1. Waarde: De hoeveelheid van de QR structured append mode barcode.

### getQRStructuredAppendModeBarCodesQuantity() {#getqrstructuredappendmodebarcodesquantity}

> **Deprecated.** See method description for replacement.

Haalt de hoeveelheid QR structured append mode barcodes op. Standaardwaarde is -1. Waarde: De hoeveelheid van de QR structured append mode barcode.

### getQRStructuredAppendModeParityData() {#getqrstructuredappendmodeparitydata}

> **Deprecated.** See method description for replacement.

Haalt de pariteitsgegevens van de QR structured append mode op. Standaardwaarde is -1. Waarde: De index van de QR structured append mode barcode.

### getQRVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Versie van herkende QR-code. Van Version1 tot Version40.

**Returns:** Version of recognized QR Code

### getRectMicroQRVersion() {#getrectmicroqrversion}

Versie van herkende RectMicroQR-code. Van R7x43 tot R17x139.

**Returns:** Version of recognized RectMicroQR Code

### getStructuredAppendModeBarCodeIndex() {#getstructuredappendmodebarcodeindex}

Haalt de index op van de QR structured append mode barcode. Index begint bij 0. Standaardwaarde is -1. Waarde: De hoeveelheid van de QR structured append mode barcode.

**Returns:** the index of the QR structured append mode barcode.

### getStructuredAppendModeBarCodesQuantity() {#getstructuredappendmodebarcodesquantity}

Haalt de hoeveelheid QR structured append mode barcodes op. Standaardwaarde is -1. Waarde: De hoeveelheid van de QR structured append mode barcode.

**Returns:** the QR structured append mode barcodes quantity.

### getStructuredAppendModeParityData() {#getstructuredappendmodeparitydata}

Haalt de pariteitsgegevens van de QR structured append mode op. Standaardwaarde is -1. Waarde: De index van de QR structured append mode barcode.

**Returns:** the QR structured append mode parity data.

### getVersion() {#getversion}

Versie van herkende QR-code. Van Version1 tot Version40.

### hashCode() {#hashcode}

Retourneert de hashcode voor deze instantie.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Test of alle parameters alleen standaardwaarden hebben Waarde

**Returns:** true if all parameters has only default values; otherwise, `false `.

### toString() {#tostring}

Retourneert een menselijk leesbare tekenreeksrepresentatie van dit QRExtendedParameters.

**Returns:** A string that represents this QRExtendedParameters.
