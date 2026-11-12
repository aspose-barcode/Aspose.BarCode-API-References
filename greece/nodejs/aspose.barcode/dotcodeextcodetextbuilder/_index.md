---
title: "DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Εκτεταμένος γεννήτρια codetext για 2D barcodes DotCode για λειτουργία ExtendedCodetext του DotCodeEncodeMode"
type: docs
weight: 370
url: /el/nodejs/aspose.barcode/dotcodeextcodetextbuilder/
---

## DotCodeExtCodetextBuilder class

Εκτεταμένος γεννήτρια codetext για 2D barcodes DotCode για λειτουργία ExtendedCodetext του DotCodeEncodeMode

```js
new DotCodeExtCodetextBuilder()
```

**Example:**

```js
//Extended codetext mode
//create codetext
let textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");
textBuilder.addFNC3SymbolSeparator();
textBuilder.addFNC3ReaderInitialization();
textBuilder.addPlainCodetext("Reader initialization info");
//generate codetext
let codetext = textBuilder.getExtendedCodetext();
//generate
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
generator.save("test.bmp", BarCodeImageFormat.BMP);
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addFNC1FormatIdentifier()](#addfnc1formatidentifier) | Προσθέτει το αναγνωριστικό μορφής FNC1 στα στοιχεία εκτεταμένου κώδικα κειμένου. |
| [addFNC3ReaderInitialization()](#addfnc3readerinitialization) | Προσθέτει την αρχικοποίηση του αναγνώστη FNC3 στα στοιχεία εκτεταμένου κώδικα κειμένου. |
| [addFNC3SymbolSeparator()](#addfnc3symbolseparator) | Προσθέτει το διαχωριστικό συμβόλου FNC3 στα στοιχεία εκτεταμένου κώδικα κειμένου. |
| [addStructuredAppendMode(barcodeId, barcodesCount)](#addstructuredappendmode) | Προσθέτει τη λειτουργία δομημένης προσάρτησης στα στοιχεία εκτεταμένου κώδικα κειμένου. |
| [getExtendedCodetext()](#getextendedcodetext) | Δημιουργεί Extended codetext από τη λίστα Extended codetext. |

### addFNC1FormatIdentifier() {#addfnc1formatidentifier}

Προσθέτει το αναγνωριστικό μορφής FNC1 στα στοιχεία εκτεταμένου κώδικα κειμένου.

### addFNC3ReaderInitialization() {#addfnc3readerinitialization}

Προσθέτει την αρχικοποίηση του αναγνώστη FNC3 στα στοιχεία εκτεταμένου κώδικα κειμένου.

### addFNC3SymbolSeparator() {#addfnc3symbolseparator}

Προσθέτει το διαχωριστικό συμβόλου FNC3 στα στοιχεία εκτεταμένου κώδικα κειμένου.

### addStructuredAppendMode(barcodeId, barcodesCount) {#addstructuredappendmode}

Προσθέτει τη λειτουργία δομημένης προσάρτησης στα στοιχεία εκτεταμένου κώδικα κειμένου.

| Παράμετρος | Περιγραφή |
| --- | --- |
| barcodeId | Αναγνωριστικό του barcode |
| barcodesCount | Αριθμός barcode |

### getExtendedCodetext() {#getextendedcodetext}

Δημιουργεί Extended codetext από τη λίστα Extended codetext.

**Returns:** Extended codetext as string
