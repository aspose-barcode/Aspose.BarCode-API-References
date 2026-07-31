---
title: "HIBCLICPrimaryDataCodetext Class"
linktitle: "HIBCLICPrimaryDataCodetext"
articleTitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Class for encoding and decoding the text embedded in the HIBC LIC code which stores primary data. This sample shows how to encode and decode HIBC LIC using H..."
type: docs
weight: 460
url: /nodejs/aspose.barcode/hibclicprimarydatacodetext/
---

## HIBCLICPrimaryDataCodetext class

Class for encoding and decoding the text embedded in the HIBC LIC code which stores primary data. This sample shows how to encode and decode HIBC LIC using HIBCLICPrimaryCodetext.

```js
new HIBCLICPrimaryDataCodetext()
```

**Example:**

```js
let complexCodetext  = new HIBCLICPrimaryCodetext();
complexCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
complexCodetext.setData(new PrimaryData());
complexCodetext.getData().setProductOrCatalogNumber("12345");
complexCodetext.getData().setLabelerIdentificationCode("A999");
complexCodetext.getData().setUnitOfMeasureID(1);
let generator = new ComplexBarcodeGenerator(complexCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getData().getUnitOfMeasureID());
```

## Methods

| Name | Description |
| --- | --- |
| [equals(obj)](./equals/) | Returns a value indicating whether this instance is equal to a specified `HIBCLICPrimaryDataCodetext` value. |
| [getConstructedCodetext()](./getconstructedcodetext/) | Constructs codetext |
| [getData()](./getdata/) | Identifies primary data. |
| [hashCode()](./hashcode/) | Returns the hash code for this instance. |
| [initFromString(constructedCodetext)](./initfromstring/) | Initializes instance from constructed codetext. |
| [setData()](./setdata/) | Identifies primary data. |
