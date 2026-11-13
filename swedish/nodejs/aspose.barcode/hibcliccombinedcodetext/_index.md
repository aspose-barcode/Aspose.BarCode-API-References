---
title: "HIBCLICCombinedCodetext"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Klass för kodning och avkodning av texten inbäddad i HIBC LIC-koden som lagrar primär och sekundär data."
type: docs
weight: 440
url: /sv/nodejs/aspose.barcode/hibcliccombinedcodetext/
---

## HIBCLICCombinedCodetext class

Klass för kodning och avkodning av texten inbäddad i HIBC LIC-koden som lagrar primär och sekundär data. Detta exempel visar hur man kodar och avkodar HIBC LIC med hjälp av HIBCLICCombinedCodetext.

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals(obj)](#equals) | Returnerar ett värde som indikerar om detta objekt är lika med ett angivet `HIBCLICCombinedCodetext`-värde. |
| [getConstructedCodetext()](#getconstructedcodetext) | Skapar kodtext |
| [getPrimaryData()](#getprimarydata) | Identifierar primär data. |
| [getSecondaryAndAdditionalData()](#getsecondaryandadditionaldata) | Identifierar sekundär och ytterligare kompletterande data. |
| [hashCode()](#hashcode) | Returnerar hashkoden för detta objekt. |
| [initFromString(constructedCodetext)](#initfromstring) | Initierar objektet från konstruerad kodtext. |
| [setPrimaryData()](#setprimarydata) | Identifierar primär data. |
| [setSecondaryAndAdditionalData()](#setsecondaryandadditionaldata) | Identifierar sekundär och ytterligare kompletterande data. |

### equals(obj) {#equals}

Returnerar ett värde som indikerar om detta objekt är lika med ett angivet `HIBCLICCombinedCodetext`-värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | Ett `HIBCLICCombinedCodetext`-värde att jämföra med detta objekt. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Skapar kodtext

**Returns:** Constructed codetext

### getPrimaryData() {#getprimarydata}

Identifierar primär data.

### getSecondaryAndAdditionalData() {#getsecondaryandadditionaldata}

Identifierar sekundär och ytterligare kompletterande data.

### hashCode() {#hashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Initierar objektet från konstruerad kodtext.

| Parameter | Beskrivning |
| --- | --- |
| constructedCodetext | Konstruerad kodtext. |

### setPrimaryData() {#setprimarydata}

Identifierar primär data.

### setSecondaryAndAdditionalData() {#setsecondaryandadditionaldata}

Identifierar sekundär och ytterligare kompletterande data.
