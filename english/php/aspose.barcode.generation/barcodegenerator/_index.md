---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode for PHP via Java"
description: "BarcodeGenerator for backend barcode images generation. supported symbologies: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5"
type: docs
weight: 10
url: /php/aspose.barcode.generation/barcodegenerator/
---

## BarcodeGenerator class

**Namespace:** `Aspose.Barcode.Generation`


BarcodeGenerator for backend barcode images generation. supported symbologies: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ... This sample shows how to create and save a barcode image.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) | BarcodeGenerator constructor. |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [exportToXml](#exporttoxml) | No | Exports BarCode properties to the xml-file specified |
| [generateBarCodeGDImage](#generatebarcodegdimage) | No | Generate the barcode image under current settings. This sample shows how to create and save a barcode image. |
| [generateBarCodeImage](#generatebarcodeimage) | No | Generate the barcode image under current settings. This sample shows how to create and save a barcode image. |
| [importFromXml](#importfromxml) | Yes | Import BarCode properties from xml file |
| [save](#save) | No | Save barcode image to specific file in specific format. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [BarcodeType](#barcodetype) | Read/Write | Barcode symbology type. |
| [CodeText](#codetext) | Read/Write | Text to be encoded. |
| [Parameters](#parameters) | Read-only | Generation parameters. |

### BarcodeGenerator__construct(?int $encodeType, ?string $codeText) {#constructor}

BarcodeGenerator constructor.

| Parameter | Type | Description |
| --- | --- | --- |
| `$encodeType` | `?int` |  |
| `$codeText` | `?string` |  |

### exportToXmlexportToXml(string $xmlFile) {#exporttoxml}

Exports BarCode properties to the xml-file specified

| Parameter | Type | Description |
| --- | --- | --- |
| `$xmlFile` | `string` |  |

**Returns:** bool Whether or not export completed successfully. Returns True in case of success; False Otherwise

### generateBarCodeGDImagegenerateBarCodeGDImage() {#generatebarcodegdimage}

Generate the barcode image under current settings. This sample shows how to create and save a barcode image.

**Returns:** resource|false GD image resource or false on failure.

### generateBarCodeImagegenerateBarCodeImage(int $format, bool $passLicense) {#generatebarcodeimage}

Generate the barcode image under current settings. This sample shows how to create and save a barcode image.

| Parameter | Type | Description |
| --- | --- | --- |
| `$format` | `int` |  |
| `$passLicense` | `bool` |  |

**Returns:** base64 representation of image.

### importFromXmlimportFromXml($resource) (static) {#importfromxml}

Import BarCode properties from xml file

| Parameter | Type | Description |
| --- | --- | --- |
| `$resource` | `` |  |

**Returns:** \Aspose\Barcode\Recognition\BarCodeReader

### savesave(string $filePath, int $format) {#save}

Save barcode image to specific file in specific format.

| Parameter | Type | Description |
| --- | --- | --- |
| `$filePath` | `string` |  |
| `$format` | `int` |  |

### BarcodeType {#barcodetype}

**Access:** Read/Write

Barcode symbology type.

Barcode symbology type.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### CodeText {#codetext}

**Access:** Read/Write

Text to be encoded.

Encodes the Unicode into a byte sequence using the specified . UTF-8 is the most commonly used encoding. If the encoding supports it and is set to , the function includes a . This function is intended for use with 2D barcodes only (e.g., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). It enables manual encoding of Unicode text using national or special encodings; however, this method is considered obsolete in modern applications. For modern use cases, encoding is recommended for Unicode data. Using this function with 1D barcodes, GS1-compliant barcodes (including 2D), or HIBC barcodes (including 2D) is not supported by the corresponding barcode standards and may lead to unpredictable results.

| Parameter | Type | Description |
| --- | --- | --- |
| `$codeText` | `` | CodeText string |
| `$encoding` | `?string` | Applied encoding |
| `$insertBOM` | `?bool` | Indicates whether to insert a byte order mark (BOM) when the specified encoding supports it (e.g., UTF-8, UTF-16, UTF-32). If set totrue , the BOM is added; iffalse , the BOM is omitted even if the encoding normally uses one. |

### Parameters {#parameters}

**Access:** Read-only

**Returns:** BaseGenerationParameters

Generation parameters.

