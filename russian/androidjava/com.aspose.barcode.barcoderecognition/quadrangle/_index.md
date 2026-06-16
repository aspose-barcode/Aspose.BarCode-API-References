---
title: Quadrangle
second_title: Справочник API Aspose.BarCode для Android через Java
description: Stores a set of four Points that represent a Quadrangle region.
type: docs
weight: 43
url: /ru/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Сохраняет набор из четырёх  Point  , представляющих регион  Quadrangle .
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | Initializes a new instance of the  Quadrangle  structure with the describing points. |
## Поля

| Поле | Описание |
| --- | --- |
| [EMPTY](#EMPTY) | Represents a  Quadrangle  class with its properties left uninitialized. |
## Методы

| Метод | Описание |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | Determines if the specified  Point  is contained within this  Quadrangle  class. |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | Determines if the specified  Rectangle  is contained or intersect this  Quadrangle  class. |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Determines if the specified  Quadrangle  is contained or intersect this  Quadrangle  class. |
| [contains(int x, int y)](#contains-int-int-) | Determines if the specified point is contained within this  Quadrangle  class. |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified  Quadrangle  value. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Creates  Rectangle  bounding this  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Gets left-bottom corner  Point  of  Quadrangle  region |
| [getLeftTop()](#getLeftTop--) | Получает левый верхний угол  Point  региона Quadrangle |
| [getRightBottom()](#getRightBottom--) | Получает правый нижний угол  Point  региона Quadrangle |
| [getRightTop()](#getRightTop--) | Получает правый верхний угол  Point  региона Quadrangle |
| [hashCode()](#hashCode--) | Возвращает хеш‑код для этого экземпляра. |
| [isEmpty()](#isEmpty--) | Проверяет, имеют ли все  Point  этого  Quadrangle  нулевые значения. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Gets left-bottom corner  Point  of  Quadrangle  region |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Получает левый верхний угол  Point  региона Quadrangle |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Получает правый нижний угол  Point  региона Quadrangle |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Получает правый верхний угол  Point  региона Quadrangle |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого  Quadrangle . |
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


Initializes a new instance of the  Quadrangle  structure with the describing points.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| leftTop | android.graphics.Point | Точка  Point , представляющая левый верхний угол Quadrangle. |
| rightTop | android.graphics.Point | Точка  Point , представляющая правый верхний угол Quadrangle. |
| rightBottom | android.graphics.Point | Точка  Point , представляющая правый нижний угол Quadrangle. |
| leftBottom | android.graphics.Point | Точка  Point , представляющая левый нижний угол Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Represents a  Quadrangle  class with its properties left uninitialized.

Значение:  Quadrangle

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


Determines if the specified  Point  is contained within this  Quadrangle  class.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | android.graphics.Point | Точка  Point  для тестирования. |

**Returns:**
boolean - Возвращает  **true**  если  Point  содержится в этом классе  Quadrangle ; в противном случае  **false** .
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


Determines if the specified  Rectangle  is contained or intersect this  Quadrangle  class.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | android.graphics.Rect | Прямоугольник  Rectangle  для тестирования. |

**Returns:**
boolean - Возвращает  **true**  если  Rectangle  содержится или пересекает этот класс  Quadrangle ; в противном случае  **false** .
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Determines if the specified  Quadrangle  is contained or intersect this  Quadrangle  class.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Тестируемый  Quadrangle  для проверки. |

**Returns:**
boolean - Возвращает  **true**  если  Quadrangle  содержится или пересекает этот класс  Quadrangle ; в противном случае  **false** .
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Determines if the specified point is contained within this  Quadrangle  class.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x точки. |
| y | int | Координата y точки. |

**Returns:**
boolean - Возвращает  **true**, если точка находится внутри этого класса  Quadrangle ; в противном случае,  **false**.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns a value indicating whether this instance is equal to a specified  Quadrangle  value.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Значение  Quadrangle  для сравнения с этим экземпляром. |

**Returns:**
boolean —  **true**  если obj имеет то же значение, что и этот экземпляр; в противном случае  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


Creates  Rectangle  bounding this  Quadrangle

**Returns:**
android.graphics.Rect - возвращает  Rectangle , ограничивающий этот  Quadrangle.
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


Gets left-bottom corner  Point  of  Quadrangle  region

Значение: Точка левого нижнего угла  Point  области  Quadrangle.

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Получает левый верхний угол  Point  региона Quadrangle

Значение: Точка левого верхнего угла  Point  области  Quadrangle.

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Получает правый нижний угол  Point  региона Quadrangle

Значение: Точка правого нижнего угла  Point  области  Quadrangle.

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Получает правый верхний угол  Point  региона Quadrangle

Значение: Точка правого верхнего угла  Point  области  Quadrangle.

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код для этого экземпляра.

**Returns:**
int — 32‑битный знаковый целочисленный хеш‑код.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Проверяет, имеют ли все  Point  этого  Quadrangle  нулевые значения.

Значение: Возвращает  **true**, если все  Point  этого  Quadrangle  имеют нулевые значения; в противном случае,  **false**.

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


Gets left-bottom corner  Point  of  Quadrangle  region

Значение: Точка левого нижнего угла  Point  области  Quadrangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Получает левый верхний угол  Point  региона Quadrangle

Значение: Точка левого верхнего угла  Point  области  Quadrangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Получает правый нижний угол  Point  региона Quadrangle

Значение: Точка правого нижнего угла  Point  области  Quadrangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Получает правый верхний угол  Point  региона Quadrangle

Значение: Точка правого верхнего угла  Point  области  Quadrangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого  Quadrangle .

**Returns:**
java.lang.String - Строка, представляющая этот  Quadrangle.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

