---
title: "DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Lagrar specialdata för DataMatrix igenkänd streckkod Detta exempel visar hur man får DataMatrix råvärden let generator = new BarcodeGenerator(EncodeTypes.DATA_MA"
type: docs
weight: 350
url: /sv/nodejs/aspose.barcode/datamatrixextendedparameters/
---

## DataMatrixExtendedParameters class

Lagrar specialdata för DataMatrix igenkänd streckkod Detta exempel visar hur man får DataMatrix råvärden let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345")) generator.save("test.png", BarcodeImageFormat.PNG); let reader = new BarCodeReader("test.png", null, DecodeType.DATA_MATRIX)) let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode type: " + result.getCodeTypeName()); console.log("BarCode codetext: " + result.getCodeText()); console.log("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId()); console.log("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount()); console.log("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId()); console.log("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming()); }

```js
new DataMatrixExtendedParameters()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals(obj)](#equals) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `DataMatrixExtendedParameters`-värde. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Hämtar ID för DataMatrix structured append-lägesstreckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Hämtar antalet DataMatrix structured append-lägesstreckkoder. Standardvärdet är -1. Antalet måste vara ett värde mellan 1 och 35. Valu |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Hämtar ID för DataMatrix structured append-lägesstreckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder |
| [hashCode()](#hashcode) | Returnerar hashkoden för detta objekt. |
| [isReaderProgramming()](#isreaderprogramming) | Indikerar om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av detta `DataMatrixExtendedParameters`. |

### equals(obj) {#equals}

Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `DataMatrixExtendedParameters`-värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | Ett System.Object-värde att jämföra med detta objekt. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Hämtar ID för DataMatrix structured append-lägesstreckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärdet är -1. Värde: ID för DataMatrix structured append-lägesstreckkod.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Hämtar antalet DataMatrix structured append-lägesstreckkoder. Standardvärdet är -1. Antalet måste vara ett värde mellan 1 och 35. Värde: Antalet för DataMatrix structured append-lägesstreckkod.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Hämtar ID för DataMatrix structured append-lägesstreckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärdet är -1. Värde: ID för DataMatrix structured append-lägesstreckkod.

### hashCode() {#hashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code.

### isReaderProgramming() {#isreaderprogramming}

Indikerar om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. Standardvärde är false.

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av detta `DataMatrixExtendedParameters`.

**Returns:** A string that represents this `DataMatrixExtendedParameters`.
