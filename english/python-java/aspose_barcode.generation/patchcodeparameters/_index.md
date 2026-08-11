---
title: "PatchCodeParameters"
linktitle: "PatchCodeParameters"
second_title: "Aspose.BarCode for Python via Java"
description: "PatchCode parameters."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/patchcodeparameters/
---

## PatchCodeParameters class

**Module:** `aspose_barcode.generation.patch_code_parameters`


PatchCode parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__str__](#__str__) | `str` | No | Returns a human-readable string representation of this PatchCodeParameters. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [extra_barcode_text](#extra_barcode_text) | `str` | Specifies codetext for an extra QR barcode, when PatchCode is generated in page mode. |
| [format](#format) | `PatchFormat` |  |
| [patch_format](#patch_format) | `PatchFormat` | PatchCode format. Choose PatchOnly to generate single PatchCode. Use page format to generate Patch page with PatchCodes as borders. Default value: PatchFormat.PATCH_ONLY |

### PatchCodeParameters Constructor {#constructor}

```python
__init__(self, _java_class)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `_java_class` | `` |  |

### PatchCodeParameters.__str__ {#__str__}

```python
__str__(self) -> str
```

Returns a human-readable string representation of this PatchCodeParameters.

**Return Type:** `str` — A string that represents this PatchCodeParameters.

### PatchCodeParameters.extra_barcode_text {#extra_barcode_text}

**Type:** `str`

Specifies codetext for an extra QR barcode, when PatchCode is generated in page mode.

Specifies codetext for an extra QR barcode, when PatchCode is generated in page mode.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### PatchCodeParameters.format {#format}

**Type:** `PatchFormat`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `PatchFormat` |  |

### PatchCodeParameters.patch_format {#patch_format}

**Type:** `PatchFormat`

PatchCode format. Choose PatchOnly to generate single PatchCode. Use page format to generate Patch page with PatchCodes as borders. Default value: PatchFormat.PATCH_ONLY

**Returns:** PatchFormat

PatchCode format. Choose PatchOnly to generate single PatchCode. Use page format to generate Patch page with PatchCodes as borders. Default value: PatchFormat.PATCH_ONLY

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `PatchFormat` |  |

