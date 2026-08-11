---
title: "BarcodeSettings"
linktitle: "BarcodeSettings"
second_title: "Aspose.BarCode for Python via Java"
description: "Contains settings for barcode recognition."
type: docs
weight: 10
url: /python-java/aspose_barcode.recognition/barcodesettings/
---

## BarcodeSettings class

**Module:** `aspose_barcode.recognition.barcode_settings`


Contains settings for barcode recognition.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [australia_post](#australia_post) | `"AustraliaPostSettings"` | No |  |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [checksum_validation](#checksum_validation) | `ChecksumValidation` |  |
| [detect_encoding](#detect_encoding) | `bool` |  |
| [only_requested_types](#only_requested_types) | `bool` | Returns only barcode types explicitly specified for recognition. When enabled, recognized barcodes of other compatible or equivalent types are filtered out. Default value is false. Example: |
| [strip_fnc](#strip_fnc) | `bool` |  |

### BarcodeSettings Constructor {#constructor}

```python
__init__(self, _java_class) -> def
```

| Parameter | Type | Description |
| --- | --- | --- |
| `_java_class` | `` |  |

### BarcodeSettings.australia_post {#australia_post}

```python
australia_post(self) -> "AustraliaPostSettings"
```

**Return Type:** `"AustraliaPostSettings"`

### BarcodeSettings.checksum_validation {#checksum_validation}

**Type:** `ChecksumValidation`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `ChecksumValidation` |  |

### BarcodeSettings.detect_encoding {#detect_encoding}

**Type:** `bool`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `bool` |  |

### BarcodeSettings.only_requested_types {#only_requested_types}

**Type:** `bool`

Returns only barcode types explicitly specified for recognition. When enabled, recognized barcodes of other compatible or equivalent types are filtered out. Default value is false. Example:

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

Returns only barcode types explicitly specified for recognition. When enabled, recognized barcodes of other compatible or equivalent types are filtered out. Default value is false. Example:

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `` |  |

### BarcodeSettings.strip_fnc {#strip_fnc}

**Type:** `bool`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `bool` |  |

