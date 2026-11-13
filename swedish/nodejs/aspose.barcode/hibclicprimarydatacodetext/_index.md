---
title: "HIBCLICPrimaryDataCodetext"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Klass för kodning och avkodning av texten som är inbäddad i HIBC LIC-koden som lagrar primärdata."
type: docs
weight: 460
url: /sv/nodejs/aspose.barcode/hibclicprimarydatacodetext/
---

## HIBCLICPrimaryDataCodetext class

Klass för kodning och avkodning av texten som är inbäddad i HIBC LIC-koden som lagrar primärdata. Detta exempel visar hur man kodar och avkodar HIBC LIC med hjälp av HIBCLICPrimaryCodetext.

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals(obj)](#equals) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `HIBCLICPrimaryDataCodetext`-värde. |
| [getConstructedCodetext()](#getconstructedcodetext) | Skapar kodtext |
| [getData()](#getdata) | Identifierar primär data. |
| [hashCode()](#hashcode) | Returnerar hashkoden för detta objekt. |
| [initFromString(constructedCodetext)](#initfromstring) | Initierar objektet från konstruerad kodtext. |
| [setData()](#setdata) | Identifierar primär data. |

### equals(obj) {#equals}

Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `HIBCLICPrimaryDataCodetext`-värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | Ett `HIBCLICPrimaryDataCodetext`-värde att jämföra med detta objekt. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Skapar kodtext

**Returns:** Constructed codetext

### getData() {#getdata}

Identifierar primär data.

### hashCode() {#hashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Initierar objektet från konstruerad kodtext.

| Parameter | Beskrivning |
| --- | --- |
| constructedCodetext | Konstruerad kodtext. |

### setData() {#setdata}

Identifierar primär data.
