---
title: "BarcodeGenerator.save"
linktitle: "save"
articleTitle: "save"
second_title: "Aspose.BarCode for Python via Java"
description: "Save barcode image to specific file in specific format."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation.barcode_generator/barcodegenerator/save/
---

## BarcodeGenerator.save

```python
save(self, str imagePath, BarCodeImageFormat imageFormat)
```


Save barcode image to specific file in specific format.


| Parameter | Type | Description |
| --- | --- | --- |
| `imagePath` | `str` | Path to save to. |
| `imageFormat` | `BarCodeImageFormat` | Optional format override. If omitted, the format to use is determined from the filename extension. If a file object was used instead of a filename, this parameter should always be used. generator = BarcodeGenerator(EncodeTypes.CODE_128, "123ABCDEFG") generator.save(image_path_to_save3, BarCodeImageFormat.PNG) |
