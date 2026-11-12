---
title: "DotCodeExtendedParameters"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Slaat speciale gegevens van herkende DotCode-barcode op. Deze voorbeeld toont hoe je ruwe DotCode-waarden krijgt"
type: docs
weight: 380
url: /nl/nodejs/aspose.barcode/dotcodeextendedparameters/
---

## DotCodeExtendedParameters class

Slaat speciale gegevens van herkende DotCode-barcode op. Deze voorbeeld toont hoe je ruwe DotCode-waarden krijgt

```js
new DotCodeExtendedParameters()
```

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
generator.save("test.png", BarCodeImageFormat.PNG);

let reader = new BarCodeReader("test.png", null, DecodeType.DOT_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    print("BarCode type: " + result.getCodeTypeName());
    print("BarCode codetext: " + result.getCodeText());
    print("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
    print("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
}
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [equals(obj)](#equals) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `DotCodeExtendedParameters`-waarde. |
| [getDotCodeIsReaderInitialization()](#getdotcodeisreaderinitialization) ~~(deprecated)~~ | Geeft aan of code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | Haalt de ID op van de DotCode gestructureerde append-modus barcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | Haalt het aantal barcodes op van de DotCode gestructureerde append-modus. Standaardwaarde is -1. Aantal moet een waarde zijn van 1 tot 35. Waarde: |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Haalt de ID op van de DotCode gestructureerde append-modus barcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | Haalt het aantal barcodes op van de DotCode gestructureerde append-modus. Standaardwaarde is -1. Aantal moet een waarde zijn van 1 tot 35. Waarde: |
| [hashCode()](#hashcode) | Retourneert de hashcode voor deze instantie. |
| [isReaderInitialization()](#isreaderinitialization) | Geeft aan of code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of |
| [toString()](#tostring) | Retourneert een menselijk leesbare stringrepresentatie van deze `DotCodeExtendedParameters`. |

### equals(obj) {#equals}

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `DotCodeExtendedParameters`-waarde.

| Parameter | Beschrijving |
| --- | --- |
| obj | Een System.Object-waarde om te vergelijken met deze instantie. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDotCodeIsReaderInitialization() {#getdotcodeisreaderinitialization}

> **Deprecated.** See method description for replacement.

Geeft aan of code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

Haalt de ID op van de DotCode gestructureerde append-modus barcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1. Waarde: De ID van de DotCode gestructureerde append-modus barcode.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

Haalt het aantal barcodes op van de DotCode gestructureerde append-modus. Standaardwaarde is -1. Aantal moet een waarde zijn van 1 tot 35. Waarde: Het aantal van de DotCode gestructureerde append-modus barcode.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Haalt de ID op van de DotCode gestructureerde append-modus barcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1. Waarde: De ID van de DotCode gestructureerde append-modus barcode.

**Returns:** the ID of the DotCode structured append mode barcode.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

Haalt het aantal barcodes op van de DotCode gestructureerde append-modus. Standaardwaarde is -1. Aantal moet een waarde zijn van 1 tot 35. Waarde: Het aantal van de DotCode gestructureerde append-modus barcode.

**Returns:** the DotCode structured append mode barcodes count.

### hashCode() {#hashcode}

Retourneert de hashcode voor deze instantie.

**Returns:** A 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Geeft aan of code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false.

### toString() {#tostring}

Retourneert een menselijk leesbare stringrepresentatie van deze `DotCodeExtendedParameters`.

**Returns:** A string that represents this `DotCodeExtendedParameters`.
