---
title: Quadrangle
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: يخزن مجموعة من أربع Points تمثل منطقة Quadrangle.
type: docs
weight: 43
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

يخزن مجموعة من أربع نقاط Point تمثل منطقة Quadrangle
## Constructors

| Constructor | الوصف |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | ينشئ نسخة جديدة من بنية  Quadrangle  باستخدام النقاط الوصفية. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [EMPTY](#EMPTY) | يمثل فئة  Quadrangle  مع خصائصها غير مهيأة. |
## Methods

| Method | الوصف |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | يحدد ما إذا كان الـ Point المحدد موجودًا داخل فئة  Quadrangle  هذه. |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | يحدد ما إذا كان الـ Rectangle المحدد موجودًا أو يتقاطع مع فئة  Quadrangle  هذه. |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | يحدد ما إذا كان الـ Quadrangle المحدد موجودًا أو يتقاطع مع فئة  Quadrangle  هذه. |
| [contains(int x, int y)](#contains-int-int-) | يحدد ما إذا كانت النقطة المحددة موجودة داخل فئة  Quadrangle  هذه. |
| [equals(Object obj)](#equals-java.lang.Object-) | يعيد قيمة تشير إلى ما إذا كانت هذه النسخة مساوية لقيمة  Quadrangle  المحددة. |
| [getBoundingRectangle()](#getBoundingRectangle--) | ينشئ  Rectangle  يحد هذا  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | يحصل على نقطة الزاوية اليسرى السفلية  Point  لمنطقة  Quadrangle |
| [getLeftTop()](#getLeftTop--) | يحصل على نقطة الزاوية اليسرى‑العليا لمنطقة Quadrangle |
| [getRightBottom()](#getRightBottom--) | يحصل على نقطة الزاوية اليمنى‑السفلية لمنطقة Quadrangle |
| [getRightTop()](#getRightTop--) | يحصل على نقطة الزاوية اليمنى‑العليا لمنطقة Quadrangle |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [isEmpty()](#isEmpty--) | يفحص ما إذا كانت جميع نقاط هذا Quadrangle لها قيم صفرية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | يحصل على نقطة الزاوية اليسرى السفلية  Point  لمنطقة  Quadrangle |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | يحصل على نقطة الزاوية اليسرى‑العليا لمنطقة Quadrangle |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | يحصل على نقطة الزاوية اليمنى‑السفلية لمنطقة Quadrangle |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | يحصل على نقطة الزاوية اليمنى‑العليا لمنطقة Quadrangle |
| [toString()](#toString--) | يرجع تمثيلاً نصيًا مقروءًا للإنسان لهذا Quadrangle. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


ينشئ نسخة جديدة من بنية  Quadrangle  باستخدام النقاط الوصفية.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| leftTop | android.graphics.Point | نقطة تمثل الزاوية اليسرى‑العليا للـ Quadrangle. |
| rightTop | android.graphics.Point | نقطة تمثل الزاوية اليمنى‑العليا للـ Quadrangle. |
| rightBottom | android.graphics.Point | نقطة تمثل الزاوية اليمنى‑السفلية للـ Quadrangle. |
| leftBottom | android.graphics.Point | نقطة تمثل الزاوية اليسرى‑السفلية للـ Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


يمثل فئة  Quadrangle  مع خصائصها غير مهيأة.

القيمة: Quadrangle

### clone() {#clone--}
```
public Quadrangle clone()
```




**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### contains(Point pt) {#contains-android.graphics.Point-}
```
public boolean contains(Point pt)
```


يحدد ما إذا كان الـ Point المحدد موجودًا داخل فئة  Quadrangle  هذه.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| pt | android.graphics.Point | النقطة Point للاختبار. |

**Returns:**
منطقي - يرجع **true** إذا كانت Point موجودة داخل فئة Quadrangle هذه؛ وإلا **false**.
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


يحدد ما إذا كان الـ Rectangle المحدد موجودًا أو يتقاطع مع فئة  Quadrangle  هذه.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| rect | android.graphics.Rect | المستطيل Rectangle للاختبار. |

**Returns:**
منطقي - يرجع **true** إذا كان Rectangle موجودًا أو يتقاطع مع فئة Quadrangle هذه؛ وإلا **false**.
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


يحدد ما إذا كان الـ Quadrangle المحدد موجودًا أو يتقاطع مع فئة  Quadrangle  هذه.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | الـ Quadrangle للاختبار. |

**Returns:**
منطقي - يرجع **true** إذا كان Quadrangle موجودًا أو يتقاطع مع فئة Quadrangle هذه؛ وإلا **false**.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


يحدد ما إذا كانت النقطة المحددة موجودة داخل فئة  Quadrangle  هذه.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| x | int | إحداثية النقطة x. |
| y | int | إحداثي النقطة ص. |

**Returns:**
منطقي - يرجع **true** إذا كانت النقطة داخل فئة Quadrangle هذه؛ وإلا **false**.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يعيد قيمة تشير إلى ما إذا كانت هذه النسخة مساوية لقيمة  Quadrangle  المحددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة Quadrangle للمقارنة مع هذا المثيل. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كما هذا الكائن؛ وإلا،  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


ينشئ  Rectangle  يحد هذا  Quadrangle

**Returns:**
android.graphics.Rect - يرجع Rectangle الذي يحد Quadrangle هذا.
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

القيمة: نقطة الزاوية اليسرى السفلية Point لمنطقة Quadrangle.

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


يحصل على نقطة الزاوية اليسرى‑العليا لمنطقة Quadrangle

القيمة: نقطة الزاوية اليسرى العليا Point لمنطقة Quadrangle.

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


يحصل على نقطة الزاوية اليمنى‑السفلية لمنطقة Quadrangle

القيمة: نقطة الزاوية اليمنى السفلية Point لمنطقة Quadrangle.

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


يحصل على نقطة الزاوية اليمنى‑العليا لمنطقة Quadrangle

القيمة: نقطة الزاوية اليمنى العليا Point لمنطقة Quadrangle.

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - رمز تجزئة (hash code) عدد صحيح موقع 32 بت.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يفحص ما إذا كانت جميع نقاط هذا Quadrangle لها قيم صفرية.

القيمة: يرجع **true** إذا كانت جميع Point في هذا Quadrangle قيمتها صفر؛ وإلا **false**.

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




### setLeftBottom(Point value) {#setLeftBottom-android.graphics.Point-}
```
public void setLeftBottom(Point value)
```


يحصل على نقطة الزاوية اليسرى السفلية  Point  لمنطقة  Quadrangle

القيمة: نقطة الزاوية اليسرى السفلية Point لمنطقة Quadrangle.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


يحصل على نقطة الزاوية اليسرى‑العليا لمنطقة Quadrangle

القيمة: نقطة الزاوية اليسرى العليا Point لمنطقة Quadrangle.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


يحصل على نقطة الزاوية اليمنى‑السفلية لمنطقة Quadrangle

القيمة: نقطة الزاوية اليمنى السفلية Point لمنطقة Quadrangle.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


يحصل على نقطة الزاوية اليمنى‑العليا لمنطقة Quadrangle

القيمة: نقطة الزاوية اليمنى العليا Point لمنطقة Quadrangle.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


يرجع تمثيلاً نصيًا مقروءًا للإنسان لهذا Quadrangle.

**Returns:**
java.lang.String - سلسلة تمثل هذا Quadrangle.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

