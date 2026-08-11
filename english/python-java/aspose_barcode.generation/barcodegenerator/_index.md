---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode for Python via Java"
description: "BarcodeGenerator for backend barcode images generation. Supported symbologies: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code"
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/barcodegenerator/
---

## BarcodeGenerator class

**Module:** `aspose_barcode.generation.barcode_generator`


BarcodeGenerator for backend barcode images generation. Supported symbologies: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ... This sample shows how to create and save a barcode image.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) | BarcodeGenerator constructor. |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__str__](#__str__) | `str` | No |  |
| [code_text](#code_text) | `str` | No | Text to be encoded. |
| [export_to_xml](#export_to_xml) | `bool` | No | Exports BarCode properties to the xml-stream specified. |
| [generate_barcode_image](#generate_barcode_image) | `Image` | No | Generate the barcode image under current settings. This sample shows how to create and save a barcode image. |
| [import_from_xml](#import_from_xml) | `BarcodeGenerator` | No | Imports BarCode properties from the xml-file specified and creates BarcodeGenerator instance. |
| [parameters](#parameters) | `BaseGenerationParameters` | No | Generation parameters. |
| [save](#save) | `None` | No | Save barcode image to specific file in specific format. |
| [set_code_text](#set_code_text) | `None` | No |  |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [barcode_type](#barcode_type) | `EncodeTypes` | Barcode symbology type. |

### BarcodeGenerator Constructor {#constructor}

```python
__init__(self, encode_type, Optional[str] code_text) -> def
```

BarcodeGenerator constructor.

| Parameter | Type | Description |
| --- | --- | --- |
| `encode_type` | `` |  |
| `code_text` | `Optional[str]` |  |

### BarcodeGenerator.__str__ {#__str__}

```python
__str__(self) -> str
```

**Return Type:** `str`

### BarcodeGenerator.code_text {#code_text}

```python
code_text(self) -> str
```

Text to be encoded.

**Return Type:** `str`

### BarcodeGenerator.export_to_xml {#export_to_xml}

```python
export_to_xml(self, str file_path) -> bool
```

Exports BarCode properties to the xml-stream specified.

| Parameter | Type | Description |
| --- | --- | --- |
| `file_path` | `str` | The path to the file where the XML will be saved. |

**Return Type:** `bool` — Whether the export completed successfully. Returns True in case of success; False Otherwise.

### BarcodeGenerator.generate_barcode_image {#generate_barcode_image}

```python
generate_barcode_image(self) -> Image
```

Generate the barcode image under current settings. This sample shows how to create and save a barcode image.

**Return Type:** `Image`

### BarcodeGenerator.import_from_xml {#import_from_xml}

```python
import_from_xml(self, cls, str resource) -> BarcodeGenerator
```

Imports BarCode properties from the xml-file specified and creates BarcodeGenerator instance.

| Parameter | Type | Description |
| --- | --- | --- |
| `cls` | `` |  |
| `resource` | `str` |  |

**Return Type:** `BarcodeGenerator` — instance

### BarcodeGenerator.parameters {#parameters}

```python
parameters(self) -> BaseGenerationParameters
```

Generation parameters.

**Return Type:** `BaseGenerationParameters` — BaseGenerationParameters

### BarcodeGenerator.save {#save}

```python
save(self, str imagePath, BarCodeImageFormat imageFormat)
```

Save barcode image to specific file in specific format.

| Parameter | Type | Description |
| --- | --- | --- |
| `imagePath` | `str` | Path to save to. |
| `imageFormat` | `BarCodeImageFormat` | Optional format override. If omitted, the format to use is determined from the filename extension. If a file object was used instead of a filename, this parameter should always be used. generator = BarcodeGenerator(EncodeTypes.CODE_128, "123ABCDEFG") generator.save(image_path_to_save3, BarCodeImageFormat.PNG) |

### BarcodeGenerator.set_code_text {#set_code_text}

```python
set_code_text(self, Union[str, bytes] code_text, Optional[str] encoding, Optional[bool] BoM)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `code_text` | `Union[str, bytes]` |  |
| `encoding` | `Optional[str]` |  |
| `BoM` | `Optional[bool]` |  |

### BarcodeGenerator.barcode_type {#barcode_type}

**Type:** `EncodeTypes`

Barcode symbology type.

Barcode symbology type.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `EncodeTypes` |  |

