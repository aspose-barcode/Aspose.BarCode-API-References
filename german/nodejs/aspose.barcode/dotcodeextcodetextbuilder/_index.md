---
title: "DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Erweiterter Codetext-Generator für 2D DotCode-Barcodes für den ExtendedCodetext-Modus von DotCodeEncodeMode"
type: docs
weight: 370
url: /de/nodejs/aspose.barcode/dotcodeextcodetextbuilder/
---

## DotCodeExtCodetextBuilder class

Erweiterter Codetext-Generator für 2D DotCode-Barcodes für den ExtendedCodetext-Modus von DotCodeEncodeMode

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

| Name | Beschreibung |
| --- | --- |
| [addFNC1FormatIdentifier()](#addfnc1formatidentifier) | Fügt den FNC1-Formatbezeichner zu den erweiterten Codetext-Elementen hinzu. |
| [addFNC3ReaderInitialization()](#addfnc3readerinitialization) | Fügt die FNC3-Leserinitialisierung zu den erweiterten Codetext-Elementen hinzu. |
| [addFNC3SymbolSeparator()](#addfnc3symbolseparator) | Fügt den FNC3-Symboltrenner zu den erweiterten Codetext-Elementen hinzu. |
| [addStructuredAppendMode(barcodeId, barcodesCount)](#addstructuredappendmode) | Fügt den strukturierten Anfügemodus zu den erweiterten Codetext-Elementen hinzu. |
| [getExtendedCodetext()](#getextendedcodetext) | Erzeugt erweiterten Codetext aus der erweiterten Codetext‑Liste. |

### addFNC1FormatIdentifier() {#addfnc1formatidentifier}

Fügt den FNC1-Formatbezeichner zu den erweiterten Codetext-Elementen hinzu.

### addFNC3ReaderInitialization() {#addfnc3readerinitialization}

Fügt die FNC3-Leserinitialisierung zu den erweiterten Codetext-Elementen hinzu.

### addFNC3SymbolSeparator() {#addfnc3symbolseparator}

Fügt den FNC3-Symboltrenner zu den erweiterten Codetext-Elementen hinzu.

### addStructuredAppendMode(barcodeId, barcodesCount) {#addstructuredappendmode}

Fügt den strukturierten Anfügemodus zu den erweiterten Codetext-Elementen hinzu.

| Parameter | Beschreibung |
| --- | --- |
| barcodeId | ID des Barcodes |
| barcodesCount | Barcode-Anzahl |

### getExtendedCodetext() {#getextendedcodetext}

Erzeugt erweiterten Codetext aus der erweiterten Codetext‑Liste.

**Returns:** Extended codetext as string
