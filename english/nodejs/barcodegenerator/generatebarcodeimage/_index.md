---
title: BarcodeGenerator.generateBarCodeImage
linktitle: generateBarCodeImage
articleTitle: generateBarCodeImage
second_title: Aspose.BarCode for Node.js via Java
description: "Generate the barcode image under current settings. This sample shows how to create and save a barcode image."
type: docs
weight: 90
url: /nodejs/barcodegenerator/generatebarcodeimage/
---
## generateBarCodeImage(object) {#generatebarcodeimage}

Generate the barcode image under current settings. This sample shows how to create and save a barcode image.

```javascript
generateBarCodeImage(format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| format | object | BarCodeImageFormat value (PNG, BMP, JPEG, GIF) |

### Return Value

String

base64 representation of image.

## Examples

```javascript
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```

### See Also

* class [BarcodeGenerator](../)
* assembly [Aspose.BarCode](../../)

