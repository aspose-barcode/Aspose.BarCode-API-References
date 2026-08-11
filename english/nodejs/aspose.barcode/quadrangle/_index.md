---
title: "Quadrangle"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Stores a set of four Points that represent a Quadrangle region."
type: docs
weight: 850
url: /nodejs/aspose.barcode/quadrangle/
---

## Quadrangle class

Stores a set of four Points that represent a Quadrangle region.

```js
new Quadrangle(leftTop, rightTop, rightBottom, leftBottom)
```

Initializes a new instance of the Quadrangle structure with the describing points.

| Parameter | Description |
| --- | --- |
| leftTop | A Point that represents the left-top corner of the Quadrangle. |
| rightTop | A Point that represents the right-top corner of the Quadrangle. |
| rightBottom | A Point that represents the right-bottom corner of the Quadrangle. |
| leftBottom | A Point that represents the left-bottom corner of the Quadrangle. |

## Methods

| Name | Description |
| --- | --- |
| [contains(pt)](#contains) | Determines if the specified Point is contained within this Quadrangle structure. |
| [containsPoint(x, y)](#containspoint) | Determines if the specified point is contained within this Quadrangle structure. |
| [containsQuadrangle(quad)](#containsquadrangle) | Determines if the specified Quadrangle is contained or intersect this Quadrangle structure. |
| [containsRectangle(rect)](#containsrectangle) | Determines if the specified Rectangle is contained or intersect this Quadrangle structure. |
| [equals(other)](#equals) | Returns a value indicating whether this instance is equal to a specified Quadrangle value. |
| [getBoundingRectangle()](#getboundingrectangle) | Creates Rectangle bounding this Quadrangle |
| [getLeftBottom()](#getleftbottom) | Gets left-bottom corner Point of Quadrangle regionValue: A left-bottom corner Point of Quadrangle region |
| [getLeftTop()](#getlefttop) | Gets left-top corner Point of Quadrangle regionValue: A left-top corner Point of Quadrangle region |
| [getRightBottom()](#getrightbottom) | Gets right-bottom corner Point of Quadrangle regionValue: A right-bottom corner Point of Quadrangle region |
| [getRightTop()](#getrighttop) | Gets right-top corner Point of Quadrangle regionValue: A right-top corner Point of Quadrangle region |
| [hashCode()](#hashcode) | Returns the hash code for this instance. |
| [isEmpty()](#isempty) | Tests whether all Points of this Quadrangle have values of zero.Value: Returns true if all Points of this Quadrangle hav |
| [setLeftBottom()](#setleftbottom) | Sets left-bottom corner Point of Quadrangle regionValue: A left-bottom corner Point of Quadrangle region |
| [setLeftTop()](#setlefttop) | Sets left-top corner Point of Quadrangle regionValue: A left-top corner Point of Quadrangle region |
| [setRightBottom()](#setrightbottom) | Sets right-bottom corner Point of Quadrangle regionValue: A right-bottom corner Point of Quadrangle region |
| [setRightTop()](#setrighttop) | Sets right-top corner Point of Quadrangle regionValue: A right-top corner Point of Quadrangle region |
| [toString()](#tostring) | Returns a human-readable string representation of this Quadrangle. |

### contains(pt) {#contains}

Determines if the specified Point is contained within this Quadrangle structure.

| Parameter | Description |
| --- | --- |
| pt | The Point to test. |

**Returns:** true if Point is contained within this Quadrangle structure; otherwise, false.

### containsPoint(x, y) {#containspoint}

Determines if the specified point is contained within this Quadrangle structure.

| Parameter | Description |
| --- | --- |
| x | The x point cordinate. |
| y | The y point cordinate. |

**Returns:** Returns true if point is contained within this Quadrangle structure; otherwise, false.

### containsQuadrangle(quad) {#containsquadrangle}

Determines if the specified Quadrangle is contained or intersect this Quadrangle structure.

| Parameter | Description |
| --- | --- |
| quad | The Quadrangle to test. |

**Returns:** Returns true if Quadrangle is contained or intersect this Quadrangle structure; otherwise, false.

### containsRectangle(rect) {#containsrectangle}

Determines if the specified Rectangle is contained or intersect this Quadrangle structure.

| Parameter | Description |
| --- | --- |
| rect | The Rectangle to test. |

**Returns:** Returns true if Rectangle is contained or intersect this Quadrangle structure; otherwise, false.

### equals(other) {#equals}

Returns a value indicating whether this instance is equal to a specified Quadrangle value.

| Parameter | Description |
| --- | --- |
| other | An Quadrangle value to compare to this instance. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getBoundingRectangle() {#getboundingrectangle}

Creates Rectangle bounding this Quadrangle

**Returns:** returns Rectangle bounding this Quadrangle

### getLeftBottom() {#getleftbottom}

Gets left-bottom corner Point of Quadrangle regionValue: A left-bottom corner Point of Quadrangle region

### getLeftTop() {#getlefttop}

Gets left-top corner Point of Quadrangle regionValue: A left-top corner Point of Quadrangle region

### getRightBottom() {#getrightbottom}

Gets right-bottom corner Point of Quadrangle regionValue: A right-bottom corner Point of Quadrangle region

### getRightTop() {#getrighttop}

Gets right-top corner Point of Quadrangle regionValue: A right-top corner Point of Quadrangle region

### hashCode() {#hashcode}

Returns the hash code for this instance.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Tests whether all Points of this Quadrangle have values of zero.Value: Returns true if all Points of this Quadrangle have values of zero; otherwise, false.

### setLeftBottom() {#setleftbottom}

Sets left-bottom corner Point of Quadrangle regionValue: A left-bottom corner Point of Quadrangle region

### setLeftTop() {#setlefttop}

Sets left-top corner Point of Quadrangle regionValue: A left-top corner Point of Quadrangle region

### setRightBottom() {#setrightbottom}

Sets right-bottom corner Point of Quadrangle regionValue: A right-bottom corner Point of Quadrangle region

### setRightTop() {#setrighttop}

Sets right-top corner Point of Quadrangle regionValue: A right-top corner Point of Quadrangle region

### toString() {#tostring}

Returns a human-readable string representation of this Quadrangle.

**Returns:** A string that represents this Quadrangle.
