---
title: "DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Uitgebreide codetekstgenerator voor 2D DotCode-barcodes voor ExtendedCodetext-modus van DotCodeEncodeMode"
type: docs
weight: 370
url: /nl/nodejs/aspose.barcode/dotcodeextcodetextbuilder/
---

## DotCodeExtCodetextBuilder class

Uitgebreide codetekstgenerator voor 2D DotCode-barcodes voor ExtendedCodetext-modus van DotCodeEncodeMode

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

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addFNC1FormatIdentifier()](#addfnc1formatidentifier) | Voegt FNC1-formaatidentificatie toe aan de uitgebreide codetext-items |
| [addFNC3ReaderInitialization()](#addfnc3readerinitialization) | Voegt FNC3-lezerinitialisatie toe aan de uitgebreide codetext-items |
| [addFNC3SymbolSeparator()](#addfnc3symbolseparator) | Voegt FNC3-symboolscheidingsteken toe aan de uitgebreide codetext-items |
| [addStructuredAppendMode(barcodeId, barcodesCount)](#addstructuredappendmode) | Voegt gestructureerde toevoegingsmodus toe aan de uitgebreide codetext-items |
| [getExtendedCodetext()](#getextendedcodetext) | Genereert uitgebreide codetekst vanuit de uitgebreide codetekst‑lijst. |

### addFNC1FormatIdentifier() {#addfnc1formatidentifier}

Voegt FNC1-formaatidentificatie toe aan de uitgebreide codetext-items

### addFNC3ReaderInitialization() {#addfnc3readerinitialization}

Voegt FNC3-lezerinitialisatie toe aan de uitgebreide codetext-items

### addFNC3SymbolSeparator() {#addfnc3symbolseparator}

Voegt FNC3-symboolscheidingsteken toe aan de uitgebreide codetext-items

### addStructuredAppendMode(barcodeId, barcodesCount) {#addstructuredappendmode}

Voegt gestructureerde toevoegingsmodus toe aan de uitgebreide codetext-items

| Parameter | Beschrijving |
| --- | --- |
| barcodeId | ID van barcode |
| barcodesCount | Aantal barcodes |

### getExtendedCodetext() {#getextendedcodetext}

Genereert uitgebreide codetekst vanuit de uitgebreide codetekst‑lijst.

**Returns:** Extended codetext as string
