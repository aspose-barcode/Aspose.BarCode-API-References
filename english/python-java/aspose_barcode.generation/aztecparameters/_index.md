---
title: "AztecParameters"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode for Python via Java"
description: "Aztec parameters."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/aztecparameters/
---

## AztecParameters class

**Module:** `aspose_barcode.generation.aztec_parameters`


Aztec parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__str__](#__str__) | `str` | No | Returns a human-readable string representation of this. . |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [aspect_ratio](#aspect_ratio) | `float` | Height/Width ratio of 2D BarCode module. |
| [aztec_encode_mode](#aztec_encode_mode) | `AztecEncodeMode` | Gets a Aztec encode mode. Default value: Auto. |
| [aztec_error_level](#aztec_error_level) | `int` | Level of error correction of Aztec types of barcode. Value should between 5 to 95. |
| [aztec_symbol_mode](#aztec_symbol_mode) | `AztecSymbolMode` | Gets a Aztec Symbol mode. Default value: AztecSymbolMode.Auto. |
| [eci_encoding](#eci_encoding) | `ECIEncodings` |  |
| [encode_mode](#encode_mode) | `AztecEncodeMode` |  |
| [error_level](#error_level) | `int` |  |
| [layers_count](#layers_count) | `int` | Gets layers count of Aztec symbol. Layers count should be in range from 1 to 3 for Compact mode and in range from 1 to 32 for Full Range mode. Default value: 0 (auto). |
| [reader_initialization](#reader_initialization) | `bool` | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [structured_append_barcode_id](#structured_append_barcode_id) | `int` |  |
| [structured_append_barcodes_count](#structured_append_barcodes_count) | `int` |  |
| [structured_append_file_id](#structured_append_file_id) | `Optional[str]` |  |
| [symbol_mode](#symbol_mode) | `AztecSymbolMode` |  |

### AztecParameters Constructor {#constructor}

```python
__init__(self, _java_class)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `_java_class` | `` |  |

### AztecParameters.__str__ {#__str__}

```python
__str__(self) -> str
```

Returns a human-readable string representation of this. .

**Return Type:** `str` — A string that represents thisAztecParameters .

### AztecParameters.aspect_ratio {#aspect_ratio}

**Type:** `float`

Height/Width ratio of 2D BarCode module.

Height/Width ratio of 2D BarCode module.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `float` |  |

### AztecParameters.aztec_encode_mode {#aztec_encode_mode}

**Type:** `AztecEncodeMode`

Gets a Aztec encode mode. Default value: Auto.

Gets a Aztec encode mode. Default value: Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `AztecEncodeMode` |  |

### AztecParameters.aztec_error_level {#aztec_error_level}

**Type:** `int`

Level of error correction of Aztec types of barcode. Value should between 5 to 95.

Level of error correction of Aztec types of barcode. Value should between 5 to 95.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### AztecParameters.aztec_symbol_mode {#aztec_symbol_mode}

**Type:** `AztecSymbolMode`

Gets a Aztec Symbol mode. Default value: AztecSymbolMode.Auto.

Gets a Aztec Symbol mode. Default value: AztecSymbolMode.Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `AztecSymbolMode` |  |

### AztecParameters.eci_encoding {#eci_encoding}

**Type:** `ECIEncodings`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `ECIEncodings` |  |

### AztecParameters.encode_mode {#encode_mode}

**Type:** `AztecEncodeMode`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `AztecEncodeMode` |  |

### AztecParameters.error_level {#error_level}

**Type:** `int`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### AztecParameters.layers_count {#layers_count}

**Type:** `int`

Gets layers count of Aztec symbol. Layers count should be in range from 1 to 3 for Compact mode and in range from 1 to 32 for Full Range mode. Default value: 0 (auto).

Gets layers count of Aztec symbol. Layers count should be in range from 1 to 3 for Compact mode and in range from 1 to 32 for Full Range mode. Default value: 0 (auto).

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### AztecParameters.reader_initialization {#reader_initialization}

**Type:** `bool`

Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization.

Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `bool` |  |

### AztecParameters.structured_append_barcode_id {#structured_append_barcode_id}

**Type:** `int`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### AztecParameters.structured_append_barcodes_count {#structured_append_barcodes_count}

**Type:** `int`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### AztecParameters.structured_append_file_id {#structured_append_file_id}

**Type:** `Optional[str]`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### AztecParameters.symbol_mode {#symbol_mode}

**Type:** `AztecSymbolMode`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `AztecSymbolMode` |  |

