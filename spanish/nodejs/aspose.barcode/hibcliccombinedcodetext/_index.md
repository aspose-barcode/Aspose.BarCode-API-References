---
title: "HIBCLICCombinedCodetext"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos primarios y secundarios."
type: docs
weight: 440
url: /es/nodejs/aspose.barcode/hibcliccombinedcodetext/
---

## HIBCLICCombinedCodetext class

Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos primarios y secundarios. Este ejemplo muestra cómo codificar y decodificar HIBC LIC usando HIBCLICCombinedCodetext.

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

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals(obj)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `HIBCLICCombinedCodetext`. |
| [getConstructedCodetext()](#getconstructedcodetext) | Construye codetext |
| [getPrimaryData()](#getprimarydata) | Identifica los datos primarios. |
| [getSecondaryAndAdditionalData()](#getsecondaryandadditionaldata) | Identifica los datos secundarios y suplementarios adicionales. |
| [hashCode()](#hashcode) | Devuelve el código hash de esta instancia. |
| [initFromString(constructedCodetext)](#initfromstring) | Inicializa la instancia a partir del codetext construido. |
| [setPrimaryData()](#setprimarydata) | Identifica los datos primarios. |
| [setSecondaryAndAdditionalData()](#setsecondaryandadditionaldata) | Identifica los datos secundarios y suplementarios adicionales. |

### equals(obj) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor especificado de `HIBCLICCombinedCodetext`.

| Parámetro | Descripción |
| --- | --- |
| obj | Un valor de `HIBCLICCombinedCodetext` para comparar con esta instancia. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Construye codetext

**Returns:** Constructed codetext

### getPrimaryData() {#getprimarydata}

Identifica los datos primarios.

### getSecondaryAndAdditionalData() {#getsecondaryandadditionaldata}

Identifica los datos secundarios y suplementarios adicionales.

### hashCode() {#hashcode}

Devuelve el código hash de esta instancia.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Inicializa la instancia a partir del codetext construido.

| Parámetro | Descripción |
| --- | --- |
| constructedCodetext | Codetext construido. |

### setPrimaryData() {#setprimarydata}

Identifica los datos primarios.

### setSecondaryAndAdditionalData() {#setsecondaryandadditionaldata}

Identifica los datos secundarios y suplementarios adicionales.
