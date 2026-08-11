---
title: "FontUnit"
linktitle: "FontUnit"
second_title: "Aspose.BarCode for Python via Java"
description: "Defines a particular format for text, including font face, size, and style attributes where size in Unit value property. This sample shows how to create and sav"
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/fontunit/
---

## FontUnit class

**Module:** `aspose_barcode.generation.font_unit`


Defines a particular format for text, including font face, size, and style attributes where size in Unit value property. This sample shows how to create and save a BarCode image.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__str__](#__str__) | `str` | No | String representation of the FontUnit object. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [family_name](#family_name) | `str` | Gets the face name of this Font. |
| [size](#size) | `Optional[Unit]` | Gets size of this FontUnit in Unit value. Raises: IllegalArgumentException: if the Size parameter value is less than or equal to 0. |
| [style](#style) | `FontStyle` | Gets style information for this FontUnit. |

### FontUnit Constructor {#constructor}

```python
__init__(self, Union[FontUnit, Any] source)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `source` | `Union[FontUnit, Any]` |  |

### FontUnit.__str__ {#__str__}

```python
__str__(self) -> str
```

String representation of the FontUnit object.

**Return Type:** `str`

### FontUnit.family_name {#family_name}

**Type:** `str`

Gets the face name of this Font.

Sets the face name of this Font.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### FontUnit.size {#size}

**Type:** `Optional[Unit]`

Gets size of this FontUnit in Unit value. Raises: IllegalArgumentException: if the Size parameter value is less than or equal to 0.

Sets size of this FontUnit in Unit value. Raises: IllegalArgumentException: if the Size parameter value is less than or equal to 0.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Unit` |  |

### FontUnit.style {#style}

**Type:** `FontStyle`

Gets style information for this FontUnit.

Sets style information for this FontUnit.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `FontStyle` |  |

