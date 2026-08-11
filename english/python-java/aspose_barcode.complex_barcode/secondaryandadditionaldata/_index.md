---
title: "SecondaryAndAdditionalData"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for Python via Java"
description: "Class for storing HIBC LIC secondary and additional data."
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

**Module:** `aspose_barcode.complex_barcode.secondary_and_additional_data`


Class for storing HIBC LIC secondary and additional data.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__eq__](#__eq__) | `bool` | No | Returns a value indicating whether this instance is equal to a specified SecondaryAndAdditionalData value. |
| [__hash__](#__hash__) | `int` | No | Returns the hash code for the current instance. |
| [__str__](#__str__) | `str` | No | Converts data to string format according HIBC LIC specification. |
| [parse_from_string](#parse_from_string) | `None` | No | Instantiates secondary and additional supplemental data from string format according HIBC LIC specification. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [date_of_manufacture](#date_of_manufacture) | `datetime` | Identifies date of manufacture. Date of manufacture can be set to DateTime.MinValue in order not to use this field. Default value: DateTime.MinValue |
| [expiry_date](#expiry_date) | `datetime` | Identifies expiry date format. |
| [expiry_date_format](#expiry_date_format) | `HIBCLICDateFormat` | Identifies expiry date format. |
| [lot_number](#lot_number) | `Optional[str]` | Identifies lot or batch number. Lot/batch number must be alphanumeric string with up to 18 sybmols length. |
| [quantity](#quantity) | `int` | Identifies quantity, must be integer value from 0 to 500. Quantity can be set to -1 in order not to use this field. Default value: -1 |
| [serial_number](#serial_number) | `Optional[str]` | Identifies serial number. Serial number must be alphanumeric string up to 18 sybmols length. |

### SecondaryAndAdditionalData Constructor {#constructor}

```python
__init__(self)
```

### SecondaryAndAdditionalData.__eq__ {#__eq__}

```python
__eq__(self, SecondaryAndAdditionalData other) -> bool
```

Returns a value indicating whether this instance is equal to a specified SecondaryAndAdditionalData value.

| Parameter | Type | Description |
| --- | --- | --- |
| `other` | `SecondaryAndAdditionalData` |  |

**Return Type:** `bool` — True if obj has the same value as this instance; otherwise, False.

### SecondaryAndAdditionalData.__hash__ {#__hash__}

```python
__hash__(self) -> int
```

Returns the hash code for the current instance.

**Return Type:** `int` — A hash code for the current object.

### SecondaryAndAdditionalData.__str__ {#__str__}

```python
__str__(self) -> str
```

Converts data to string format according HIBC LIC specification.

**Return Type:** `str` — Formatted string.

### SecondaryAndAdditionalData.parse_from_string {#parse_from_string}

```python
parse_from_string(self, str secondary_data_codetext)
```

Instantiates secondary and additional supplemental data from string format according HIBC LIC specification.

| Parameter | Type | Description |
| --- | --- | --- |
| `secondary_data_codetext` | `str` |  |

### SecondaryAndAdditionalData.date_of_manufacture {#date_of_manufacture}

**Type:** `datetime`

Identifies date of manufacture. Date of manufacture can be set to DateTime.MinValue in order not to use this field. Default value: DateTime.MinValue

Identifies date of manufacture. Date of manufacture can be set to DateTime.MinValue in order not to use this field. Default value: DateTime.MinValue

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `datetime` |  |

### SecondaryAndAdditionalData.expiry_date {#expiry_date}

**Type:** `datetime`

Identifies expiry date format.

Identifies expiry date format.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `datetime` |  |

### SecondaryAndAdditionalData.expiry_date_format {#expiry_date_format}

**Type:** `HIBCLICDateFormat`

Identifies expiry date format.

Identifies expiry date format.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `HIBCLICDateFormat` |  |

### SecondaryAndAdditionalData.lot_number {#lot_number}

**Type:** `Optional[str]`

Identifies lot or batch number. Lot/batch number must be alphanumeric string with up to 18 sybmols length.

Identifies lot or batch number. Lot/batch number must be alphanumeric string with up to 18 sybmols length.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Optional[str]` |  |

### SecondaryAndAdditionalData.quantity {#quantity}

**Type:** `int`

Identifies quantity, must be integer value from 0 to 500. Quantity can be set to -1 in order not to use this field. Default value: -1

Identifies quantity, must be integer value from 0 to 500. Quantity can be set to -1 in order not to use this field. Default value: -1

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### SecondaryAndAdditionalData.serial_number {#serial_number}

**Type:** `Optional[str]`

Identifies serial number. Serial number must be alphanumeric string up to 18 sybmols length.

Identifies serial number. Serial number must be alphanumeric string up to 18 sybmols length.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Optional[str]` |  |

