---
title: "四边形"
linktitle: "四边形"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "存储一组由四个点组成的表示四边形区域的点集合。"
type: docs
weight: 850
url: /zh/nodejs/aspose.barcode/quadrangle/
---

## Quadrangle class

存储一组由四个点组成的表示四边形区域的点集合。

```js
new Quadrangle(leftTop, rightTop, rightBottom, leftBottom)
```

使用描述点初始化 Quadrangle 结构的新实例。

| 参数 | 描述 |
| --- | --- |
| 左上 | 表示 Quadrangle 左上角的点。 |
| 右上 | 表示 Quadrangle 右上角的点。 |
| 右下 | 表示 Quadrangle 右下角的点。 |
| 左下 | 表示 Quadrangle 左下角的点。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [contains(pt)](#contains) | 确定指定的点是否包含在此 Quadrangle 结构中。 |
| [containsPoint(x, y)](#containspoint) | 确定指定的点是否包含在此 Quadrangle 结构中。 |
| [containsQuadrangle(quad)](#containsquadrangle) | 确定指定的 Quadrangle 是否包含或与此 Quadrangle 结构相交。 |
| [containsRectangle(rect)](#containsrectangle) | 确定指定的矩形是否包含或与此 Quadrangle 结构相交。 |
| [equals(other)](#equals) | 返回一个值，指示此实例是否等于指定的 Quadrangle 值。 |
| [getBoundingRectangle()](#getboundingrectangle) | 创建包围此 Quadrangle 的矩形 |
| [getLeftBottom()](#getleftbottom) | 获取 Quadrangle 区域的左下角点 值：Quadrangle 区域的左下角点 |
| [getLeftTop()](#getlefttop) | 获取 Quadrangle 区域的左上角点 值：Quadrangle 区域的左上角点 |
| [getRightBottom()](#getrightbottom) | 获取 Quadrangle 区域的右下角点 值：Quadrangle 区域的右下角点 |
| [getRightTop()](#getrighttop) | 获取 Quadrangle 区域的右上角点 值：Quadrangle 区域的右上角点 |
| [hashCode()](#hashcode) | 返回此实例的哈希码。 |
| [isEmpty()](#isempty) | 测试此四边形的所有点是否全部为零。值：如果此四边形的所有点全部为零则返回 true。 |
| [setLeftBottom()](#setleftbottom) | 设置四边形区域左下角的点。值：四边形区域左下角的点。 |
| [setLeftTop()](#setlefttop) | 设置四边形区域左上角的点。值：四边形区域左上角的点。 |
| [setRightBottom()](#setrightbottom) | 设置四边形区域右下角的点。值：四边形区域右下角的点。 |
| [setRightTop()](#setrighttop) | 设置四边形区域右上角的点。值：四边形区域右上角的点。 |
| [toString()](#tostring) | 返回此四边形的可读字符串表示。 |

### contains(pt) {#contains}

确定指定的点是否包含在此 Quadrangle 结构中。

| 参数 | 描述 |
| --- | --- |
| pt | 要测试的点。 |

**Returns:** true if Point is contained within this Quadrangle structure; otherwise, false.

### containsPoint(x, y) {#containspoint}

确定指定的点是否包含在此 Quadrangle 结构中。

| 参数 | 描述 |
| --- | --- |
| x | x 点坐标。 |
| y | y 点坐标。 |

**Returns:** Returns true if point is contained within this Quadrangle structure; otherwise, false.

### containsQuadrangle(quad) {#containsquadrangle}

确定指定的 Quadrangle 是否包含或与此 Quadrangle 结构相交。

| 参数 | 描述 |
| --- | --- |
| quad | 要测试的四边形。 |

**Returns:** Returns true if Quadrangle is contained or intersect this Quadrangle structure; otherwise, false.

### containsRectangle(rect) {#containsrectangle}

确定指定的矩形是否包含或与此 Quadrangle 结构相交。

| 参数 | 描述 |
| --- | --- |
| rect | 要测试的矩形。 |

**Returns:** Returns true if Rectangle is contained or intersect this Quadrangle structure; otherwise, false.

### equals(other) {#equals}

返回一个值，指示此实例是否等于指定的 Quadrangle 值。

| 参数 | 描述 |
| --- | --- |
| 其他 | 用于与此实例比较的四边形值。 |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getBoundingRectangle() {#getboundingrectangle}

创建包围此 Quadrangle 的矩形

**Returns:** returns Rectangle bounding this Quadrangle

### getLeftBottom() {#getleftbottom}

获取 Quadrangle 区域的左下角点 值：Quadrangle 区域的左下角点

### getLeftTop() {#getlefttop}

获取 Quadrangle 区域的左上角点 值：Quadrangle 区域的左上角点

### getRightBottom() {#getrightbottom}

获取 Quadrangle 区域的右下角点 值：Quadrangle 区域的右下角点

### getRightTop() {#getrighttop}

获取 Quadrangle 区域的右上角点 值：Quadrangle 区域的右上角点

### hashCode() {#hashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

测试此四边形的所有点是否全部为零。值：如果此四边形的所有点全部为零则返回 true；否则返回 false。

### setLeftBottom() {#setleftbottom}

设置四边形区域左下角的点。值：四边形区域左下角的点。

### setLeftTop() {#setlefttop}

设置四边形区域左上角的点。值：四边形区域左上角的点。

### setRightBottom() {#setrightbottom}

设置四边形区域右下角的点。值：四边形区域右下角的点。

### setRightTop() {#setrighttop}

设置四边形区域右上角的点。值：四边形区域右上角的点。

### toString() {#tostring}

返回此四边形的可读字符串表示。

**Returns:** A string that represents this Quadrangle.
