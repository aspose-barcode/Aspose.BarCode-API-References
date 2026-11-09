---
title: "Quadrangle"
second_title: "Aspose.BarCode for Java API Reference"
description: "Сохраняет набор из четырёх Points, представляющих регион Quadrangle."
type: docs
weight: 39
url: /ru/java/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Сохраняет набор из четырёх точек Point, представляющих регион Quadrangle
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-) | Инициализирует новый экземпляр класса  Quadrangle  с описывающими точками. |
## Поля

| Поле | Описание |
| --- | --- |
| [EMPTY](#EMPTY) | Представляет класс  Quadrangle , у которого свойства оставлены неинициализированными. |
## Методы

| Метод | Описание |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Определяет, содержится ли указанный  Quadrangle  в этом классе  Quadrangle  или пересекается с ним. |
| [contains(int x, int y)](#contains-int-int-) | Определяет, содержится ли указанная точка в этом классе  Quadrangle . |
| [contains(Point pt)](#contains-java.awt.Point-) | Определяет, содержится ли указанный  Point  в этом классе  Quadrangle . |
| [contains(Rectangle rect)](#contains-java.awt.Rectangle-) | Определяет, содержится ли указанный  Rectangle  в этом классе  Quadrangle  или пересекается с ним. |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению  Quadrangle . |
| [getBoundingRectangle()](#getBoundingRectangle--) | Создаёт  Rectangle , ограничивающий этот  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Получает левый нижний угол  Point  региона  Quadrangle |
| [getLeftTop()](#getLeftTop--) | Получает левый верхний угол  Point  региона  Quadrangle |
| [getRightBottom()](#getRightBottom--) | Получает правый нижний угол  Point  региона  Quadrangle |
| [getRightTop()](#getRightTop--) | Получает правый верхний угол  Point  региона  Quadrangle |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [isEmpty()](#isEmpty--) | Проверяет, имеют ли все  Point s этого  Quadrangle  нулевые значения. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-java.awt.Point-) | Получает левый нижний угол  Point  региона  Quadrangle |
| [setLeftTop(Point value)](#setLeftTop-java.awt.Point-) | Получает левый верхний угол  Point  региона  Quadrangle |
| [setRightBottom(Point value)](#setRightBottom-java.awt.Point-) | Получает правый нижний угол  Point  региона  Quadrangle |
| [setRightTop(Point value)](#setRightTop-java.awt.Point-) | Получает правый верхний угол  Point  региона  Quadrangle |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого  Quadrangle . |
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


Инициализирует новый экземпляр класса  Quadrangle  с описывающими точками.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| leftTop | java.awt.Point | Точка  Point  представляет левый верхний угол Quadrangle. |
| rightTop | java.awt.Point | Точка  Point  представляет правый верхний угол Quadrangle. |
| rightBottom | java.awt.Point | Точка  Point  представляет правый нижний угол Quadrangle. |
| leftBottom | java.awt.Point | Точка  Point  представляет левый нижний угол Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Представляет класс  Quadrangle , у которого свойства оставлены неинициализированными.

Значение:  Quadrangle

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


Определяет, содержится ли указанный  Quadrangle  в этом классе  Quadrangle  или пересекается с ним.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Тестируемый  Quadrangle . |

**Returns:**
boolean - Возвращает  **true**  если  Quadrangle  содержится или пересекает этот  Quadrangle  класс; иначе,  **false** .
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
boolean - Возвращает  **true**  если точка содержится в этом  Quadrangle  классе; иначе,  **false** .
### contains(Point pt) {#contains-java.awt.Point-}
```
public boolean contains(Point pt)
```


Определяет, содержится ли указанный  Point  в этом классе  Quadrangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | java.awt.Point | Тестируемая  Point . |

**Returns:**
boolean - Возвращает  **true**  если  Point  содержится в этом  Quadrangle  классе; иначе,  **false** .
### contains(Rectangle rect) {#contains-java.awt.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Определяет, содержится ли указанный  Rectangle  в этом классе  Quadrangle  или пересекается с ним.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Тестируемый  Rectangle . |

**Returns:**
boolean - Возвращает  **true**  если  Rectangle  содержится или пересекает этот  Quadrangle  класс; иначе,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает значение, указывающее, равен ли этот экземпляр указанному значению  Quadrangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Значение  Quadrangle  для сравнения с этим экземпляром. |

**Returns:**
логический -  **true**  если obj имеет то же значение, что и этот экземпляр; иначе,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Создаёт  Rectangle , ограничивающий этот  Quadrangle

**Returns:**
java.awt.Rectangle - возвращает Rectangle, ограничивающий этот Quadrangle
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


Получает левый нижний угол  Point  региона  Quadrangle

Значение: левый нижний угол Point области Quadrangle

**Returns:**
java.awt.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Получает левый верхний угол  Point  региона  Quadrangle

Значение: левый верхний угол Point области Quadrangle

**Returns:**
java.awt.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Получает правый нижний угол  Point  региона  Quadrangle

Значение: правый нижний угол Point области Quadrangle

**Returns:**
java.awt.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Получает правый верхний угол  Point  региона  Quadrangle

Значение: правый верхний угол Point области Quadrangle

**Returns:**
java.awt.Point
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


Проверяет, имеют ли все  Point s этого  Quadrangle  нулевые значения.

Значение: Возвращает **true**, если все Point этого Quadrangle имеют нулевые значения; иначе **false**.

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


Получает левый нижний угол  Point  региона  Quadrangle

Значение: левый нижний угол Point области Quadrangle

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Point |  |

### setLeftTop(Point value) {#setLeftTop-java.awt.Point-}
```
public void setLeftTop(Point value)
```


Получает левый верхний угол  Point  региона  Quadrangle

Значение: левый верхний угол Point области Quadrangle

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Point |  |

### setRightBottom(Point value) {#setRightBottom-java.awt.Point-}
```
public void setRightBottom(Point value)
```


Получает правый нижний угол  Point  региона  Quadrangle

Значение: правый нижний угол Point области Quadrangle

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Point |  |

### setRightTop(Point value) {#setRightTop-java.awt.Point-}
```
public void setRightTop(Point value)
```


Получает правый верхний угол  Point  региона  Quadrangle

Значение: правый верхний угол Point области Quadrangle

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.awt.Point |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого  Quadrangle .

**Returns:**
java.lang.String - Строка, представляющая этот Quadrangle.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

