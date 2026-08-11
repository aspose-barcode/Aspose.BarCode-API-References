---
title: "DotCodeParameters"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode for Python via Java"
description: "DotCode parameters."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/dotcodeparameters/
---

## DotCodeParameters class

**Module:** `aspose_barcode.generation.dotcode_parameters`


DotCode parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__str__](#__str__) | `str` | No | Returns a human-readable string representation of this DotCodeParameters. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [aspect_ratio](#aspect_ratio) | `float` | Height/Width ratio of 2D BarCode module. |
| [columns](#columns) | `int` | Identifies columns count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of columns must be at least 5. Default value: -1 |
| [dot_code_encode_mode](#dot_code_encode_mode) | `DotCodeEncodeMode` | Identifies DotCode encode mode. Default value: Auto. |
| [dot_code_structured_append_mode_barcode_id](#dot_code_structured_append_mode_barcode_id) | `int` | Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. |
| [dot_code_structured_append_mode_barcodes_count](#dot_code_structured_append_mode_barcodes_count) | `int` | Identifies DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. |
| [eci_encoding](#eci_encoding) | `ECIEncodings` | Identifies ECI encoding. Used when DotCodeEncodeMode is Auto. Default value: ISO-8859-1 |
| [encode_mode](#encode_mode) | `DotCodeEncodeMode` |  |
| [reader_initialization](#reader_initialization) | `bool` | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false. |
| [rows](#rows) | `int` | Identifies rows count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of rows must be at least 5. Default value: -1 |
| [structured_append_mode_barcode_id](#structured_append_mode_barcode_id) | `int` |  |
| [structured_append_mode_barcodes_count](#structured_append_mode_barcodes_count) | `int` |  |

### DotCodeParameters Constructor {#constructor}

```python
__init__(self, _java_class)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `_java_class` | `` |  |

### DotCodeParameters.__str__ {#__str__}

```python
__str__(self) -> str
```

Returns a human-readable string representation of this DotCodeParameters.

**Return Type:** `str` — A string that represents this DotCodeParameters.

### DotCodeParameters.aspect_ratio {#aspect_ratio}

**Type:** `float`

Height/Width ratio of 2D BarCode module.

Height/Width ratio of 2D BarCode module.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `float` |  |

### DotCodeParameters.columns {#columns}

**Type:** `int`

Identifies columns count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of columns must be at least 5. Default value: -1

Identifies columns count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of columns must be at least 5. Default value: -1

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### DotCodeParameters.dot_code_encode_mode {#dot_code_encode_mode}

**Type:** `DotCodeEncodeMode`

Identifies DotCode encode mode. Default value: Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `DotCodeEncodeMode` |  |

### DotCodeParameters.dot_code_structured_append_mode_barcode_id {#dot_code_structured_append_mode_barcode_id}

**Type:** `int`

Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1.

Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### DotCodeParameters.dot_code_structured_append_mode_barcodes_count {#dot_code_structured_append_mode_barcodes_count}

**Type:** `int`

Identifies DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35.

Identifies DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### DotCodeParameters.eci_encoding {#eci_encoding}

**Type:** `ECIEncodings`

Identifies ECI encoding. Used when DotCodeEncodeMode is Auto. Default value: ISO-8859-1

Identifies ECI encoding. Used when DotCodeEncodeMode is Auto. Default value: ISO-8859-1

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `ECIEncodings` |  |

### DotCodeParameters.encode_mode {#encode_mode}

**Type:** `DotCodeEncodeMode`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `DotCodeEncodeMode` |  |

### DotCodeParameters.reader_initialization {#reader_initialization}

**Type:** `bool`

Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false.

Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `bool` |  |

### DotCodeParameters.rows {#rows}

**Type:** `int`

Identifies rows count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of rows must be at least 5. Default value: -1

Identifies rows count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of rows must be at least 5. Default value: -1

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### DotCodeParameters.structured_append_mode_barcode_id {#structured_append_mode_barcode_id}

**Type:** `int`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### DotCodeParameters.structured_append_mode_barcodes_count {#structured_append_mode_barcodes_count}

**Type:** `int`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

