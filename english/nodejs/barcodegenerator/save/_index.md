---
title: "BarcodeGenerator.save"
linktitle: "save"
articleTitle: "save"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Save barcode image to specific file in specific format."
type: docs
weight: 100
url: /nodejs/barcodegenerator/save/
---
## save(object, object) {#save}

Save barcode image to specific file in specific format.

```javascript
save(filePath, format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | object | Path to save to. |
| format | object | BarCodeImageFormat value (PNG, BMP, JPEG, GIF) |

## Examples

```javascript
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```

### See Also

* class [BarcodeGenerator](../)
* assembly [Aspose.BarCode](../../)

