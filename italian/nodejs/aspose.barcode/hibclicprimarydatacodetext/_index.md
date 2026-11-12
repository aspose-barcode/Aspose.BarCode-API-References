---
title: "HIBCLICPrimaryDataCodetext"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Classe per la codifica e la decodifica del testo incorporato nel codice HIBC LIC che memorizza i dati primari."
type: docs
weight: 460
url: /it/nodejs/aspose.barcode/hibclicprimarydatacodetext/
---

## HIBCLICPrimaryDataCodetext class

Classe per la codifica e la decodifica del testo incorporato nel codice HIBC LIC che memorizza i dati primari. Questo esempio mostra come codificare e decodificare HIBC LIC usando HIBCLICPrimaryCodetext.

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [equals(obj)](#equals) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di `HIBCLICPrimaryDataCodetext`. |
| [getConstructedCodetext()](#getconstructedcodetext) | Costruisce il codetext |
| [getData()](#getdata) | Identifica i dati primari. |
| [hashCode()](#hashcode) | Restituisce il codice hash per questa istanza. |
| [initFromString(constructedCodetext)](#initfromstring) | Inizializza l'istanza dal codetext costruito. |
| [setData()](#setdata) | Identifica i dati primari. |

### equals(obj) {#equals}

Restituisce un valore che indica se questa istanza è uguale a un valore specificato di `HIBCLICPrimaryDataCodetext`.

| Parametro | Descrizione |
| --- | --- |
| obj | Un valore `HIBCLICPrimaryDataCodetext` da confrontare con questa istanza. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Costruisce il codetext

**Returns:** Constructed codetext

### getData() {#getdata}

Identifica i dati primari.

### hashCode() {#hashcode}

Restituisce il codice hash per questa istanza.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Inizializza l'istanza dal codetext costruito.

| Parametro | Descrizione |
| --- | --- |
| constructedCodetext | Codetext costruito. |

### setData() {#setdata}

Identifica i dati primari.
