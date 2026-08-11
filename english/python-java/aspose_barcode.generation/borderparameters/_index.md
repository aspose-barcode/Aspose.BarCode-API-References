---
title: "BorderParameters"
linktitle: "BorderParameters"
second_title: "Aspose.BarCode for Python via Java"
description: "Barcode image border parameters."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/borderparameters/
---

## BorderParameters class

**Module:** `aspose_barcode.generation.border_parameters`


Barcode image border parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__str__](#__str__) | `str` | No | Returns a human-readable string representation of this BorderParameters instance. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [color](#color) | `Tuple[int, int, int]` | Border color, representation of an RGB tuple. Default value: 0 |
| [dash_style](#dash_style) | `BorderDashStyle` | Border dash style. Default value: BorderDashStyle.SOLID. |
| [visible](#visible) | `bool` | Border visibility. If false, the Width parameter is always ignored (0). Default value: false. |
| [width](#width) | `Unit` | Border width. Default value: 0. Ignored if Visible is set to false. |

### BorderParameters Constructor {#constructor}

```python
__init__(self, _java_class) -> def
```

| Parameter | Type | Description |
| --- | --- | --- |
| `_java_class` | `` |  |

### BorderParameters.__str__ {#__str__}

```python
__str__(self) -> str
```

Returns a human-readable string representation of this BorderParameters instance.

**Return Type:** `str`

### BorderParameters.color {#color}

**Type:** `Tuple[int, int, int]`

Border color, representation of an RGB tuple. Default value: 0

Border color, representation of an RGB tuple. Default value: 0

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Tuple[int, int, int]` |  |

### BorderParameters.dash_style {#dash_style}

**Type:** `BorderDashStyle`

Border dash style. Default value: BorderDashStyle.SOLID.

Border dash style. Default value: BorderDashStyle.SOLID.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `BorderDashStyle` |  |

### BorderParameters.visible {#visible}

**Type:** `bool`

Border visibility. If false, the Width parameter is always ignored (0). Default value: false.

Border visibility. If false, the Width parameter is always ignored (0). Default value: false.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `bool` |  |

### BorderParameters.width {#width}

**Type:** `Unit`

Border width. Default value: 0. Ignored if Visible is set to false.

Border width. Default value: 0. Ignored if Visible is set to false.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Unit` |  |

