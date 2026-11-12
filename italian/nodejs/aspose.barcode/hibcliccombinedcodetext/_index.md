---
title: "HIBCLICCombinedCodetext"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Classe per la codifica e decodifica del testo incorporato nel codice HIBC LIC che memorizza i dati primari e secondari."
type: docs
weight: 440
url: /it/nodejs/aspose.barcode/hibcliccombinedcodetext/
---

## HIBCLICCombinedCodetext class

Classe per la codifica e decodifica del testo incorporato nel codice HIBC LIC che memorizza i dati primari e secondari. Questo esempio mostra come codificare e decodificare HIBC LIC usando HIBCLICCombinedCodetext.

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [equals(obj)](#equals) | Restituisce un valore che indica se questa istanza è uguale a un valore `HIBCLICCombinedCodetext` specificato. |
| [getConstructedCodetext()](#getconstructedcodetext) | Costruisce il codetext |
| [getPrimaryData()](#getprimarydata) | Identifica i dati primari. |
| [getSecondaryAndAdditionalData()](#getsecondaryandadditionaldata) | Identifica i dati secondari e supplementari aggiuntivi. |
| [hashCode()](#hashcode) | Restituisce il codice hash per questa istanza. |
| [initFromString(constructedCodetext)](#initfromstring) | Inizializza l'istanza dal codetext costruito. |
| [setPrimaryData()](#setprimarydata) | Identifica i dati primari. |
| [setSecondaryAndAdditionalData()](#setsecondaryandadditionaldata) | Identifica i dati secondari e supplementari aggiuntivi. |

### equals(obj) {#equals}

Restituisce un valore che indica se questa istanza è uguale a un valore `HIBCLICCombinedCodetext` specificato.

| Parametro | Descrizione |
| --- | --- |
| obj | Un valore `HIBCLICCombinedCodetext` da confrontare con questa istanza. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Costruisce il codetext

**Returns:** Constructed codetext

### getPrimaryData() {#getprimarydata}

Identifica i dati primari.

### getSecondaryAndAdditionalData() {#getsecondaryandadditionaldata}

Identifica i dati secondari e supplementari aggiuntivi.

### hashCode() {#hashcode}

Restituisce il codice hash per questa istanza.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Inizializza l'istanza dal codetext costruito.

| Parametro | Descrizione |
| --- | --- |
| constructedCodetext | Codetext costruito. |

### setPrimaryData() {#setprimarydata}

Identifica i dati primari.

### setSecondaryAndAdditionalData() {#setsecondaryandadditionaldata}

Identifica i dati secondari e supplementari aggiuntivi.
