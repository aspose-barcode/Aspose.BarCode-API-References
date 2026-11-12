---
title: "AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Slaat speciale gegevens op van een door Aztec herkende barcode. Dit voorbeeld toont hoe je Aztec-ruwe waarden krijgt let generator = new BarcodeGenerator(EncodeTypes.AZTEC, \"12345\"); "
type: docs
weight: 60
url: /nl/nodejs/aspose.barcode/aztecextendedparameters/
---

## AztecExtendedParameters class

Slaat speciale gegevens op van een door Aztec herkende barcode. Dit voorbeeld toont hoe je Aztec-ruwe waarden krijgt let generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345"); generator.save("test.png", BarcodeImageFormat.PNG);

```js
new AztecExtendedParameters()
```

**Example:**

```js
BarCodeReader reader = new BarCodeReader("test.png", null, DecodeType.AZTEC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode type: " + result.getCodeTypeName());
    console.log("BarCode codetext: " + result.getCodeText());
    console.log("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
    console.log("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
    console.log("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
    console.log("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
}
</pre>
</pre></blockquote></hr></p>
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [equals(obj)](#equals) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `AztecExtendedParameters`-waarde. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Haalt de ID op van de Aztec gestructureerde append-modus barcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. D |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Haalt het aantal barcodes op van de Aztec gestructureerde append-modus. Standaardwaarde is 0. Aantal moet een waarde tussen 1 en 26 zijn. Waarde: The |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Haalt de bestands-ID op van de Aztec gestructureerde append-modus. Standaardwaarde is een lege tekenreeks. Waarde: The File ID of the Aztec stru |
| [hashCode()](#hashcode) | Retourneert de hashcode voor deze instantie. |
| [isReaderInitialization()](#isreaderinitialization) | Geeft aan of code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of |
| [toString()](#tostring) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze `AztecExtendedParameters`. |

### equals(obj) {#equals}

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `AztecExtendedParameters`-waarde.

| Parameter | Beschrijving |
| --- | --- |
| obj | Een System.Object-waarde om te vergelijken met deze instantie. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Haalt de ID op van de Aztec gestructureerde append-modus barcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is 0. Waarde: De barcode-ID van de Aztec gestructureerde append-modus.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Haalt het aantal barcodes op van de Aztec gestructureerde append-modus. Standaardwaarde is 0. Aantal moet een waarde tussen 1 en 26 zijn. Waarde: Het aantal barcodes van de Aztec gestructureerde append-modus.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Haalt de bestands-ID op van de Aztec gestructureerde append-modus. Standaardwaarde is een lege tekenreeks. Waarde: De bestands-ID van de Aztec gestructureerde append-modus.

### hashCode() {#hashcode}

Retourneert de hashcode voor deze instantie.

**Returns:** 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Geeft aan of code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false.

### toString() {#tostring}

Retourneert een menselijk leesbare tekenreeksrepresentatie van deze `AztecExtendedParameters`.

**Returns:** A string that represents this `AztecExtendedParameters`.
