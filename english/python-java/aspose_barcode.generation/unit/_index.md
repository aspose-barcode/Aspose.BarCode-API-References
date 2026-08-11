---
title: "Unit"
linktitle: "Unit"
second_title: "Aspose.BarCode for Python via Java"
description: "Specifies the size value in different units (Pixel, Inches, etc.). This sample shows how to create and save a BarCode image."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/unit/
---

## Unit class

**Module:** `aspose_barcode.generation.unit`


Specifies the size value in different units (Pixel, Inches, etc.). This sample shows how to create and save a BarCode image.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__eq__](#__eq__) | `bool` | No | Determines whether this instance and a specified object, which must also be a Unit object, have the same value. |
| [__hash__](#__hash__) | `int` | No | Returns the hash code for the current instance. |
| [__str__](#__str__) | `str` | No | Returns a human-readable string representation of this Unit. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [document](#document) | `float` | Gets size value in document units. |
| [inches](#inches) | `float` | Gets size value in inches. |
| [millimeters](#millimeters) | `float` | Gets size value in millimeters. |
| [pixels](#pixels) | `float` | Gets size value in pixels. |
| [point](#point) | `float` | Gets size value in point. |

### Unit Constructor {#constructor}

```python
__init__(self, Union[Unit, Any] source)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `source` | `Union[Unit, Any]` |  |

### Unit.__eq__ {#__eq__}

```python
__eq__(self, Optional[Unit] other) -> bool
```

Determines whether this instance and a specified object, which must also be a Unit object, have the same value.

| Parameter | Type | Description |
| --- | --- | --- |
| `other` | `Optional[Unit]` | The Unit to compare to this instance. |

**Return Type:** `bool` — True if other is a Unit and its value is the same as this instance, otherwise False. If other is None, the method returns false.

### Unit.__hash__ {#__hash__}

```python
__hash__(self) -> int
```

Returns the hash code for the current instance.

**Return Type:** `int` — A hash code for the current object.

### Unit.__str__ {#__str__}

```python
__str__(self) -> str
```

Returns a human-readable string representation of this Unit.

**Return Type:** `str` — A string that represents this Unit.

### Unit.document {#document}

**Type:** `float`

Gets size value in document units.

Sets size value in document units.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `float` |  |

### Unit.inches {#inches}

**Type:** `float`

Gets size value in inches.

Sets size value in inches.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `float` |  |

### Unit.millimeters {#millimeters}

**Type:** `float`

Gets size value in millimeters.

Sets size value in millimeters.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `float` |  |

### Unit.pixels {#pixels}

**Type:** `float`

Gets size value in pixels.

Sets size value in pixels.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `float` |  |

### Unit.point {#point}

**Type:** `float`

Gets size value in point.

Sets size value in point.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `float` |  |

