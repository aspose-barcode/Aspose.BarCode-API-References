---
title: "BarcodeGenerator.CodeText"
linktitle: "CodeText"
articleTitle: "CodeText"
second_title: "Aspose.BarCode for PHP via Java"
description: "Text to be encoded."
type: docs
weight: 10
url: /php/aspose.barcode.generation/barcodegenerator/codetext/
---

## BarcodeGenerator.CodeText

**Access:** Read/Write


### Get

Text to be encoded.


### Set

Encodes the Unicode into a byte sequence using the specified . UTF-8 is the most commonly used encoding. If the encoding supports it and is set to , the function includes a . This function is intended for use with 2D barcodes only (e.g., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). It enables manual encoding of Unicode text using national or special encodings; however, this method is considered obsolete in modern applications. For modern use cases, encoding is recommended for Unicode data. Using this function with 1D barcodes, GS1-compliant barcodes (including 2D), or HIBC barcodes (including 2D) is not supported by the corresponding barcode standards and may lead to unpredictable results.


| Parameter | Type | Description |
| --- | --- | --- |
| `$codeText` | `` | CodeText string |
| `$encoding` | `?string` | Applied encoding |
| `$insertBOM` | `?bool` | Indicates whether to insert a byte order mark (BOM) when the specified encoding supports it (e.g., UTF-8, UTF-16, UTF-32). If set totrue , the BOM is added; iffalse , the BOM is omitted even if the encoding normally uses one. |
