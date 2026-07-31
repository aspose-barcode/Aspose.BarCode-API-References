---
title: "BarcodeGenerator.save"
linktitle: "save"
articleTitle: "save"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Save barcode image to specific file in specific format."
type: docs
weight: 70
url: /nodejs/aspose.barcode/barcodegenerator/save/
---

## save(filePath, format)

Save barcode image to specific file in specific format.

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | Path to save to. |
| format | BarCodeImageFormat | BarCodeImageFormat value (PNG, BMP, JPEG, GIF) |

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```
