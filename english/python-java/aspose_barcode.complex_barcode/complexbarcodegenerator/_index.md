---
title: "ComplexBarcodeGenerator"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for Python via Java"
description: "ComplexBarcodeGenerator for backend complex barcode (e.g. SwissQR) images generation. This sample shows how to create and save a SwissQR image."
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/complexbarcodegenerator/
---

## ComplexBarcodeGenerator class

**Module:** `aspose_barcode.complex_barcode.complex_barcode_generator`


ComplexBarcodeGenerator for backend complex barcode (e.g. SwissQR) images generation. This sample shows how to create and save a SwissQR image.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) | Creates an instance of ComplexBarcodeGenerator. |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [generate_barcode_image](#generate_barcode_image) | `"Image.Image"` | No | Generates complex barcode image under current settings. |
| [parameters](#parameters) | `BaseGenerationParameters` | No | Generation parameters. |
| [save](#save) | `None` | No | Save barcode image to specific file in specific format. |

### ComplexBarcodeGenerator Constructor {#constructor}

```python
__init__(self, IComplexCodetext complexCodetext) -> def
```

Creates an instance of ComplexBarcodeGenerator.

| Parameter | Type | Description |
| --- | --- | --- |
| `complexCodetext` | `IComplexCodetext` | Complex codetext |

### ComplexBarcodeGenerator.generate_barcode_image {#generate_barcode_image}

```python
generate_barcode_image(self) -> "Image.Image"
```

Generates complex barcode image under current settings.

**Return Type:** `"Image.Image"` — Pillow Image object of barcode image

### ComplexBarcodeGenerator.parameters {#parameters}

```python
parameters(self) -> BaseGenerationParameters
```

Generation parameters.

**Return Type:** `BaseGenerationParameters`

### ComplexBarcodeGenerator.save {#save}

```python
save(self, Union[str, io.BytesIO] image_source, BarCodeImageFormat image_format)
```

Save barcode image to specific file in specific format.

| Parameter | Type | Description |
| --- | --- | --- |
| `image_source` | `Union[str, io.BytesIO]` |  |
| `image_format` | `BarCodeImageFormat` |  |

