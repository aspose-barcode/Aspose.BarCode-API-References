---
title: "HIBCLICCombinedCodetext"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Classe permettant d'encoder et de décoder le texte intégré dans le code HIBC LIC qui stocke les données primaires et secondaires."
type: docs
weight: 440
url: /fr/nodejs/aspose.barcode/hibcliccombinedcodetext/
---

## HIBCLICCombinedCodetext class

Classe permettant d'encoder et de décoder le texte intégré dans le code HIBC LIC qui stocke les données primaires et secondaires. Cet exemple montre comment encoder et décoder le HIBC LIC en utilisant HIBCLICCombinedCodetext.

```js
new HIBCLICCombinedCodetext()
```

**Example:**

```js
let combinedCodetext = new HIBCLICCombinedCodetext();
combinedCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
combinedCodetext.setPrimaryData(new PrimaryData());
combinedCodetext.getPrimaryData().setProductOrCatalogNumber("12345");
combinedCodetext.getPrimaryData().setLabelerIdentificationCode("A999");
combinedCodetext.getPrimaryData().setUnitOfMeasureID(1);
combinedCodetext.setSecondaryAndAdditionalData(new SecondaryAndAdditionalData());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDate(new Date());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDateFormat(HIBCLICDateFormat.MMDDYY);
combinedCodetext.getSecondaryAndAdditionalData().setQuantity(30);
combinedCodetext.getSecondaryAndAdditionalData().setLotNumber("LOT123");
combinedCodetext.getSecondaryAndAdditionalData().setSerialNumber("SERIAL123");
combinedCodetext.getSecondaryAndAdditionalData().setDateOfManufacture(new Date());
ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getPrimaryData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getPrimaryData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getPrimaryData().getUnitOfMeasureID());
print("Expiry date: " + result.getSecondaryAndAdditionalData().getExpiryDate());
print("Quantity: " + result.getSecondaryAndAdditionalData().getQuantity());
print("Lot number: " + result.getSecondaryAndAdditionalData().getLotNumber());
print("Serial number: " + result.getSecondaryAndAdditionalData().getSerialNumber());
print("Date of manufacture: " + result.getSecondaryAndAdditionalData().getDateOfManufacture());
```

## Méthodes

| Nom | Description |
| --- | --- |
| [equals(obj)](#equals) | Renvoie une valeur indiquant si cette instance est égale à une valeur `HIBCLICCombinedCodetext` spécifiée. |
| [getConstructedCodetext()](#getconstructedcodetext) | Construit le codetext |
| [getPrimaryData()](#getprimarydata) | Identifie les données primaires. |
| [getSecondaryAndAdditionalData()](#getsecondaryandadditionaldata) | Identifie les données secondaires et supplémentaires. |
| [hashCode()](#hashcode) | Renvoie le code de hachage pour cette instance. |
| [initFromString(constructedCodetext)](#initfromstring) | Initialise l'instance à partir du codetext construit. |
| [setPrimaryData()](#setprimarydata) | Identifie les données primaires. |
| [setSecondaryAndAdditionalData()](#setsecondaryandadditionaldata) | Identifie les données secondaires et supplémentaires. |

### equals(obj) {#equals}

Renvoie une valeur indiquant si cette instance est égale à une valeur `HIBCLICCombinedCodetext` spécifiée.

| Paramètre | Description |
| --- | --- |
| obj | Une valeur `HIBCLICCombinedCodetext` à comparer à cette instance. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Construit le codetext

**Returns:** Constructed codetext

### getPrimaryData() {#getprimarydata}

Identifie les données primaires.

### getSecondaryAndAdditionalData() {#getsecondaryandadditionaldata}

Identifie les données secondaires et supplémentaires.

### hashCode() {#hashcode}

Renvoie le code de hachage pour cette instance.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Initialise l'instance à partir du codetext construit.

| Paramètre | Description |
| --- | --- |
| constructedCodetext | Codetext construit. |

### setPrimaryData() {#setprimarydata}

Identifie les données primaires.

### setSecondaryAndAdditionalData() {#setsecondaryandadditionaldata}

Identifie les données secondaires et supplémentaires.
