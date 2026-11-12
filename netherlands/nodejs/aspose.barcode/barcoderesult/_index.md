---
title: "BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Slaat herkende barcodegegevens op, zoals SingleDecodeType type, `string` codetext, BarCodeRegionParameters regio en andere parameters"
type: docs
weight: 110
url: /nl/nodejs/aspose.barcode/barcoderesult/
---

## BarCodeResult class

Slaat herkende barcodegegevens op, zoals SingleDecodeType type, `string` codetext, BarCodeRegionParameters regio en andere parameters

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

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [deepClone()](#deepclone) | Maakt een kopie van de BarCodeResult-klasse. |
| [equals(other)](#equals) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven BarCodeResult-waarde. |
| [getCodeBytes()](#getcodebytes) | Haalt de gecodeerde codebytes op Waarde: De codebytes van de barcode |
| [getCodeText(encoding)](#getcodetext) | Haalt de code-tekst op met codering. Dit voorbeeld laat zien hoe `getCodeText` te gebruiken: let gen = new BarcodeGenerator(EncodeType |
| [getCodeType()](#getcodetype) | Haalt het barcode-type op Waarde: De type-informatie van de herkende barcode |
| [getCodeTypeName()](#getcodetypename) | Haalt de naam van het barcode-type op Waarde: De typenaam van de herkende barcode |
| [getConfidence()](#getconfidence) | Haalt het herkenningsvertrouwensniveau van de herkende barcode op Waarde: BarCodeConfidence.Strong heeft geen neppe of foutieve herkenning |
| [getExtended()](#getextended) | Haalt uitgebreide parameters van de herkende barcode op Waarde: De uitgebreide parameters van de herkende barcode |
| [getReadingQuality()](#getreadingquality) | Haalt de leeskwaliteit op. Werkt voor 1D- en postbarcode. Waarde: Het leeskwaliteitpercentage |
| [getRegion()](#getregion) | Haalt de barcode-regio op Waarde: De regio van de herkende barcode |
| [hashCode()](#hashcode) | Retourneert de hashcode voor deze instantie. |
| [toString()](#tostring) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze BarCodeResult. |

### deepClone() {#deepclone}

Maakt een kopie van de BarCodeResult-klasse.

**Returns:** Returns copy of BarCodeResult class.

### equals(other) {#equals}

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven BarCodeResult-waarde.

| Parameter | Beschrijving |
| --- | --- |
| overig | Een BarCodeResult-waarde om te vergelijken met deze instantie. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCodeBytes() {#getcodebytes}

Haalt de gecodeerde codebytes op Waarde: De codebytes van de barcode

### getCodeText(encoding) {#getcodetext}

Haalt de code-tekst op met codering. Dit voorbeeld laat zien hoe `getCodeText` te gebruiken: let gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null); gen.setCodeText("車種名", "932"); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.DATA_MATRIX); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText("932")); }

| Parameter | Beschrijving |
| --- | --- |
| codering | De codering voor codetext. |

**Returns:** A string containing recognized code text.

### getCodeType() {#getcodetype}

Haalt het barcode-type op Waarde: De type-informatie van de herkende barcode

### getCodeTypeName() {#getcodetypename}

Haalt de naam van het barcode-type op Waarde: De typenaam van de herkende barcode

### getConfidence() {#getconfidence}

Haalt het herkenningsvertrouwensniveau van de herkende barcode op Waarde: BarCodeConfidence.Strong heeft geen neppe of foutieve herkenningen, BarCodeConfidence.Moderate kan soms neppe of onjuiste codetext hebben omdat dit vertrouwensniveau geldt voor barcodes met een zwakke controle som of zelfs zonder, BarCodeConfidence.NONE heeft altijd onjuiste codetext en kan neppe herkenningen bevatten

### getExtended() {#getextended}

Haalt uitgebreide parameters van de herkende barcode op Waarde: De uitgebreide parameters van de herkende barcode

### getReadingQuality() {#getreadingquality}

Haalt de leeskwaliteit op. Werkt voor 1D- en postbarcode. Waarde: Het leeskwaliteitpercentage

### getRegion() {#getregion}

Haalt de barcode-regio op Waarde: De regio van de herkende barcode

### hashCode() {#hashcode}

Retourneert de hashcode voor deze instantie.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Retourneert een menselijk leesbare tekenreeksrepresentatie van deze BarCodeResult.

**Returns:** A string that represents this BarCodeResult.
