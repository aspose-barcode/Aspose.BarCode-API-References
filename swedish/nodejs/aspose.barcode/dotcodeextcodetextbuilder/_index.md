---
title: "DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Utökad kodtextgenerator för 2D DotCode‑streckkoder för ExtendedCodetext‑läge i DotCodeEncodeMode"
type: docs
weight: 370
url: /sv/nodejs/aspose.barcode/dotcodeextcodetextbuilder/
---

## DotCodeExtCodetextBuilder class

Utökad kodtextgenerator för 2D DotCode‑streckkoder för ExtendedCodetext‑läge i DotCodeEncodeMode

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addFNC1FormatIdentifier()](#addfnc1formatidentifier) | Lägger till FNC1‑formatidentifierare till de utökade kodtextobjekten |
| [addFNC3ReaderInitialization()](#addfnc3readerinitialization) | Lägger till FNC3‑läsarinitiering till de utökade kodtextobjekten |
| [addFNC3SymbolSeparator()](#addfnc3symbolseparator) | Lägger till FNC3‑symbolseparator till de utökade kodtextobjekten |
| [addStructuredAppendMode(barcodeId, barcodesCount)](#addstructuredappendmode) | Lägger till strukturerat tilläggsläge till de utökade kodtextobjekten |
| [getExtendedCodetext()](#getextendedcodetext) | Genererar utökad kodtext från den utökade kodtextlistan. |

### addFNC1FormatIdentifier() {#addfnc1formatidentifier}

Lägger till FNC1‑formatidentifierare till de utökade kodtextobjekten

### addFNC3ReaderInitialization() {#addfnc3readerinitialization}

Lägger till FNC3‑läsarinitiering till de utökade kodtextobjekten

### addFNC3SymbolSeparator() {#addfnc3symbolseparator}

Lägger till FNC3‑symbolseparator till de utökade kodtextobjekten

### addStructuredAppendMode(barcodeId, barcodesCount) {#addstructuredappendmode}

Lägger till strukturerat tilläggsläge till de utökade kodtextobjekten

| Parameter | Beskrivning |
| --- | --- |
| barcodeId | ID för streckkod |
| barcodesCount | Antal streckkoder |

### getExtendedCodetext() {#getextendedcodetext}

Genererar utökad kodtext från den utökade kodtextlistan.

**Returns:** Extended codetext as string
