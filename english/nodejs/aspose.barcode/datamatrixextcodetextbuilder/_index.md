---
title: "DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Extended codetext generator for 2D DataMatrix barcodes for ExtendedCodetext Mode of DataMatrixEncodeMode //Extended codetext mode //create codetext let textBuil"
type: docs
weight: 340
url: /nodejs/aspose.barcode/datamatrixextcodetextbuilder/
---

## DataMatrixExtCodetextBuilder class

Extended codetext generator for 2D DataMatrix barcodes for ExtendedCodetext Mode of DataMatrixEncodeMode //Extended codetext mode //create codetext let textBuilder = new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.BYTES, "World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF_8, "犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C_40, "ABCDE"); //generate codetext let codetext = textBuilder.getExtendedCodetext(); //generate let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null, codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.BMP);

```js
new DataMatrixExtCodetextBuilder()
```

## Methods

| Name | Description |
| --- | --- |
| [addCodetextWithEncodeMode(encodeMode, codetext)](#addcodetextwithencodemode) | Adds codetext with defined encode mode to the extended codetext items |
| [addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext)](#addecicodetextwithencodemode) | Adds codetext with Extended Channel Identifier with defined encode mode |
| [getExtendedCodetext()](#getextendedcodetext) | Generates Extended codetext from the extended codetext list. |

### addCodetextWithEncodeMode(encodeMode, codetext) {#addcodetextwithencodemode}

Adds codetext with defined encode mode to the extended codetext items

| Parameter | Description |
| --- | --- |
| encodeMode | Encode mode value |
| codetext | Codetext in unicode to add as extended codetext item |

### addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext) {#addecicodetextwithencodemode}

Adds codetext with Extended Channel Identifier with defined encode mode

| Parameter | Description |
| --- | --- |
| ECIEncoding | Extended Channel Identifier |
| encodeMode | Encode mode value |
| codetext | Codetext in unicode to add as extended codetext item with Extended Channel Identifier with defined encode mode |

### getExtendedCodetext() {#getextendedcodetext}

Generates Extended codetext from the extended codetext list.

**Returns:** Extended codetext as string
