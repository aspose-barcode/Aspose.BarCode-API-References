---
title: "Quadrangle"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode for PHP via Java"
description: "Stores a set of four Points that represent a Quadrangle region."
type: docs
weight: 10
url: /php/aspose.barcode.recognition/quadrangle/
---

## Quadrangle class

**Namespace:** `Aspose.Barcode.Recognition`


Stores a set of four Points that represent a Quadrangle region.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) | Initializes a new instance of the Quadrangle structure with the describing points. |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [construct](#construct) | Yes |  |
| [containsCoordinates](#containscoordinates) | No | Determines if the specified point is contained within this Quadrangle structure. |
| [containsPoint](#containspoint) | No | Determines if the specified Point is contained within this Quadrangle structure. |
| [containsQuadrangle](#containsquadrangle) | No | Determines if the specified Quadrangle is contained or intersect this Quadrangle structure. |
| [containsRectangle](#containsrectangle) | No | Determines if the specified Rectangle is contained or intersect this Quadrangle structure. |
| [EMPTY](#empty) | Yes | Represents a Quadrangle structure with its properties left uninitialized.Value: Quadrangle |
| [isEmpty](#isempty) | No | Tests whether all Points of this Quadrangle have values of zero.Value: Returns true if all Points of this Quadrangle have values of zero; otherwise, false. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [BoundingRectangle](#boundingrectangle) | Read-only | Creates Rectangle bounding this Quadrangle |
| [LeftBottom](#leftbottom) | Read/Write | Gets left-bottom corner Point of Quadrangle regionValue: A left-bottom corner Point of Quadrangle region |
| [LeftTop](#lefttop) | Read/Write | Gets left-top corner Point of Quadrangle regionValue: A left-top corner Point of Quadrangle region |
| [RightBottom](#rightbottom) | Read/Write | Gets right-bottom corner Point of Quadrangle regionValue: A right-bottom corner Point of Quadrangle region |
| [RightTop](#righttop) | Read/Write | Gets right-top corner Point of Quadrangle regionValue: A right-top corner Point of Quadrangle region |

### Quadrangle__construct(Point $leftTop, Point $rightTop, Point $rightBottom, Point $leftBottom) {#constructor}

Initializes a new instance of the Quadrangle structure with the describing points.

| Parameter | Type | Description |
| --- | --- | --- |
| `$leftTop` | `Point` |  |
| `$rightTop` | `Point` |  |
| `$rightBottom` | `Point` |  |
| `$leftBottom` | `Point` |  |

### constructconstruct(QuadrangleDTO $quadrangleDTO) (static) {#construct}

| Parameter | Type | Description |
| --- | --- | --- |
| `$quadrangleDTO` | `QuadrangleDTO` |  |

### containsCoordinatescontainsCoordinates(int $x, int $y) {#containscoordinates}

Determines if the specified point is contained within this Quadrangle structure.

| Parameter | Type | Description |
| --- | --- | --- |
| `$x` | `int` |  |
| `$y` | `int` |  |

**Returns:** bool Returns true if point is contained within this Quadrangle structure; otherwise, false.

### containsPointcontainsPoint(Point $pt) {#containspoint}

Determines if the specified Point is contained within this Quadrangle structure.

| Parameter | Type | Description |
| --- | --- | --- |
| `$pt` | `Point` |  |

**Returns:** bool Returns true if Point is contained within this Quadrangle structure; otherwise, false.

### containsQuadranglecontainsQuadrangle(Quadrangle $quad) {#containsquadrangle}

Determines if the specified Quadrangle is contained or intersect this Quadrangle structure.

| Parameter | Type | Description |
| --- | --- | --- |
| `$quad` | `Quadrangle` |  |

**Returns:** bool Returns true if Quadrangle is contained or intersect this Quadrangle structure; otherwise, false.

### containsRectanglecontainsRectangle(Rectangle $rect) {#containsrectangle}

Determines if the specified Rectangle is contained or intersect this Quadrangle structure.

| Parameter | Type | Description |
| --- | --- | --- |
| `$rect` | `Rectangle` |  |

**Returns:** bool Returns true if Rectangle is contained or intersect this Quadrangle structure; otherwise, false.

### EMPTYEMPTY() (static) {#empty}

Represents a Quadrangle structure with its properties left uninitialized.Value: Quadrangle

### isEmptyisEmpty() {#isempty}

Tests whether all Points of this Quadrangle have values of zero.Value: Returns true if all Points of this Quadrangle have values of zero; otherwise, false.

### BoundingRectangle {#boundingrectangle}

**Access:** Read-only

**Returns:** Rectangle returns Rectangle bounding this Quadrangle

Creates Rectangle bounding this Quadrangle

### LeftBottom {#leftbottom}

**Access:** Read/Write

Gets left-bottom corner Point of Quadrangle regionValue: A left-bottom corner Point of Quadrangle region

Gets left-bottom corner Point of Quadrangle regionValue: A left-bottom corner Point of Quadrangle region

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `Point` |  |

### LeftTop {#lefttop}

**Access:** Read/Write

Gets left-top corner Point of Quadrangle regionValue: A left-top corner Point of Quadrangle region

Gets left-top corner Point of Quadrangle regionValue: A left-top corner Point of Quadrangle region

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `Point` |  |

### RightBottom {#rightbottom}

**Access:** Read/Write

Gets right-bottom corner Point of Quadrangle regionValue: A right-bottom corner Point of Quadrangle region

Gets right-bottom corner Point of Quadrangle regionValue: A right-bottom corner Point of Quadrangle region

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `Point` |  |

### RightTop {#righttop}

**Access:** Read/Write

Gets right-top corner Point of Quadrangle regionValue: A right-top corner Point of Quadrangle region

Gets right-top corner Point of Quadrangle regionValue: A right-top corner Point of Quadrangle region

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `Point` |  |

