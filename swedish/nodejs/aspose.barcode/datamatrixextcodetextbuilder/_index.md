---
title: "DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Utökad kodtextgenerator för 2D DataMatrix-streckkoder för ExtendedCodetext-läge i DataMatrixEncodeMode //Extended codetext mode //create codetext let textBuil"
type: docs
weight: 340
url: /sv/nodejs/aspose.barcode/datamatrixextcodetextbuilder/
---

## DataMatrixExtCodetextBuilder class

Utökad kodtextgenerator för 2D DataMatrix-streckkoder för ExtendedCodetext-läge i DataMatrixEncodeMode //Extended codetext mode //create codetext let textBuilder = new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.BYTES, "World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF_8, "犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C_40, "ABCDE"); //generate codetext let codetext = textBuilder.getExtendedCodetext(); //generate let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null, codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.BMP);

```js
new DataMatrixExtCodetextBuilder()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addCodetextWithEncodeMode(encodeMode, codetext)](#addcodetextwithencodemode) | Lägger till kodtext med definierat kodningsläge till de utökade kodtextobjekten |
| [addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext)](#addecicodetextwithencodemode) | Lägger till kodtext med Extended Channel Identifier med definierat kodningsläge |
| [getExtendedCodetext()](#getextendedcodetext) | Genererar utökad kodtext från den utökade kodtextlistan. |

### addCodetextWithEncodeMode(encodeMode, codetext) {#addcodetextwithencodemode}

Lägger till kodtext med definierat kodningsläge till de utökade kodtextobjekten

| Parameter | Beskrivning |
| --- | --- |
| encodeMode | Kodningslägesvärde |
| codetext | Kodtext i Unicode att lägga till som utökat kodtextobjekt |

### addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext) {#addecicodetextwithencodemode}

Lägger till kodtext med Extended Channel Identifier med definierat kodningsläge

| Parameter | Beskrivning |
| --- | --- |
| ECIEncoding | Extended Channel Identifier |
| encodeMode | Kodningslägesvärde |
| codetext | Kodtext i Unicode att lägga till som utökat kodtextobjekt med Extended Channel Identifier med definierat kodningsläge |

### getExtendedCodetext() {#getextendedcodetext}

Genererar utökad kodtext från den utökade kodtextlistan.

**Returns:** Extended codetext as string
