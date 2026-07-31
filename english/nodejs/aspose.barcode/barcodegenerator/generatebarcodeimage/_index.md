---
title: "BarcodeGenerator.generateBarCodeImage"
linktitle: "generateBarCodeImage"
articleTitle: "generateBarCodeImage"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Generate the barcode image under current settings. This sample shows how to create and save a barcode image."
type: docs
weight: 30
url: /nodejs/aspose.barcode/barcodegenerator/generatebarcodeimage/
---

## generateBarCodeImage(format)

Generate the barcode image under current settings. This sample shows how to create and save a barcode image.

| Parameter | Type | Description |
| --- | --- | --- |
| format | BarCodeImageFormat | BarCodeImageFormat value (PNG, BMP, JPEG, GIF) |

**Returns:** String — base64 representation of image.

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```
