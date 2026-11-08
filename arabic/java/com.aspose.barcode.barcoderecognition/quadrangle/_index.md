---
title: "Quadrangle"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "يخزن مجموعة من أربع Points تمثل منطقة Quadrangle."
type: docs
weight: 39
url: /ar/java/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

يخزن مجموعة من أربع نقاط تمثل منطقة رباعية.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-) | ينشئ مثيلًا جديدًا من الفئة  Quadrangle  باستخدام النقاط الوصفية. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [EMPTY](#EMPTY) | يمثل فئة  Quadrangle  مع ترك خصائصها غير مهيأة. |
## الدوال

| دالة | الوصف |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | يحدد ما إذا كان الـ  Quadrangle  المحدد محتوى أو يتقاطع مع فئة  Quadrangle  هذه. |
| [contains(int x, int y)](#contains-int-int-) | يحدد ما إذا كانت النقطة المحددة محتواة داخل فئة  Quadrangle  هذه. |
| [contains(Point pt)](#contains-java.awt.Point-) | يحدد ما إذا كان الـ  Point  المحدد محتوى داخل فئة  Quadrangle  هذه. |
| [contains(Rectangle rect)](#contains-java.awt.Rectangle-) | يحدد ما إذا كان الـ  Rectangle  المحدد محتوى أو يتقاطع مع فئة  Quadrangle  هذه. |
| [equals(Object obj)](#equals-java.lang.Object-) | يرجع قيمة تشير إلى ما إذا كان هذا المثيل مساويًا لقيمة  Quadrangle  المحددة. |
| [getBoundingRectangle()](#getBoundingRectangle--) | ينشئ  Rectangle  يحد هذا  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | يحصل على نقطة الزاوية اليسرى السفلية  Point  لمنطقة  Quadrangle |
| [getLeftTop()](#getLeftTop--) | يحصل على نقطة الزاوية اليسرى العليا  Point  لمنطقة  Quadrangle |
| [getRightBottom()](#getRightBottom--) | يحصل على نقطة الزاوية اليمنى السفلية  Point  لمنطقة  Quadrangle |
| [getRightTop()](#getRightTop--) | يحصل على نقطة الزاوية اليمنى العليا  Point  لمنطقة  Quadrangle |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذه المثيلة. |
| [isEmpty()](#isEmpty--) | يفحص ما إذا كانت جميع  Point s في هذا  Quadrangle  لها قيم صفر. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-java.awt.Point-) | يحصل على نقطة الزاوية اليسرى السفلية  Point  لمنطقة  Quadrangle |
| [setLeftTop(Point value)](#setLeftTop-java.awt.Point-) | يحصل على نقطة الزاوية اليسرى العليا  Point  لمنطقة  Quadrangle |
| [setRightBottom(Point value)](#setRightBottom-java.awt.Point-) | يحصل على نقطة الزاوية اليمنى السفلية  Point  لمنطقة  Quadrangle |
| [setRightTop(Point value)](#setRightTop-java.awt.Point-) | يحصل على نقطة الزاوية اليمنى العليا  Point  لمنطقة  Quadrangle |
| [toString()](#toString--) | يعيد تمثيل سلسلة قابلة للقراءة من قبل الإنسان لهذا Quadrangle . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


ينشئ مثيلًا جديدًا من الفئة  Quadrangle  باستخدام النقاط الوصفية.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| leftTop | java.awt.Point | نقطة Point تمثل الزاوية اليسرى العليا من Quadrangle. |
| rightTop | java.awt.Point | نقطة Point تمثل الزاوية اليمنى العليا من Quadrangle. |
| rightBottom | java.awt.Point | نقطة Point تمثل الزاوية اليمنى السفلية من Quadrangle. |
| leftBottom | java.awt.Point | نقطة Point تمثل الزاوية اليسرى السفلية من Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


يمثل فئة  Quadrangle  مع ترك خصائصها غير مهيأة.

القيمة: Quadrangle

### clone() {#clone--}
```
public Quadrangle clone()
```




**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


يحدد ما إذا كان الـ  Quadrangle  المحدد محتوى أو يتقاطع مع فئة  Quadrangle  هذه.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Quadrangle للاختبار. |

**Returns:**
منطقي - يعيد **true** إذا كان Quadrangle موجودًا أو يتقاطع مع فئة Quadrangle هذه؛ وإلا، **false** .
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


يحدد ما إذا كانت النقطة المحددة محتواة داخل فئة  Quadrangle  هذه.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| x | int | إحداثيات النقطة x. |
| y | int | إحداثيات النقطة y. |

**Returns:**
منطقي - يعيد **true** إذا كانت النقطة موجودة داخل فئة Quadrangle هذه؛ وإلا، **false** .
### contains(Point pt) {#contains-java.awt.Point-}
```
public boolean contains(Point pt)
```


يحدد ما إذا كان الـ  Point  المحدد محتوى داخل فئة  Quadrangle  هذه.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| pt | java.awt.Point | Point للاختبار. |

**Returns:**
منطقي - يعيد **true** إذا كانت Point موجودة داخل فئة Quadrangle هذه؛ وإلا، **false** .
### contains(Rectangle rect) {#contains-java.awt.Rectangle-}
```
public boolean contains(Rectangle rect)
```


يحدد ما إذا كان الـ  Rectangle  المحدد محتوى أو يتقاطع مع فئة  Quadrangle  هذه.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | java.awt.Rectangle | Rectangle للاختبار. |

**Returns:**
منطقي - يعيد **true** إذا كانت Rectangle موجودة أو تتقاطع مع فئة Quadrangle هذه؛ وإلا، **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يرجع قيمة تشير إلى ما إذا كان هذا المثيل مساويًا لقيمة  Quadrangle  المحددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة Quadrangle للمقارنة مع هذه الحالة. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كهذه المثيلة؛ وإلا،  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


ينشئ  Rectangle  يحد هذا  Quadrangle

**Returns:**
java.awt.Rectangle - يُرجِع Rectangle يحد هذا Quadrangle
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLeftBottom() {#getLeftBottom--}
```
public Point getLeftBottom()
```


يحصل على نقطة الزاوية اليسرى السفلية  Point  لمنطقة  Quadrangle

القيمة: نقطة الزاوية اليسرى السفلية لمنطقة Quadrangle

**Returns:**
java.awt.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


يحصل على نقطة الزاوية اليسرى العليا  Point  لمنطقة  Quadrangle

القيمة: نقطة الزاوية اليسرى العليا لمنطقة Quadrangle

**Returns:**
java.awt.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


يحصل على نقطة الزاوية اليمنى السفلية  Point  لمنطقة  Quadrangle

القيمة: نقطة الزاوية اليمنى السفلية لمنطقة Quadrangle

**Returns:**
java.awt.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


يحصل على نقطة الزاوية اليمنى العليا  Point  لمنطقة  Quadrangle

القيمة: نقطة الزاوية اليمنى العليا لمنطقة Quadrangle

**Returns:**
java.awt.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز التجزئة لهذه المثيلة.

**Returns:**
int - رمز تجزئة عدد صحيح موقع 32-بت.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يفحص ما إذا كانت جميع  Point s في هذا  Quadrangle  لها قيم صفر.

القيمة: يُرجِع **true** إذا كانت جميع نقاط هذا Quadrangle قيمها صفر؛ وإلا، **false**.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLeftBottom(Point value) {#setLeftBottom-java.awt.Point-}
```
public void setLeftBottom(Point value)
```


يحصل على نقطة الزاوية اليسرى السفلية  Point  لمنطقة  Quadrangle

القيمة: نقطة الزاوية اليسرى السفلية لمنطقة Quadrangle

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.awt.Point |  |

### setLeftTop(Point value) {#setLeftTop-java.awt.Point-}
```
public void setLeftTop(Point value)
```


يحصل على نقطة الزاوية اليسرى العليا  Point  لمنطقة  Quadrangle

القيمة: نقطة الزاوية اليسرى العليا لمنطقة Quadrangle

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.awt.Point |  |

### setRightBottom(Point value) {#setRightBottom-java.awt.Point-}
```
public void setRightBottom(Point value)
```


يحصل على نقطة الزاوية اليمنى السفلية  Point  لمنطقة  Quadrangle

القيمة: نقطة الزاوية اليمنى السفلية لمنطقة Quadrangle

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.awt.Point |  |

### setRightTop(Point value) {#setRightTop-java.awt.Point-}
```
public void setRightTop(Point value)
```


يحصل على نقطة الزاوية اليمنى العليا  Point  لمنطقة  Quadrangle

القيمة: نقطة الزاوية اليمنى العليا لمنطقة Quadrangle

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.awt.Point |  |

### toString() {#toString--}
```
public String toString()
```


يعيد تمثيل سلسلة قابلة للقراءة من قبل الإنسان لهذا Quadrangle .

**Returns:**
java.lang.String - سلسلة تمثل هذا Quadrangle.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

