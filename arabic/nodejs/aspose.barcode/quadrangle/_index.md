---
title: "Quadrangle"
linktitle: "Quadrangle"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "يخزن مجموعة من أربع نقاط تمثل منطقة رباعية."
type: docs
weight: 850
url: /ar/nodejs/aspose.barcode/quadrangle/
---

## Quadrangle class

يخزن مجموعة من أربع نقاط تمثل منطقة رباعية.

```js
new Quadrangle(leftTop, rightTop, rightBottom, leftBottom)
```

يُهيئ نسخة جديدة من بنية Quadrangle بالنقاط الوصفية.

| معامل | الوصف |
| --- | --- |
| leftTop | نقطة تمثل الزاوية اليسرى العليا من Quadrangle. |
| rightTop | نقطة تمثل الزاوية اليمنى العليا من Quadrangle. |
| rightBottom | نقطة تمثل الزاوية اليمنى السفلية من Quadrangle. |
| leftBottom | نقطة تمثل الزاوية اليسرى السفلية من Quadrangle. |

## طرق

| اسم | الوصف |
| --- | --- |
| [contains(pt)](#contains) | يحدد ما إذا كانت النقطة المحددة موجودة داخل بنية Quadrangle هذه. |
| [containsPoint(x, y)](#containspoint) | يحدد ما إذا كانت النقطة المحددة موجودة داخل بنية Quadrangle هذه. |
| [containsQuadrangle(quad)](#containsquadrangle) | يحدد ما إذا كان Quadrangle المحدد موجودًا أو يتقاطع مع بنية Quadrangle هذه. |
| [containsRectangle(rect)](#containsrectangle) | يحدد ما إذا كان Rectangle المحدد موجودًا أو يتقاطع مع بنية Quadrangle هذه. |
| [equals(other)](#equals) | يرجع قيمة تشير إلى ما إذا كان هذا المثيل مساويًا لقيمة Quadrangle المحددة. |
| [getBoundingRectangle()](#getboundingrectangle) | ينشئ Rectangle يحدّ هذه Quadrangle. |
| [getLeftBottom()](#getleftbottom) | يحصل على نقطة الزاوية اليسرى السفلية لمنطقة Quadrangle القيمة: نقطة الزاوية اليسرى السفلية لمنطقة Quadrangle |
| [getLeftTop()](#getlefttop) | يحصل على نقطة الزاوية اليسرى العليا لمنطقة Quadrangle القيمة: نقطة الزاوية اليسرى العليا لمنطقة Quadrangle |
| [getRightBottom()](#getrightbottom) | يحصل على نقطة الزاوية اليمنى السفلية لمنطقة Quadrangle القيمة: نقطة الزاوية اليمنى السفلية لمنطقة Quadrangle |
| [getRightTop()](#getrighttop) | يحصل على نقطة الزاوية اليمنى العليا لمنطقة Quadrangle القيمة: نقطة الزاوية اليمنى العليا لمنطقة Quadrangle |
| [hashCode()](#hashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [isEmpty()](#isempty) | يفحص ما إذا كانت جميع نقاط هذا الشكل الرباعي لها قيم صفر. القيمة: يرجع true إذا كانت جميع نقاط هذا الشكل الرباعي لها قيم صفر |
| [setLeftBottom()](#setleftbottom) | يضبط نقطة الزاوية اليسرى السفلية لمنطقة الشكل الرباعي. القيمة: نقطة الزاوية اليسرى السفلية لمنطقة الشكل الرباعي |
| [setLeftTop()](#setlefttop) | يضبط نقطة الزاوية اليسرى العليا لمنطقة الشكل الرباعي. القيمة: نقطة الزاوية اليسرى العليا لمنطقة الشكل الرباعي |
| [setRightBottom()](#setrightbottom) | يضبط نقطة الزاوية اليمنى السفلية لمنطقة الشكل الرباعي. القيمة: نقطة الزاوية اليمنى السفلية لمنطقة الشكل الرباعي |
| [setRightTop()](#setrighttop) | يضبط نقطة الزاوية اليمنى العليا لمنطقة الشكل الرباعي. القيمة: نقطة الزاوية اليمنى العليا لمنطقة الشكل الرباعي |
| [toString()](#tostring) | يرجع تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا الشكل الرباعي. |

### contains(pt) {#contains}

يحدد ما إذا كانت النقطة المحددة موجودة داخل بنية Quadrangle هذه.

| معامل | الوصف |
| --- | --- |
| pt | النقطة للاختبار. |

**Returns:** true if Point is contained within this Quadrangle structure; otherwise, false.

### containsPoint(x, y) {#containspoint}

يحدد ما إذا كانت النقطة المحددة موجودة داخل بنية Quadrangle هذه.

| معامل | الوصف |
| --- | --- |
| x | إحداثية النقطة x. |
| y | إحداثية النقطة y. |

**Returns:** Returns true if point is contained within this Quadrangle structure; otherwise, false.

### containsQuadrangle(quad) {#containsquadrangle}

يحدد ما إذا كان Quadrangle المحدد موجودًا أو يتقاطع مع بنية Quadrangle هذه.

| معامل | الوصف |
| --- | --- |
| quad | الشكل الرباعي للاختبار. |

**Returns:** Returns true if Quadrangle is contained or intersect this Quadrangle structure; otherwise, false.

### containsRectangle(rect) {#containsrectangle}

يحدد ما إذا كان Rectangle المحدد موجودًا أو يتقاطع مع بنية Quadrangle هذه.

| معامل | الوصف |
| --- | --- |
| rect | المستطيل للاختبار. |

**Returns:** Returns true if Rectangle is contained or intersect this Quadrangle structure; otherwise, false.

### equals(other) {#equals}

يرجع قيمة تشير إلى ما إذا كان هذا المثيل مساويًا لقيمة Quadrangle المحددة.

| معامل | الوصف |
| --- | --- |
| أخرى | قيمة شكل رباعي للمقارنة مع هذه الحالة. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getBoundingRectangle() {#getboundingrectangle}

ينشئ Rectangle يحدّ هذه Quadrangle.

**Returns:** returns Rectangle bounding this Quadrangle

### getLeftBottom() {#getleftbottom}

يحصل على نقطة الزاوية اليسرى السفلية لمنطقة Quadrangle القيمة: نقطة الزاوية اليسرى السفلية لمنطقة Quadrangle

### getLeftTop() {#getlefttop}

يحصل على نقطة الزاوية اليسرى العليا لمنطقة Quadrangle القيمة: نقطة الزاوية اليسرى العليا لمنطقة Quadrangle

### getRightBottom() {#getrightbottom}

يحصل على نقطة الزاوية اليمنى السفلية لمنطقة Quadrangle القيمة: نقطة الزاوية اليمنى السفلية لمنطقة Quadrangle

### getRightTop() {#getrighttop}

يحصل على نقطة الزاوية اليمنى العليا لمنطقة Quadrangle القيمة: نقطة الزاوية اليمنى العليا لمنطقة Quadrangle

### hashCode() {#hashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

يفحص ما إذا كانت جميع نقاط هذا الشكل الرباعي لها قيم صفر. القيمة: يرجع true إذا كانت جميع نقاط هذا الشكل الرباعي لها قيم صفر؛ وإلا، false.

### setLeftBottom() {#setleftbottom}

يضبط نقطة الزاوية اليسرى السفلية لمنطقة الشكل الرباعي. القيمة: نقطة الزاوية اليسرى السفلية لمنطقة الشكل الرباعي

### setLeftTop() {#setlefttop}

يضبط نقطة الزاوية اليسرى العليا لمنطقة الشكل الرباعي. القيمة: نقطة الزاوية اليسرى العليا لمنطقة الشكل الرباعي

### setRightBottom() {#setrightbottom}

يضبط نقطة الزاوية اليمنى السفلية لمنطقة الشكل الرباعي. القيمة: نقطة الزاوية اليمنى السفلية لمنطقة الشكل الرباعي

### setRightTop() {#setrighttop}

يضبط نقطة الزاوية اليمنى العليا لمنطقة الشكل الرباعي. القيمة: نقطة الزاوية اليمنى العليا لمنطقة الشكل الرباعي

### toString() {#tostring}

يرجع تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا الشكل الرباعي.

**Returns:** A string that represents this Quadrangle.
