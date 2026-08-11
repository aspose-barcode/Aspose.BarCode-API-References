---
title: "Quadrangle"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode for Python via Java"
description: "Stores a set of four Points that represent a Quadrangle region."
type: docs
weight: 10
url: /python-java/aspose_barcode.recognition/quadrangle/
---

## Quadrangle class

**Module:** `aspose_barcode.recognition.quadrangle`


Stores a set of four Points that represent a Quadrangle region.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) | Initializes a new instance of the Quadrangle structure with the describing points. |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__eq__](#__eq__) | `bool` | No | Returns a value indicating whether this instance is equal to a specified Quadrangle value. |
| [__hash__](#__hash__) | `int` | No | Returns the hash code for the current instance. |
| [__str__](#__str__) | `str` | No | Returns a human-readable string representation of this Quadrangle. |
| [bounding_rectangle](#bounding_rectangle) | `RectLike` | No |  |
| [contains](#contains) | `bool` | No |  |
| [contains_point](#contains_point) | `bool` | No |  |
| [contains_quadrangle](#contains_quadrangle) | `bool` | No |  |
| [contains_rectangle](#contains_rectangle) | `bool` | No |  |
| [empty](#empty) | `Quadrangle` | Yes | Represents a Quadrangle structure with its properties set to (0,0). |
| [is_empty](#is_empty) | `bool` | No |  |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [left_bottom](#left_bottom) | `PointLike` |  |
| [left_top](#left_top) | `PointLike` |  |
| [right_bottom](#right_bottom) | `PointLike` |  |
| [right_top](#right_top) | `PointLike` |  |

### Quadrangle Constructor {#constructor}

```python
__init__(self, PointLike left_top, PointLike right_top, PointLike right_bottom, PointLike left_bottom) -> def
```

Initializes a new instance of the Quadrangle structure with the describing points.

| Parameter | Type | Description |
| --- | --- | --- |
| `left_top` | `PointLike` |  |
| `right_top` | `PointLike` |  |
| `right_bottom` | `PointLike` |  |
| `left_bottom` | `PointLike` |  |

### Quadrangle.__eq__ {#__eq__}

```python
__eq__(self, Quadrangle other) -> bool
```

Returns a value indicating whether this instance is equal to a specified Quadrangle value.

| Parameter | Type | Description |
| --- | --- | --- |
| `other` | `Quadrangle` |  |

**Return Type:** `bool` — true if obj has the same value as this instance otherwise, false.

### Quadrangle.__hash__ {#__hash__}

```python
__hash__(self) -> int
```

Returns the hash code for the current instance.

**Return Type:** `int` — A hash code for the current object.

### Quadrangle.__str__ {#__str__}

```python
__str__(self) -> str
```

Returns a human-readable string representation of this Quadrangle.

**Return Type:** `str` — A string that represents this Quadrangle.

### Quadrangle.bounding_rectangle {#bounding_rectangle}

```python
bounding_rectangle(self) -> RectLike
```

**Return Type:** `RectLike`

### Quadrangle.contains {#contains}

```python
contains(self, Union[PointLike, Quadrangle, RectLike, tuple[int, int]] obj) -> bool
```

| Parameter | Type | Description |
| --- | --- | --- |
| `obj` | `Union[PointLike, Quadrangle, RectLike, tuple[int, int]]` |  |

**Return Type:** `bool`

### Quadrangle.contains_point {#contains_point}

```python
contains_point(self, int x, int y) -> bool
```

| Parameter | Type | Description |
| --- | --- | --- |
| `x` | `int` |  |
| `y` | `int` |  |

**Return Type:** `bool`

### Quadrangle.contains_quadrangle {#contains_quadrangle}

```python
contains_quadrangle(self, Quadrangle quad) -> bool
```

| Parameter | Type | Description |
| --- | --- | --- |
| `quad` | `Quadrangle` |  |

**Return Type:** `bool`

### Quadrangle.contains_rectangle {#contains_rectangle}

```python
contains_rectangle(self, RectLike rect) -> bool
```

| Parameter | Type | Description |
| --- | --- | --- |
| `rect` | `RectLike` |  |

**Return Type:** `bool`

### Quadrangle.empty (static) {#empty}

```python
empty() -> Quadrangle
```

Represents a Quadrangle structure with its properties set to (0,0).

**Return Type:** `Quadrangle`

### Quadrangle.is_empty {#is_empty}

```python
is_empty(self) -> bool
```

**Return Type:** `bool`

### Quadrangle.left_bottom {#left_bottom}

**Type:** `PointLike`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `PointLike` |  |

### Quadrangle.left_top {#left_top}

**Type:** `PointLike`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `PointLike` |  |

### Quadrangle.right_bottom {#right_bottom}

**Type:** `PointLike`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `PointLike` |  |

### Quadrangle.right_top {#right_top}

**Type:** `PointLike`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `PointLike` |  |

