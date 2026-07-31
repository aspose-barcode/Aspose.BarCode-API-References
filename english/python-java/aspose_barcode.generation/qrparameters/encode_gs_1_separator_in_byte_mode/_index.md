---
title: "QrParameters.encode_GS_1_separator_in_byte_mode"
linktitle: "encode_GS_1_separator_in_byte_mode"
articleTitle: "encode_GS_1_separator_in_byte_mode"
second_title: "Aspose.BarCode for Python via Java"
description: "Gets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes. If False, GS1 separators may be encoded a"
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/qrparameters/encode_gs_1_separator_in_byte_mode/
---

## QrParameters.encode_GS_1_separator_in_byte_mode

**Type:** `bool`


### Get

Gets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes. If False, GS1 separators may be encoded as '' in Alphanumeric mode according to the QR specification. If True, GS1 group separators are encoded in Byte mode as the 0x1D character, and '' characters are also encoded in Byte mode to preserve them as data. This option may improve compatibility with decoders that expect byte-level GS1 group separators and prevents '' data characters from being interpreted as GS1 separators. Returns: bool: True if GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes; otherwise, False.


### Set

Sets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes. If False, GS1 separators may be encoded as '' in Alphanumeric mode according to the QR specification. If True, GS1 group separators are encoded in Byte mode as the 0x1D character, and '' characters are also encoded in Byte mode to preserve them as data. This option may improve compatibility with decoders that expect byte-level GS1 group separators and prevents '' data characters from being interpreted as GS1 separators. Args: value: True if GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes; otherwise, False.


| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `bool` |  |
