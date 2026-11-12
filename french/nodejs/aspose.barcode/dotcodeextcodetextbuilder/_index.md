---
title: "DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Générateur de codetext étendu pour les codes-barres 2D DotCode en mode ExtendedCodetext de DotCodeEncodeMode"
type: docs
weight: 370
url: /fr/nodejs/aspose.barcode/dotcodeextcodetextbuilder/
---

## DotCodeExtCodetextBuilder class

Générateur de codetext étendu pour les codes-barres 2D DotCode en mode ExtendedCodetext de DotCodeEncodeMode

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

## Méthodes

| Nom | Description |
| --- | --- |
| [addFNC1FormatIdentifier()](#addfnc1formatidentifier) | Ajoute l'identifiant de format FNC1 aux éléments de codetext étendus |
| [addFNC3ReaderInitialization()](#addfnc3readerinitialization) | Ajoute l'initialisation du lecteur FNC3 aux éléments de codetext étendus |
| [addFNC3SymbolSeparator()](#addfnc3symbolseparator) | Ajoute le séparateur de symbole FNC3 aux éléments de codetext étendus |
| [addStructuredAppendMode(barcodeId, barcodesCount)](#addstructuredappendmode) | Ajoute le mode d'ajout structuré aux éléments de codetext étendus |
| [getExtendedCodetext()](#getextendedcodetext) | Génère le codetext étendu à partir de la liste de codetext étendu. |

### addFNC1FormatIdentifier() {#addfnc1formatidentifier}

Ajoute l'identifiant de format FNC1 aux éléments de codetext étendus

### addFNC3ReaderInitialization() {#addfnc3readerinitialization}

Ajoute l'initialisation du lecteur FNC3 aux éléments de codetext étendus

### addFNC3SymbolSeparator() {#addfnc3symbolseparator}

Ajoute le séparateur de symbole FNC3 aux éléments de codetext étendus

### addStructuredAppendMode(barcodeId, barcodesCount) {#addstructuredappendmode}

Ajoute le mode d'ajout structuré aux éléments de codetext étendus

| Paramètre | Description |
| --- | --- |
| barcodeId | ID du code-barres |
| barcodesCount | Nombre de codes-barres |

### getExtendedCodetext() {#getextendedcodetext}

Génère le codetext étendu à partir de la liste de codetext étendu.

**Returns:** Extended codetext as string
