---
title: "Quadrangle"
second_title: "Справочник API Aspose.BarCode для Android через Java"
description: "Хранит набор из четырёх точек, представляющих область Quadrangle."
type: docs
weight: 41
url: /ru/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Сохраняет набор из четырёх  Point  s, представляющих регион  Quadrangle.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | Инициализирует новый экземпляр структуры  Quadrangle  с описывающими точками. |
## Поля

| Поле | Описание |
| --- | --- |
| [EMPTY](#EMPTY) | Представляет класс  Quadrangle  с неинициализированными свойствами. |
## Методы

| Метод | Описание |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | Определяет, содержится ли указанный  Point  в этом классе  Quadrangle . |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | Определяет, содержится ли указанный  Rectangle  или пересекает этот класс  Quadrangle . |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Определяет, содержится ли указанный  Quadrangle  или пересекает этот класс  Quadrangle . |
| [contains(int x, int y)](#contains-int-int-) | Определяет, содержится ли указанная точка в этом классе  Quadrangle . |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению  Quadrangle . |
| [getBoundingRectangle()](#getBoundingRectangle--) | Создаёт  Rectangle , ограничивающий этот  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Получает точку левого нижнего угла  Point  области  Quadrangle |
| [getLeftTop()](#getLeftTop--) | Получает точку левого верхнего угла  Point  области  Quadrangle |
| [getRightBottom()](#getRightBottom--) | Получает точку правого нижнего угла  Point  области  Quadrangle |
| [getRightTop()](#getRightTop--) | Получает точку правого верхнего угла  Point  области  Quadrangle |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [isEmpty()](#isEmpty--) | Проверяет, имеют ли все  Point  этого  Quadrangle  нулевые значения. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Получает точку левого нижнего угла  Point  области  Quadrangle |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Получает точку левого верхнего угла  Point  области  Quadrangle |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Получает точку правого нижнего угла  Point  области  Quadrangle |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Получает точку правого верхнего угла  Point  области  Quadrangle |
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


Инициализирует новый экземпляр структуры  Quadrangle  с описывающими точками.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| leftTop | android.graphics.Point | Точка  Point , представляющая левый верхний угол Quadrangle. |
| rightTop | android.graphics.Point | Точка, представляющая правый‑верхний угол Quadrangle. |
| rightBottom | android.graphics.Point | Точка, представляющая правый нижний угол Quadrangle. |
| leftBottom | android.graphics.Point | Точка, представляющая левый нижний угол Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Представляет класс  Quadrangle  с неинициализированными свойствами.

Значение: Quadrangle

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


Определяет, содержится ли указанный  Point  в этом классе  Quadrangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | android.graphics.Point | Точка для тестирования. |

**Returns:**
boolean — возвращает **true**, если Point находится внутри этого класса Quadrangle; в противном случае — **false**.
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


Определяет, содержится ли указанный  Rectangle  или пересекает этот класс  Quadrangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | android.graphics.Rect | Rectangle для тестирования. |

**Returns:**
boolean — возвращает **true**, если Rectangle содержится или пересекает этот класс Quadrangle; в противном случае — **false**.
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Определяет, содержится ли указанный  Quadrangle  или пересекает этот класс  Quadrangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Quadrangle для тестирования. |

**Returns:**
boolean — возвращает **true**, если Quadrangle содержится или пересекает этот класс Quadrangle; в противном случае — **false**.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Определяет, содержится ли указанная точка в этом классе  Quadrangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x точки. |
| y | int | Координата y точки. |

**Returns:**
boolean — возвращает **true**, если точка находится внутри этого класса Quadrangle; в противном случае — **false**.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает значение, указывающее, равен ли этот экземпляр указанному значению  Quadrangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Значение Quadrangle для сравнения с этим экземпляром. |

**Returns:**
boolean -  **true**  если obj имеет то же значение, что и этот экземпляр; иначе,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


Создаёт  Rectangle , ограничивающий этот  Quadrangle

**Returns:**
android.graphics.Rect — возвращает Rectangle, ограничивающий этот Quadrangle.
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


Получает точку левого нижнего угла  Point  области  Quadrangle

Значение: точка левого нижнего угла области Quadrangle.

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Получает точку левого верхнего угла  Point  области  Quadrangle

Значение: точка левого верхнего угла области Quadrangle.

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Получает точку правого нижнего угла  Point  области  Quadrangle

Значение: точка правого нижнего угла области Quadrangle.

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Получает точку правого верхнего угла  Point  области  Quadrangle

Значение: Правый верхний угол Точка региона Четырёхугольника

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int - 32-битный знаковый целочисленный хеш-код.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Проверяет, имеют ли все  Point  этого  Quadrangle  нулевые значения.

Значение: Возвращает **true**, если все Точки этого Четырёхугольника имеют нулевые значения; в противном случае **false**.

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


Получает точку левого нижнего угла  Point  области  Quadrangle

Значение: точка левого нижнего угла области Quadrangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Получает точку левого верхнего угла  Point  области  Quadrangle

Значение: точка левого верхнего угла области Quadrangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Получает точку правого нижнего угла  Point  области  Quadrangle

Значение: точка правого нижнего угла области Quadrangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Получает точку правого верхнего угла  Point  области  Quadrangle

Значение: Правый верхний угол Точка региона Четырёхугольника

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
java.lang.String — Строка, представляющая этот Четырёхугольник.
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

