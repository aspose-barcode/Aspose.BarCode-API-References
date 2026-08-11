---
title: "AztecExtCodetextBuilder"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Extended codetext generator for Aztec barcodes for ExtendedCodetext Mode of AztecEncodeMode Use TwoDDisplayText property of BarcodeGenerator to set visible text"
type: docs
weight: 50
url: /nodejs/aspose.barcode/aztecextcodetextbuilder/
---

## AztecExtCodetextBuilder class

Extended codetext generator for Aztec barcodes for ExtendedCodetext Mode of AztecEncodeMode Use TwoDDisplayText property of BarcodeGenerator to set visible text to removing managing characters. This sample shows how to use AztecExtCodetextBuilder in Extended Mode.

```js
new AztecExtCodetextBuilder()
```

**Example:**

```js
//create codetext
     let textBuilder = new AztecExtCodetextBuilder();
     textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
     textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
     textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
     textBuilder.addPlainCodetext("Plain text");
     //generate codetext
     let codetext = textBuilder.getExtendedCodetext();
     //generate
     let generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
     generator.getParameters().getBarcode().getCodeTextParameters().setwoDDisplayText("My Text");
     generator.save("test.bmp", BarcodeImageFormat.BMP);
```

## Methods

| Name | Description |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Generates Extended codetext from the extended codetext list. |

### getExtendedCodetext() {#getextendedcodetext}

Generates Extended codetext from the extended codetext list.

**Returns:** Extended codetext as string
