---
title: "HslaColor"
linktitle: "HslaColor"
second_title: "Aspose.BarCode for Python via Java"
description: "Class for representing HSLA color (Hue, Saturation, Lightness, Alpha)"
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/hslacolor/
---

## HslaColor class

**Module:** `aspose_barcode.generation.hsla_color`


Class for representing HSLA color (Hue, Saturation, Lightness, Alpha)


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) | Constructor for HslaColor. |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [check_alpha](#check_alpha) | `None` | Yes |  |
| [check_hue](#check_hue) | `None` | Yes |  |
| [check_sat_light](#check_sat_light) | `None` | Yes |  |
| [convert_hsla_to_rgba](#convert_hsla_to_rgba) | `Tuple[int, int, int, int]` | Yes |  |
| [hue_to_rgb](#hue_to_rgb) | `float` | Yes |  |

### HslaColor Constructor {#constructor}

```python
__init__(self, int h, int s, int l, float a)
```

Constructor for HslaColor.

| Parameter | Type | Description |
| --- | --- | --- |
| `h` | `int` | Hue [0, 360] |
| `s` | `int` | Saturation [0, 100] |
| `l` | `int` | Lightness [0, 100] |
| `a` | `float` | Alpha (opacity) [0.0f, 1.0f] |

### HslaColor.check_alpha (static) {#check_alpha}

```python
check_alpha(float value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `float` |  |

### HslaColor.check_hue (static) {#check_hue}

```python
check_hue(int value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### HslaColor.check_sat_light (static) {#check_sat_light}

```python
check_sat_light(int value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### HslaColor.convert_hsla_to_rgba (static) {#convert_hsla_to_rgba}

```python
convert_hsla_to_rgba(HslaColor hsla_color) -> Tuple[int, int, int, int]
```

| Parameter | Type | Description |
| --- | --- | --- |
| `hsla_color` | `HslaColor` |  |

**Return Type:** `Tuple[int, int, int, int]`

### HslaColor.hue_to_rgb (static) {#hue_to_rgb}

```python
hue_to_rgb(float p, float q, float t) -> float
```

| Parameter | Type | Description |
| --- | --- | --- |
| `p` | `float` |  |
| `q` | `float` |  |
| `t` | `float` |  |

**Return Type:** `float`

