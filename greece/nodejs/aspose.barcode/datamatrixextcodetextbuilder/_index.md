---
title: "DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Εκτεταμένος δημιουργός codetext για 2D DataMatrix barcode για λειτουργία ExtendedCodetext του DataMatrixEncodeMode //Extended codetext mode //create codetext let textBuil"
type: docs
weight: 340
url: /el/nodejs/aspose.barcode/datamatrixextcodetextbuilder/
---

## DataMatrixExtCodetextBuilder class

Εκτεταμένος δημιουργός codetext για 2D DataMatrix barcode για λειτουργία ExtendedCodetext του DataMatrixEncodeMode //Extended codetext mode //create codetext let textBuilder = new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.BYTES, "World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF_8, "犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C_40, "ABCDE"); //generate codetext let codetext = textBuilder.getExtendedCodetext(); //generate let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null, codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.BMP);

```js
new DataMatrixExtCodetextBuilder()
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addCodetextWithEncodeMode(encodeMode, codetext)](#addcodetextwithencodemode) | Προσθέτει codetext με καθορισμένη λειτουργία κωδικοποίησης στα στοιχεία του εκτεταμένου codetext |
| [addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext)](#addecicodetextwithencodemode) | Προσθέτει codetext με Extended Channel Identifier με καθορισμένη λειτουργία κωδικοποίησης |
| [getExtendedCodetext()](#getextendedcodetext) | Δημιουργεί Extended codetext από τη λίστα Extended codetext. |

### addCodetextWithEncodeMode(encodeMode, codetext) {#addcodetextwithencodemode}

Προσθέτει codetext με καθορισμένη λειτουργία κωδικοποίησης στα στοιχεία του εκτεταμένου codetext

| Παράμετρος | Περιγραφή |
| --- | --- |
| encodeMode | Τιμή λειτουργίας κωδικοποίησης |
| codetext | Codetext σε unicode για προσθήκη ως στοιχείο εκτεταμένου codetext |

### addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext) {#addecicodetextwithencodemode}

Προσθέτει codetext με Extended Channel Identifier με καθορισμένη λειτουργία κωδικοποίησης

| Παράμετρος | Περιγραφή |
| --- | --- |
| ECIEncoding | Extended Channel Identifier |
| encodeMode | Τιμή λειτουργίας κωδικοποίησης |
| codetext | Codetext σε unicode για προσθήκη ως στοιχείο εκτεταμένου codetext με Extended Channel Identifier με καθορισμένη λειτουργία κωδικοποίησης |

### getExtendedCodetext() {#getextendedcodetext}

Δημιουργεί Extended codetext από τη λίστα Extended codetext.

**Returns:** Extended codetext as string
