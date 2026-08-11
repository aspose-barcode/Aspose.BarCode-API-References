---
title: "AlternativeScheme"
linktitle: "AlternativeScheme"
second_title: "Aspose.BarCode for Python via Java"
description: "Alternative payment scheme instructions."
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/alternativescheme/
---

## AlternativeScheme class

**Module:** `aspose_barcode.complex_barcode.alternative_scheme`


Alternative payment scheme instructions.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__eq__](#__eq__) | `bool` | No | Determines whether the specified object is equal to the current object. |
| [__hash__](#__hash__) | `int` | No | Returns the hash code for the current instance. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [instruction](#instruction) | `Optional[str]` | Gets the payment instruction for a given bill. The instruction consists of a two letter abbreviation for the scheme, a separator characters and a sequence of parameters(separated by the character at index 2). |

### AlternativeScheme Constructor {#constructor}

```python
__init__(self, str instruction)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `instruction` | `str` |  |

### AlternativeScheme.__eq__ {#__eq__}

```python
__eq__(self, AlternativeScheme other) -> bool
```

Determines whether the specified object is equal to the current object.

| Parameter | Type | Description |
| --- | --- | --- |
| `other` | `AlternativeScheme` |  |

**Return Type:** `bool` — True if the specified object is equal to the current object; otherwise, false.

### AlternativeScheme.__hash__ {#__hash__}

```python
__hash__(self) -> int
```

Returns the hash code for the current instance.

**Return Type:** `int` — a hash code for the current object.

### AlternativeScheme.instruction {#instruction}

**Type:** `Optional[str]`

Gets the payment instruction for a given bill. The instruction consists of a two letter abbreviation for the scheme, a separator characters and a sequence of parameters(separated by the character at index 2).

**Returns:** The payment instruction.

Gets the payment instruction for a given bill. The instruction consists of a two letter abbreviation for the scheme, a separator characters and a sequence of parameters(separated by the character at index 2).

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

