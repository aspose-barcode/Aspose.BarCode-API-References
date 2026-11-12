---
title: "HIBCLICCombinedCodetext"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Klasse zum Kodieren und Dekodieren des in den HIBC‑LIC‑Code eingebetteten Textes, der primäre und sekundäre Daten speichert."
type: docs
weight: 440
url: /de/nodejs/aspose.barcode/hibcliccombinedcodetext/
---

## HIBCLICCombinedCodetext class

Klasse zum Kodieren und Dekodieren des in den HIBC‑LIC‑Code eingebetteten Textes, der primäre und sekundäre Daten speichert. Dieses Beispiel zeigt, wie HIBC LIC mit HIBCLICCombinedCodetext kodiert und dekodiert wird.

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

| Name | Beschreibung |
| --- | --- |
| [equals(obj)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `HIBCLICCombinedCodetext`‑Wert entspricht. |
| [getConstructedCodetext()](#getconstructedcodetext) | Erstellt Codetext |
| [getPrimaryData()](#getprimarydata) | Identifiziert primäre Daten. |
| [getSecondaryAndAdditionalData()](#getsecondaryandadditionaldata) | Identifiziert sekundäre und zusätzliche Ergänzungsdaten. |
| [hashCode()](#hashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [initFromString(constructedCodetext)](#initfromstring) | Initialisiert die Instanz aus dem erstellten Codetext. |
| [setPrimaryData()](#setprimarydata) | Identifiziert primäre Daten. |
| [setSecondaryAndAdditionalData()](#setsecondaryandadditionaldata) | Identifiziert sekundäre und zusätzliche Ergänzungsdaten. |

### equals(obj) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `HIBCLICCombinedCodetext`‑Wert entspricht.

| Parameter | Beschreibung |
| --- | --- |
| obj | Ein `HIBCLICCombinedCodetext`‑Wert zum Vergleich mit dieser Instanz. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Erstellt Codetext

**Returns:** Constructed codetext

### getPrimaryData() {#getprimarydata}

Identifiziert primäre Daten.

### getSecondaryAndAdditionalData() {#getsecondaryandadditionaldata}

Identifiziert sekundäre und zusätzliche Ergänzungsdaten.

### hashCode() {#hashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Initialisiert die Instanz aus dem erstellten Codetext.

| Parameter | Beschreibung |
| --- | --- |
| constructedCodetext | Erstellter Codetext. |

### setPrimaryData() {#setprimarydata}

Identifiziert primäre Daten.

### setSecondaryAndAdditionalData() {#setsecondaryandadditionaldata}

Identifiziert sekundäre und zusätzliche Ergänzungsdaten.
