---
title: "DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Slaat speciale gegevens van de herkende DataMatrix-barcode op Deze voorbeeld laat zien hoe je ruwe DataMatrix-waarden krijgt let generator = new BarcodeGenerator(EncodeTypes.DATA_MA"
type: docs
weight: 350
url: /nl/nodejs/aspose.barcode/datamatrixextendedparameters/
---

## DataMatrixExtendedParameters class

Slaat speciale gegevens van de herkende DataMatrix-barcode op Deze voorbeeld laat zien hoe je ruwe DataMatrix-waarden krijgt let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345")) generator.save("test.png", BarcodeImageFormat.PNG); let reader = new BarCodeReader("test.png", null, DecodeType.DATA_MATRIX)) let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode type: " + result.getCodeTypeName()); console.log("BarCode codetext: " + result.getCodeText()); console.log("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId()); console.log("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount()); console.log("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId()); console.log("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming()); }

```js
new DataMatrixExtendedParameters()
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [equals(obj)](#equals) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `DataMatrixExtendedParameters`-waarde. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Haalt de ID op van de DataMatrix structured append-modusbarcode. ID begint bij 1 en moet kleiner of gelijk zijn aan barcodes cou |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Haalt het aantal barcodes van de DataMatrix structured append-modus op. Standaardwaarde is -1. Aantal moet een waarde zijn van 1 tot 35. Valu |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Haalt de ID op van de DataMatrix structured append-modusbarcode. ID begint bij 1 en moet kleiner of gelijk zijn aan barcodes cou |
| [hashCode()](#hashcode) | Retourneert de hashcode voor deze instantie. |
| [isReaderProgramming()](#isreaderprogramming) | Geeft aan of code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of |
| [toString()](#tostring) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze `DataMatrixExtendedParameters`. |

### equals(obj) {#equals}

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `DataMatrixExtendedParameters`-waarde.

| Parameter | Beschrijving |
| --- | --- |
| obj | Een System.Object-waarde om te vergelijken met deze instantie. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Haalt de ID op van de DataMatrix structured append-modusbarcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1. Waarde: De ID van de DataMatrix structured append-modusbarcode.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Haalt het aantal DataMatrix gestructureerde append-modus barcodes op. Standaardwaarde is -1. Het aantal moet een waarde zijn van 1 tot 35. Waarde: Het aantal van de DataMatrix gestructureerde append-modus barcode.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Haalt de ID op van de DataMatrix structured append-modusbarcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1. Waarde: De ID van de DataMatrix structured append-modusbarcode.

### hashCode() {#hashcode}

Retourneert de hashcode voor deze instantie.

**Returns:** A 32-bit signed integer hash code.

### isReaderProgramming() {#isreaderprogramming}

Geeft aan of code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false.

### toString() {#tostring}

Retourneert een menselijk leesbare tekenreeksrepresentatie van deze `DataMatrixExtendedParameters`.

**Returns:** A string that represents this `DataMatrixExtendedParameters`.
