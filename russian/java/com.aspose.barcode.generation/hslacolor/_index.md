---
title: "HslaColor"
second_title: "Aspose.BarCode for Java API Reference"
description: "Класс для представления цвета HSLA Hue Saturation Lightness Alpha"
type: docs
weight: 49
url: /ru/java/com.aspose.barcode.generation/hslacolor/
---
**Inheritance:**
java.lang.Object
```
public class HslaColor
```

Класс для представления цвета HSLA (оттенок, насыщенность, светлота, альфа).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HslaColor(int h, int s, int l, float a)](#HslaColor-int-int-int-float-) | Конструктор для HslaColor |
## Поля

| Поле | Описание |
| --- | --- |
| [A](#A) | Alpha (непрозрачность) [0.0f, 1.0f] |
| [H](#H) | Hue [0, 360] |
| [L](#L) | Lightness [0, 100] |
| [S](#S) | Saturation [0, 100] |
## Методы

| Метод | Описание |
| --- | --- |
| [convertHslaToRgba(HslaColor hslaColor)](#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-) | Использует https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HslaColor(int h, int s, int l, float a) {#HslaColor-int-int-int-float-}
```
public HslaColor(int h, int s, int l, float a)
```


Конструктор для HslaColor

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| h | int | Hue [0, 360] |
| s | int | Saturation [0, 100] |
| l | int | Lightness [0, 100] |
| a | float | Alpha (непрозрачность) [0.0f, 1.0f] |

### A {#A}
```
public float A
```


Alpha (непрозрачность) [0.0f, 1.0f]

### H {#H}
```
public final int H
```


Hue [0, 360]

### L {#L}
```
public final int L
```


Lightness [0, 100]

### S {#S}
```
public final int S
```


Saturation [0, 100]

### convertHslaToRgba(HslaColor hslaColor) {#convertHslaToRgba-com.aspose.barcode.generation.HslaColor-}
```
public static Color convertHslaToRgba(HslaColor hslaColor)
```


Использует https://en.wikipedia.org/wiki/HSL\_and\_HSV\#HSL\_to\_RGB

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hslaColor | [HslaColor](../../com.aspose.barcode.generation/hslacolor) | Цвет HSLA для преобразования |

**Returns:**
java.awt.Color — цвет с значениями RGBA
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

