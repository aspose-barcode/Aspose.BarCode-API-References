---
title: "Quadrangle"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Сохраняет набор из четырёх точек, представляющих регион в виде четырёхугольника."
type: docs
weight: 850
url: /ru/nodejs/aspose.barcode/quadrangle/
---

## Quadrangle class

Сохраняет набор из четырёх точек, представляющих регион в виде четырёхугольника.

```js
new Quadrangle(leftTop, rightTop, rightBottom, leftBottom)
```

Инициализирует новый экземпляр структуры Quadrangle с описывающими точками.

| Параметр | Описание |
| --- | --- |
| leftTop | Точка, представляющая левый верхний угол Quadrangle. |
| rightTop | Точка, представляющая правый верхний угол Quadrangle. |
| rightBottom | Точка, представляющая правый нижний угол Quadrangle. |
| leftBottom | Точка, представляющая левый нижний угол Quadrangle. |

## Методы

| Имя | Описание |
| --- | --- |
| [contains(pt)](#contains) | Определяет, содержится ли указанная Точка внутри этой структуры Quadrangle. |
| [containsPoint(x, y)](#containspoint) | Определяет, содержится ли указанная точка внутри этой структуры Quadrangle. |
| [containsQuadrangle(quad)](#containsquadrangle) | Определяет, содержится ли указанный Quadrangle в этой структуре Quadrangle или пересекает её. |
| [containsRectangle(rect)](#containsrectangle) | Определяет, содержится ли указанный Rectangle в этой структуре Quadrangle или пересекает её. |
| [equals(other)](#equals) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению Quadrangle. |
| [getBoundingRectangle()](#getboundingrectangle) | Создаёт Rectangle, ограничивающий этот Quadrangle |
| [getLeftBottom()](#getleftbottom) | Получает точку левого нижнего угла Quadrangle regionValue: Точка левого нижнего угла региона Quadrangle |
| [getLeftTop()](#getlefttop) | Получает точку левого верхнего угла Quadrangle regionValue: Точка левого верхнего угла региона Quadrangle |
| [getRightBottom()](#getrightbottom) | Получает точку правого нижнего угла Quadrangle regionValue: Точка правого нижнего угла региона Quadrangle |
| [getRightTop()](#getrighttop) | Получает точку правого верхнего угла Quadrangle regionValue: Точка правого верхнего угла региона Quadrangle |
| [hashCode()](#hashcode) | Возвращает хеш-код для этого экземпляра. |
| [isEmpty()](#isempty) | Проверяет, имеют ли все точки этого Quadrangle значение ноль.Значение: Возвращает true, если все точки этого Quadrangle hav |
| [setLeftBottom()](#setleftbottom) | Устанавливает точку левого нижнего угла области QuadrangleЗначение: Точка левого нижнего угла области Quadrangle |
| [setLeftTop()](#setlefttop) | Устанавливает точку левого верхнего угла области QuadrangleЗначение: Точка левого верхнего угла области Quadrangle |
| [setRightBottom()](#setrightbottom) | Устанавливает точку правого нижнего угла области QuadrangleЗначение: Точка правого нижнего угла области Quadrangle |
| [setRightTop()](#setrighttop) | Устанавливает точку правого верхнего угла области QuadrangleЗзначение: Точка правого верхнего угла области Quadrangle |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этого Quadrangle. |

### contains(pt) {#contains}

Определяет, содержится ли указанная Точка внутри этой структуры Quadrangle.

| Параметр | Описание |
| --- | --- |
| pt | Точка для тестирования. |

**Returns:** true if Point is contained within this Quadrangle structure; otherwise, false.

### containsPoint(x, y) {#containspoint}

Определяет, содержится ли указанная точка внутри этой структуры Quadrangle.

| Параметр | Описание |
| --- | --- |
| x | Координата точки x. |
| y | Координата точки y. |

**Returns:** Returns true if point is contained within this Quadrangle structure; otherwise, false.

### containsQuadrangle(quad) {#containsquadrangle}

Определяет, содержится ли указанный Quadrangle в этой структуре Quadrangle или пересекает её.

| Параметр | Описание |
| --- | --- |
| quad | Quadrangle для тестирования. |

**Returns:** Returns true if Quadrangle is contained or intersect this Quadrangle structure; otherwise, false.

### containsRectangle(rect) {#containsrectangle}

Определяет, содержится ли указанный Rectangle в этой структуре Quadrangle или пересекает её.

| Параметр | Описание |
| --- | --- |
| rect | Rectangle для тестирования. |

**Returns:** Returns true if Rectangle is contained or intersect this Quadrangle structure; otherwise, false.

### equals(other) {#equals}

Возвращает значение, указывающее, равен ли этот экземпляр указанному значению Quadrangle.

| Параметр | Описание |
| --- | --- |
| другое | Значение Quadrangle для сравнения с этим экземпляром. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getBoundingRectangle() {#getboundingrectangle}

Создаёт Rectangle, ограничивающий этот Quadrangle

**Returns:** returns Rectangle bounding this Quadrangle

### getLeftBottom() {#getleftbottom}

Получает точку левого нижнего угла Quadrangle regionValue: Точка левого нижнего угла региона Quadrangle

### getLeftTop() {#getlefttop}

Получает точку левого верхнего угла Quadrangle regionValue: Точка левого верхнего угла региона Quadrangle

### getRightBottom() {#getrightbottom}

Получает точку правого нижнего угла Quadrangle regionValue: Точка правого нижнего угла региона Quadrangle

### getRightTop() {#getrighttop}

Получает точку правого верхнего угла Quadrangle regionValue: Точка правого верхнего угла региона Quadrangle

### hashCode() {#hashcode}

Возвращает хеш-код для этого экземпляра.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Проверяет, имеют ли все точки этого Quadrangle значение ноль.Значение: Возвращает true, если все точки этого Quadrangle имеют значение ноль; в противном случае — false.

### setLeftBottom() {#setleftbottom}

Устанавливает точку левого нижнего угла области QuadrangleЗначение: Точка левого нижнего угла области Quadrangle

### setLeftTop() {#setlefttop}

Устанавливает точку левого верхнего угла области QuadrangleЗначение: Точка левого верхнего угла области Quadrangle

### setRightBottom() {#setrightbottom}

Устанавливает точку правого нижнего угла области QuadrangleЗначение: Точка правого нижнего угла области Quadrangle

### setRightTop() {#setrighttop}

Устанавливает точку правого верхнего угла области QuadrangleЗзначение: Точка правого верхнего угла области Quadrangle

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этого Quadrangle.

**Returns:** A string that represents this Quadrangle.
