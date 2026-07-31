---
title: "BarcodeGenerator Class"
linktitle: "BarcodeGenerator"
articleTitle: "BarcodeGenerator"
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
| [__init__](./barcodegenerator/) | BarcodeGenerator constructor. |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__str__](./__str__/) | `str` | No |  |
| [code_text](./code_text/) | `str` | No | Text to be encoded. |
| [export_to_xml](./export_to_xml/) | `bool` | No | Exports BarCode properties to the xml-stream specified. |
| [generate_barcode_image](./generate_barcode_image/) | `Image` | No | Generate the barcode image under current settings. This sample shows how to create and save a barcode image. |
| [import_from_xml](./import_from_xml/) | `BarcodeGenerator` | No | Imports BarCode properties from the xml-file specified and creates BarcodeGenerator instance. |
| [parameters](./parameters/) | `BaseGenerationParameters` | No | Generation parameters. |
| [save](./save/) | `None` | No | Save barcode image to specific file in specific format. |
| [set_code_text](./set_code_text/) | `None` | No |  |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [barcode_type](./barcode_type/) | `EncodeTypes` | Barcode symbology type. |
