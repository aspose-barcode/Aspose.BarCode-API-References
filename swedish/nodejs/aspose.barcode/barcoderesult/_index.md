---
title: "BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Lagrar igenkända streckkoddata såsom SingleDecodeType-typ, `string` codetext, BarCodeRegionParameters region och andra parametrar."
type: docs
weight: 110
url: /sv/nodejs/aspose.barcode/barcoderesult/
---

## BarCodeResult class

Lagrar igenkända streckkoddata såsom SingleDecodeType-typ, `string` codetext, BarCodeRegionParameters region och andra parametrar.

```js
new BarCodeResult()
```

**Example:**

```js
//This sample shows how to obtain BarCodeResult.
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("BarCode Confidence: " + result.getConfidence());
    console.log("BarCode ReadingQuality: " + result.getReadingQuality());
    console.log("BarCode Angle: " + result.getRegion().getAngle());
}
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [deepClone()](#deepclone) | Skapar en kopia av klassen BarCodeResult. |
| [equals(other)](#equals) | Returnerar ett värde som indikerar om detta objekt är lika med ett angivet BarCodeResult-värde. |
| [getCodeBytes()](#getcodebytes) | Hämtar de kodade kodbytena. Värde: Kodbytena för streckkoden. |
| [getCodeText(encoding)](#getcodetext) | Hämtar kodtexten med kodning. Detta exempel visar hur man använder `getCodeText`: let gen = new BarcodeGenerator(EncodeType |
| [getCodeType()](#getcodetype) | Hämtar streckkodstypen. Värde: Typinformationen för den igenkända streckkoden. |
| [getCodeTypeName()](#getcodetypename) | Hämtar namnet på streckkodstypen. Värde: Typnamnet för den igenkända streckkoden. |
| [getConfidence()](#getconfidence) | Hämtar igenkänningskonfidensnivån för den igenkända streckkoden. Värde: BarCodeConfidence.Strong har inga falska eller felaktiga... |
| [getExtended()](#getextended) | Hämtar utökade parametrar för den igenkända streckkoden. Värde: De utökade parametrarna för den igenkända streckkoden. |
| [getReadingQuality()](#getreadingquality) | Hämtar läskvaliteten. Fungerar för 1D- och poststreckkoder. Värde: Läsningskvalitet i procent. |
| [getRegion()](#getregion) | Hämtar streckkodsområdet. Värde: Området för den igenkända streckkoden. |
| [hashCode()](#hashcode) | Returnerar hashkoden för detta objekt. |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av detta BarCodeResult. |

### deepClone() {#deepclone}

Skapar en kopia av klassen BarCodeResult.

**Returns:** Returns copy of BarCodeResult class.

### equals(other) {#equals}

Returnerar ett värde som indikerar om detta objekt är lika med ett angivet BarCodeResult-värde.

| Parameter | Beskrivning |
| --- | --- |
| annat | Ett BarCodeResult-värde att jämföra med detta objekt. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCodeBytes() {#getcodebytes}

Hämtar de kodade kodbytena. Värde: Kodbytena för streckkoden.

### getCodeText(encoding) {#getcodetext}

Hämtar kodtexten med kodning. Detta exempel visar hur man använder `getCodeText`: let gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null); gen.setCodeText("車種名", "932"); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.DATA_MATRIX); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText("932")); }

| Parameter | Beskrivning |
| --- | --- |
| kodning | Kodningen för codetext. |

**Returns:** A string containing recognized code text.

### getCodeType() {#getcodetype}

Hämtar streckkodstypen. Värde: Typinformationen för den igenkända streckkoden.

### getCodeTypeName() {#getcodetypename}

Hämtar namnet på streckkodstypen. Värde: Typnamnet för den igenkända streckkoden.

### getConfidence() {#getconfidence}

Hämtar igenkänningskonfidensnivån för den igenkända streckkoden. Värde: BarCodeConfidence.Strong har inga falska eller felaktiga igenkänningar, BarCodeConfidence.Moderate kan ibland ha falska eller felaktiga codetext eftersom denna konfidensnivå gäller streckkoder med svag kontrollsumma eller utan, BarCodeConfidence.NONE har alltid felaktig codetext och kan vara falska igenkänningar.

### getExtended() {#getextended}

Hämtar utökade parametrar för den igenkända streckkoden. Värde: De utökade parametrarna för den igenkända streckkoden.

### getReadingQuality() {#getreadingquality}

Hämtar läskvaliteten. Fungerar för 1D- och poststreckkoder. Värde: Läsningskvalitet i procent.

### getRegion() {#getregion}

Hämtar streckkodsområdet. Värde: Området för den igenkända streckkoden.

### hashCode() {#hashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av detta BarCodeResult.

**Returns:** A string that represents this BarCodeResult.
