---
title: "DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Erweiterter Codetext-Generator für 2D DataMatrix-Barcodes für den ExtendedCodetext-Modus von DataMatrixEncodeMode //Erweiterter Codetext-Modus //erstelle Codetext let textBuil"
type: docs
weight: 340
url: /de/nodejs/aspose.barcode/datamatrixextcodetextbuilder/
---

## DataMatrixExtCodetextBuilder class

Erweiterter Codetext-Generator für 2D DataMatrix-Barcodes für den ExtendedCodetext-Modus von DataMatrixEncodeMode //Extended codetext mode //create codetext let textBuilder = new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.BYTES, "World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF_8, "犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C_40, "ABCDE"); //generiere Codetext let codetext = textBuilder.getExtendedCodetext(); //generieren let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null, codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.BMP);

```js
new DataMatrixExtCodetextBuilder()
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addCodetextWithEncodeMode(encodeMode, codetext)](#addcodetextwithencodemode) | Fügt Codetext mit definiertem Encode-Modus zu den erweiterten Codetext-Elementen hinzu |
| [addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext)](#addecicodetextwithencodemode) | Fügt Codetext mit erweitertem Kanalbezeichner und definiertem Encode-Modus hinzu |
| [getExtendedCodetext()](#getextendedcodetext) | Erzeugt erweiterten Codetext aus der erweiterten Codetext‑Liste. |

### addCodetextWithEncodeMode(encodeMode, codetext) {#addcodetextwithencodemode}

Fügt Codetext mit definiertem Encode-Modus zu den erweiterten Codetext-Elementen hinzu

| Parameter | Beschreibung |
| --- | --- |
| encodeMode | Encode-Modus-Wert |
| codetext | Codetext in Unicode, der als erweitertes Codetext-Element hinzugefügt wird |

### addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext) {#addecicodetextwithencodemode}

Fügt Codetext mit erweitertem Kanalbezeichner und definiertem Encode-Modus hinzu

| Parameter | Beschreibung |
| --- | --- |
| ECIEncoding | Erweiterter Kanalbezeichner |
| encodeMode | Encode-Modus-Wert |
| codetext | Codetext in Unicode, der als erweitertes Codetext-Element mit erweitertem Kanalbezeichner und definiertem Encode-Modus hinzugefügt wird |

### getExtendedCodetext() {#getextendedcodetext}

Erzeugt erweiterten Codetext aus der erweiterten Codetext‑Liste.

**Returns:** Extended codetext as string
