---
title: "DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Generatore di codetext esteso per barcode DotCode 2D per la modalità ExtendedCodetext di DotCodeEncodeMode"
type: docs
weight: 370
url: /it/nodejs/aspose.barcode/dotcodeextcodetextbuilder/
---

## DotCodeExtCodetextBuilder class

Generatore di codetext esteso per barcode DotCode 2D per la modalità ExtendedCodetext di DotCodeEncodeMode

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addFNC1FormatIdentifier()](#addfnc1formatidentifier) | Aggiunge l'identificatore di formato FNC1 agli elementi di codetext estesi |
| [addFNC3ReaderInitialization()](#addfnc3readerinitialization) | Aggiunge l'inizializzazione del lettore FNC3 agli elementi di codetext estesi |
| [addFNC3SymbolSeparator()](#addfnc3symbolseparator) | Aggiunge il separatore di simboli FNC3 agli elementi di codetext estesi |
| [addStructuredAppendMode(barcodeId, barcodesCount)](#addstructuredappendmode) | Aggiunge la modalità di aggiunta strutturata agli elementi di codetext estesi |
| [getExtendedCodetext()](#getextendedcodetext) | Genera il codetext esteso dall'elenco di codetext esteso. |

### addFNC1FormatIdentifier() {#addfnc1formatidentifier}

Aggiunge l'identificatore di formato FNC1 agli elementi di codetext estesi

### addFNC3ReaderInitialization() {#addfnc3readerinitialization}

Aggiunge l'inizializzazione del lettore FNC3 agli elementi di codetext estesi

### addFNC3SymbolSeparator() {#addfnc3symbolseparator}

Aggiunge il separatore di simboli FNC3 agli elementi di codetext estesi

### addStructuredAppendMode(barcodeId, barcodesCount) {#addstructuredappendmode}

Aggiunge la modalità di aggiunta strutturata agli elementi di codetext estesi

| Parametro | Descrizione |
| --- | --- |
| barcodeId | ID del codice a barre |
| barcodesCount | Conteggio dei codici a barre |

### getExtendedCodetext() {#getextendedcodetext}

Genera il codetext esteso dall'elenco di codetext esteso.

**Returns:** Extended codetext as string
