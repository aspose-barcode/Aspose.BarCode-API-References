---
title: "HIBCLICPrimaryDataCodetext"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Classe pour l'encodage et le décodage du texte intégré dans le code HIBC LIC qui stocke les données primaires."
type: docs
weight: 460
url: /fr/nodejs/aspose.barcode/hibclicprimarydatacodetext/
---

## HIBCLICPrimaryDataCodetext class

Classe pour l'encodage et le décodage du texte intégré dans le code HIBC LIC qui stocke les données primaires. Cet exemple montre comment encoder et décoder HIBC LIC en utilisant HIBCLICPrimaryCodetext.

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

## Méthodes

| Nom | Description |
| --- | --- |
| [equals(obj)](#equals) | Renvoie une valeur indiquant si cette instance est égale à une valeur `HIBCLICPrimaryDataCodetext` spécifiée. |
| [getConstructedCodetext()](#getconstructedcodetext) | Construit le codetext |
| [getData()](#getdata) | Identifie les données primaires. |
| [hashCode()](#hashcode) | Renvoie le code de hachage pour cette instance. |
| [initFromString(constructedCodetext)](#initfromstring) | Initialise l'instance à partir du codetext construit. |
| [setData()](#setdata) | Identifie les données primaires. |

### equals(obj) {#equals}

Renvoie une valeur indiquant si cette instance est égale à une valeur `HIBCLICPrimaryDataCodetext` spécifiée.

| Paramètre | Description |
| --- | --- |
| obj | Une valeur `HIBCLICPrimaryDataCodetext` à comparer à cette instance. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Construit le codetext

**Returns:** Constructed codetext

### getData() {#getdata}

Identifie les données primaires.

### hashCode() {#hashcode}

Renvoie le code de hachage pour cette instance.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Initialise l'instance à partir du codetext construit.

| Paramètre | Description |
| --- | --- |
| constructedCodetext | Codetext construit. |

### setData() {#setdata}

Identifie les données primaires.
