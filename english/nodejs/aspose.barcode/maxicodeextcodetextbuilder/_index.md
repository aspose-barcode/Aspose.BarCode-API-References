---
title: "MaxiCodeExtCodetextBuilder"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Extended codetext generator for MaxiCode barcodes for ExtendedCodetext Mode of MaxiCodeEncodeMode Use TwoDDisplayText property of BarcodeGenerator to set visibl"
type: docs
weight: 630
url: /nodejs/aspose.barcode/maxicodeextcodetextbuilder/
---

## MaxiCodeExtCodetextBuilder class

Extended codetext generator for MaxiCode barcodes for ExtendedCodetext Mode of MaxiCodeEncodeMode Use TwoDDisplayText property of BarcodeGenerator to set visible text to removing managing characters. This sample shows how to use MaxiCodeExtCodetextBuilder in Extended Mode.

```js
new MaxiCodeExtCodetextBuilder()
```

**Example:**

```js
//create codetext
let textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");

//generate codetext
let codetext = textBuilder.getExtendedCodetext();

//generate
let generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
generator.save("test.bmp", BarcodeImageFormat.BMP);
```

## Methods

| Name | Description |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Generates Extended codetext from the extended codetext list. |

### getExtendedCodetext() {#getextendedcodetext}

Generates Extended codetext from the extended codetext list.

**Returns:** Extended codetext as string
