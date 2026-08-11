---
title: "ComplexBarcodeGenerator"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for PHP via Java"
description: "ComplexBarcodeGenerator for backend complex barcode (e.g. SwissQR) images generation. This sample shows how to create and save a SwissQR image."
type: docs
weight: 10
url: /php/aspose.barcode.complexbarcode/complexbarcodegenerator/
---

## ComplexBarcodeGenerator class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


ComplexBarcodeGenerator for backend complex barcode (e.g. SwissQR) images generation. This sample shows how to create and save a SwissQR image.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) | Creates an instance of ComplexBarcodeGenerator. |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [generateBarcodeImage](#generatebarcodeimage) | No | Generates complex barcode image under current settings. |
| [save](#save) | No | Save barcode image to specific file in specific format. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [Parameters](#parameters) | Read-only | Generation parameters. |

### ComplexBarcodeGenerator__construct(IComplexCodetext $complexCodetext) {#constructor}

Creates an instance of ComplexBarcodeGenerator.

| Parameter | Type | Description |
| --- | --- | --- |
| `$complexCodetext` | `IComplexCodetext` |  |

### generateBarcodeImagegenerateBarcodeImage(int $format, bool $passLicense) {#generatebarcodeimage}

Generates complex barcode image under current settings.

| Parameter | Type | Description |
| --- | --- | --- |
| `$format` | `int` |  |
| `$passLicense` | `bool` |  |

**Returns:** string base64 representation of image.

### savesave(string $filePath, int $format) {#save}

Save barcode image to specific file in specific format.

| Parameter | Type | Description |
| --- | --- | --- |
| `$filePath` | `string` | string Path to save to. |
| `$format` | `int` |  |

### Parameters {#parameters}

**Access:** Read-only

Generation parameters.

