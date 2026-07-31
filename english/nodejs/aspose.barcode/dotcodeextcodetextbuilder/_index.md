---
title: "DotCodeExtCodetextBuilder Class"
linktitle: "DotCodeExtCodetextBuilder"
articleTitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Extended codetext generator for 2D DotCode barcodes for ExtendedCodetext Mode of DotCodeEncodeMode"
type: docs
weight: 370
url: /nodejs/aspose.barcode/dotcodeextcodetextbuilder/
---

## DotCodeExtCodetextBuilder class

Extended codetext generator for 2D DotCode barcodes for ExtendedCodetext Mode of DotCodeEncodeMode

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

## Methods

| Name | Description |
| --- | --- |
| [addFNC1FormatIdentifier()](./addfnc1formatidentifier/) | Adds FNC1 format identifier to the extended codetext items |
| [addFNC3ReaderInitialization()](./addfnc3readerinitialization/) | Adds FNC3 reader initialization to the extended codetext items |
| [addFNC3SymbolSeparator()](./addfnc3symbolseparator/) | Adds FNC3 symbol separator to the extended codetext items |
| [addStructuredAppendMode(barcodeId, barcodesCount)](./addstructuredappendmode/) | Adds structured append mode to the extended codetext items |
| [getExtendedCodetext()](./getextendedcodetext/) | Generates Extended codetext from the extended codetext list. |
