---
title: "PrimaryData"
linktitle: "PrimaryData"
second_title: "Aspose.BarCode for Python via Java"
description: "Class for storing HIBC LIC primary data."
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/primarydata/
---

## PrimaryData class

**Module:** `aspose_barcode.complex_barcode.primary_data`


Class for storing HIBC LIC primary data.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__eq__](#__eq__) | `bool` | No | Returns a value indicating whether this instance is equal to a specified PrimaryData value. |
| [__hash__](#__hash__) | `int` | No | Returns the hash code for the current instance. |
| [__str__](#__str__) | `str` | No | Converts data to string format according HIBC LIC specification. |
| [parse_from_string](#parse_from_string) | `None` | No | Instantiates primary data from string format according HIBC LIC specification. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [labeler_identification_code](#labeler_identification_code) | `Optional[str]` | Gets the identification date of the labeler identification code. Labeler identification code must be 4 symbols alphanumeric string, with first character always being alphabetic. |
| [product_or_catalog_number](#product_or_catalog_number) | `Optional[str]` | Identifies product or catalog number. |
| [unit_of_measure_id](#unit_of_measure_id) | `int` | Identifies unit of measure ID. |

### PrimaryData Constructor {#constructor}

```python
__init__(self)
```

### PrimaryData.__eq__ {#__eq__}

```python
__eq__(self, PrimaryData other) -> bool
```

Returns a value indicating whether this instance is equal to a specified PrimaryData value.

| Parameter | Type | Description |
| --- | --- | --- |
| `other` | `PrimaryData` |  |

**Return Type:** `bool` — True if obj has the same value as this instance; otherwise, False.

### PrimaryData.__hash__ {#__hash__}

```python
__hash__(self) -> int
```

Returns the hash code for the current instance.

**Return Type:** `int` — A hash code for the current object.

### PrimaryData.__str__ {#__str__}

```python
__str__(self) -> str
```

Converts data to string format according HIBC LIC specification.

**Return Type:** `str` — Formatted string.

### PrimaryData.parse_from_string {#parse_from_string}

```python
parse_from_string(self, str primary_data_codetext)
```

Instantiates primary data from string format according HIBC LIC specification.

| Parameter | Type | Description |
| --- | --- | --- |
| `primary_data_codetext` | `str` |  |

### PrimaryData.labeler_identification_code {#labeler_identification_code}

**Type:** `Optional[str]`

Gets the identification date of the labeler identification code. Labeler identification code must be 4 symbols alphanumeric string, with first character always being alphabetic.

Sets the identification date for the labeler code. Labeler identification code must be 4 symbols alphanumeric string, with first character always being alphabetic.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### PrimaryData.product_or_catalog_number {#product_or_catalog_number}

**Type:** `Optional[str]`

Identifies product or catalog number.

Identifies product or catalog number.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### PrimaryData.unit_of_measure_id {#unit_of_measure_id}

**Type:** `int`

Identifies unit of measure ID.

Identifies unit of measure ID.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

