---
title: "DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Uitgebreide codetextgenerator voor 2D DataMatrix-streepjescodes voor de ExtendedCodetext-modus van DataMatrixEncodeMode //Extended codetext mode //create codetext let textBuil"
type: docs
weight: 340
url: /nl/nodejs/aspose.barcode/datamatrixextcodetextbuilder/
---

## DataMatrixExtCodetextBuilder class

Uitgebreide codetextgenerator voor 2D DataMatrix-streepjescodes voor de ExtendedCodetext-modus van DataMatrixEncodeMode //Extended codetext mode //create codetext let textBuilder = new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.BYTES, "World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF_8, "犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C_40, "ABCDE"); //generate codetext let codetext = textBuilder.getExtendedCodetext(); //generate let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null, codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.BMP);

```js
new DataMatrixExtCodetextBuilder()
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addCodetextWithEncodeMode(encodeMode, codetext)](#addcodetextwithencodemode) | Voegt codetext toe met gedefinieerde encodeermodus aan de uitgebreide codetextitems |
| [addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext)](#addecicodetextwithencodemode) | Voegt codetext toe met Extended Channel Identifier met gedefinieerde encodeermodus |
| [getExtendedCodetext()](#getextendedcodetext) | Genereert uitgebreide codetekst vanuit de uitgebreide codetekst‑lijst. |

### addCodetextWithEncodeMode(encodeMode, codetext) {#addcodetextwithencodemode}

Voegt codetext toe met gedefinieerde encodeermodus aan de uitgebreide codetextitems

| Parameter | Beschrijving |
| --- | --- |
| encodeMode | Encodeermoduswaarde |
| codetext | Codetext in Unicode om toe te voegen als uitgebreid codetextitem |

### addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext) {#addecicodetextwithencodemode}

Voegt codetext toe met Extended Channel Identifier met gedefinieerde encodeermodus

| Parameter | Beschrijving |
| --- | --- |
| ECIEncoding | Extended Channel Identifier |
| encodeMode | Encodeermoduswaarde |
| codetext | Codetext in Unicode om toe te voegen als uitgebreid codetextitem met Extended Channel Identifier met gedefinieerde encodeermodus |

### getExtendedCodetext() {#getextendedcodetext}

Genereert uitgebreide codetekst vanuit de uitgebreide codetekst‑lijst.

**Returns:** Extended codetext as string
