---
title: "QrParameters Class"
linktitle: "QrParameters"
articleTitle: "QrParameters"
second_title: "Aspose.BarCode for Python via Java"
description: "QR parameters."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation.qr_parameters/qrparameters/
---

## QrParameters class

**Module:** `aspose_barcode.generation.qr_parameters`


QR parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](./qrparameters/) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__str__](./__str__/) | `str` | No | Returns a human-readable string representation of this QrParameters. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [aspect_ratio](./aspect_ratio/) | `float` | Height/Width ratio of 2D BarCode module. |
| [eci_encoding](./eci_encoding/) | `ECIEncodings` |  |
| [encode_GS_1_separator_in_byte_mode](./encode_gs_1_separator_in_byte_mode/) | `bool` | Gets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes. If False, GS1 separators may be encoded as '' in Alphanumeric mode according to the QR specification. If True, GS1 group separators are encoded in Byte mode as the 0x1D character, and '' characters are also encoded in Byte mode to preserve them as data. This option may improve compatibility with decoders that expect byte-level GS1 group separators and prevents '' data characters from being interpreted as GS1 separators. Returns: bool: True if GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes; otherwise, False. |
| [encode_mode](./encode_mode/) | `QREncodeMode` |  |
| [error_level](./error_level/) | `QRErrorLevel` |  |
| [micro_qr_version](./micro_qr_version/) | `MicroQRVersion` | Version of MicroQR Code. |
| [qr_eci_encoding](./qr_eci_encoding/) | `ECIEncodings` | Extended Channel Interpretation Identifiers. |
| [qr_encode_mode](./qr_encode_mode/) | `QREncodeMode` | QR symbology type of BarCode's encoding mode. |
| [qr_encode_type](./qr_encode_type/) | `QREncodeType` | QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR. |
| [qr_error_level](./qr_error_level/) | `QRErrorLevel` | Level of Reed-Solomon error correction for QR barcode. From low to high: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. see QRErrorLevel. |
| [qr_version](./qr_version/) | `QRVersion` | Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. Default value is QRVersion.AUTO. |
| [rect_micro_qr_version](./rect_micro_qr_version/) | `RectMicroQRVersion` | Version of RectMicroQR Code. |
| [structured_append](./structured_append/) | `Optional[QrStructuredAppendParameters]` | QR structured append parameters. |
| [version](./version/) | `QRVersion` |  |
