---
title: "HIBCLICCombinedCodetext"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC LIC‑code die primaire en secundaire gegevens opslaat."
type: docs
weight: 440
url: /nl/nodejs/aspose.barcode/hibcliccombinedcodetext/
---

## HIBCLICCombinedCodetext class

Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC LIC‑code die primaire en secundaire gegevens opslaat. Deze voorbeeld toont hoe HIBC LIC te coderen en decoderen met behulp van HIBCLICCombinedCodetext.

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

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [equals(obj)](#equals) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `HIBCLICCombinedCodetext`‑waarde. |
| [getConstructedCodetext()](#getconstructedcodetext) | Construeert codetext |
| [getPrimaryData()](#getprimarydata) | Identificeert primaire gegevens. |
| [getSecondaryAndAdditionalData()](#getsecondaryandadditionaldata) | Identificeert secundaire en aanvullende gegevens. |
| [hashCode()](#hashcode) | Retourneert de hashcode voor deze instantie. |
| [initFromString(constructedCodetext)](#initfromstring) | Initialiseert instantie vanuit geconstrueerde codetext. |
| [setPrimaryData()](#setprimarydata) | Identificeert primaire gegevens. |
| [setSecondaryAndAdditionalData()](#setsecondaryandadditionaldata) | Identificeert secundaire en aanvullende gegevens. |

### equals(obj) {#equals}

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `HIBCLICCombinedCodetext`‑waarde.

| Parameter | Beschrijving |
| --- | --- |
| obj | Een `HIBCLICCombinedCodetext`‑waarde om te vergelijken met deze instantie. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Construeert codetext

**Returns:** Constructed codetext

### getPrimaryData() {#getprimarydata}

Identificeert primaire gegevens.

### getSecondaryAndAdditionalData() {#getsecondaryandadditionaldata}

Identificeert secundaire en aanvullende gegevens.

### hashCode() {#hashcode}

Retourneert de hashcode voor deze instantie.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Initialiseert instantie vanuit geconstrueerde codetext.

| Parameter | Beschrijving |
| --- | --- |
| constructedCodetext | Geconstrueerde codetext. |

### setPrimaryData() {#setprimarydata}

Identificeert primaire gegevens.

### setSecondaryAndAdditionalData() {#setsecondaryandadditionaldata}

Identificeert secundaire en aanvullende gegevens.
