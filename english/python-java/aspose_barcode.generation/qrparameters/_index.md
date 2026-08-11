---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "Aspose.BarCode for Python via Java"
description: "QR parameters."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/qrparameters/
---

## QrParameters class

**Module:** `aspose_barcode.generation.qr_parameters`


QR parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__str__](#__str__) | `str` | No | Returns a human-readable string representation of this QrParameters. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [aspect_ratio](#aspect_ratio) | `float` | Height/Width ratio of 2D BarCode module. |
| [eci_encoding](#eci_encoding) | `ECIEncodings` |  |
| [encode_GS_1_separator_in_byte_mode](#encode_gs_1_separator_in_byte_mode) | `bool` | Gets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes. If False, GS1 separators may be encoded as '' in Alphanumeric mode according to the QR specification. If True, GS1 group separators are encoded in Byte mode as the 0x1D character, and '' characters are also encoded in Byte mode to preserve them as data. This option may improve compatibility with decoders that expect byte-level GS1 group separators and prevents '' data characters from being interpreted as GS1 separators. Returns: bool: True if GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes; otherwise, False. |
| [encode_mode](#encode_mode) | `QREncodeMode` |  |
| [error_level](#error_level) | `QRErrorLevel` |  |
| [micro_qr_version](#micro_qr_version) | `MicroQRVersion` | Version of MicroQR Code. |
| [qr_eci_encoding](#qr_eci_encoding) | `ECIEncodings` | Extended Channel Interpretation Identifiers. |
| [qr_encode_mode](#qr_encode_mode) | `QREncodeMode` | QR symbology type of BarCode's encoding mode. |
| [qr_encode_type](#qr_encode_type) | `QREncodeType` | QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR. |
| [qr_error_level](#qr_error_level) | `QRErrorLevel` | Level of Reed-Solomon error correction for QR barcode. From low to high: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. see QRErrorLevel. |
| [qr_version](#qr_version) | `QRVersion` | Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. Default value is QRVersion.AUTO. |
| [rect_micro_qr_version](#rect_micro_qr_version) | `RectMicroQRVersion` | Version of RectMicroQR Code. |
| [structured_append](#structured_append) | `Optional[QrStructuredAppendParameters]` | QR structured append parameters. |
| [version](#version) | `QRVersion` |  |

### QrParameters Constructor {#constructor}

```python
__init__(self, _java_class)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `_java_class` | `` |  |

### QrParameters.__str__ {#__str__}

```python
__str__(self) -> str
```

Returns a human-readable string representation of this QrParameters.

**Return Type:** `str` — A string that represents this QrParameters.

### QrParameters.aspect_ratio {#aspect_ratio}

**Type:** `float`

Height/Width ratio of 2D BarCode module.

Height/Width ratio of 2D BarCode module.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `float` |  |

### QrParameters.eci_encoding {#eci_encoding}

**Type:** `ECIEncodings`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `ECIEncodings` |  |

### QrParameters.encode_GS_1_separator_in_byte_mode {#encode_gs_1_separator_in_byte_mode}

**Type:** `bool`

Gets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes. If False, GS1 separators may be encoded as '' in Alphanumeric mode according to the QR specification. If True, GS1 group separators are encoded in Byte mode as the 0x1D character, and '' characters are also encoded in Byte mode to preserve them as data. This option may improve compatibility with decoders that expect byte-level GS1 group separators and prevents '' data characters from being interpreted as GS1 separators. Returns: bool: True if GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes; otherwise, False.

Sets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes. If False, GS1 separators may be encoded as '' in Alphanumeric mode according to the QR specification. If True, GS1 group separators are encoded in Byte mode as the 0x1D character, and '' characters are also encoded in Byte mode to preserve them as data. This option may improve compatibility with decoders that expect byte-level GS1 group separators and prevents '' data characters from being interpreted as GS1 separators. Args: value: True if GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes; otherwise, False.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `bool` |  |

### QrParameters.encode_mode {#encode_mode}

**Type:** `QREncodeMode`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `QREncodeMode` |  |

### QrParameters.error_level {#error_level}

**Type:** `QRErrorLevel`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `QRErrorLevel` |  |

### QrParameters.micro_qr_version {#micro_qr_version}

**Type:** `MicroQRVersion`

Version of MicroQR Code.

Version of MicroQR Code.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `MicroQRVersion` |  |

### QrParameters.qr_eci_encoding {#qr_eci_encoding}

**Type:** `ECIEncodings`

Extended Channel Interpretation Identifiers.

Extended Channel Interpretation Identifiers.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `ECIEncodings` |  |

### QrParameters.qr_encode_mode {#qr_encode_mode}

**Type:** `QREncodeMode`

QR symbology type of BarCode's encoding mode.

QR symbology type of BarCode's encoding mode.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `QREncodeMode` |  |

### QrParameters.qr_encode_type {#qr_encode_type}

**Type:** `QREncodeType`

QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR.

QR / MicroQR selector mode.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `QREncodeType` |  |

### QrParameters.qr_error_level {#qr_error_level}

**Type:** `QRErrorLevel`

Level of Reed-Solomon error correction for QR barcode. From low to high: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. see QRErrorLevel.

Level of Reed-Solomon error correction for QR barcode. From low to high: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. see QRErrorLevel.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `QRErrorLevel` |  |

### QrParameters.qr_version {#qr_version}

**Type:** `QRVersion`

Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. Default value is QRVersion.AUTO.

Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. Default value is QRVersion.AUTO.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `QRVersion` |  |

### QrParameters.rect_micro_qr_version {#rect_micro_qr_version}

**Type:** `RectMicroQRVersion`

Version of RectMicroQR Code.

Version of RectMicroQR Code.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `RectMicroQRVersion` |  |

### QrParameters.structured_append {#structured_append}

**Type:** `Optional[QrStructuredAppendParameters]`

QR structured append parameters.

QR structured append parameters.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `QrStructuredAppendParameters` |  |

### QrParameters.version {#version}

**Type:** `QRVersion`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `QRVersion` |  |

