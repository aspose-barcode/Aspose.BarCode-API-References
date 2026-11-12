---
title: "HIBCLICPrimaryDataCodetext"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC LIC-code die primaire gegevens opslaat."
type: docs
weight: 460
url: /nl/nodejs/aspose.barcode/hibclicprimarydatacodetext/
---

## HIBCLICPrimaryDataCodetext class

Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC LIC-code die primaire gegevens opslaat. Dit voorbeeld toont hoe HIBC LIC te coderen en decoderen met behulp van HIBCLICPrimaryCodetext.

```js
new HIBCLICPrimaryDataCodetext()
```

**Example:**

```js
let complexCodetext  = new HIBCLICPrimaryCodetext();
complexCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
complexCodetext.setData(new PrimaryData());
complexCodetext.getData().setProductOrCatalogNumber("12345");
complexCodetext.getData().setLabelerIdentificationCode("A999");
complexCodetext.getData().setUnitOfMeasureID(1);
let generator = new ComplexBarcodeGenerator(complexCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getData().getUnitOfMeasureID());
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [equals(obj)](#equals) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `HIBCLICPrimaryDataCodetext`-waarde. |
| [getConstructedCodetext()](#getconstructedcodetext) | Construeert codetext |
| [getData()](#getdata) | Identificeert primaire gegevens. |
| [hashCode()](#hashcode) | Retourneert de hashcode voor deze instantie. |
| [initFromString(constructedCodetext)](#initfromstring) | Initialiseert instantie vanuit geconstrueerde codetext. |
| [setData()](#setdata) | Identificeert primaire gegevens. |

### equals(obj) {#equals}

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `HIBCLICPrimaryDataCodetext`-waarde.

| Parameter | Beschrijving |
| --- | --- |
| obj | Een `HIBCLICPrimaryDataCodetext`-waarde om te vergelijken met deze instantie. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Construeert codetext

**Returns:** Constructed codetext

### getData() {#getdata}

Identificeert primaire gegevens.

### hashCode() {#hashcode}

Retourneert de hashcode voor deze instantie.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Initialiseert instantie vanuit geconstrueerde codetext.

| Parameter | Beschrijving |
| --- | --- |
| constructedCodetext | Geconstrueerde codetext. |

### setData() {#setdata}

Identificeert primaire gegevens.
