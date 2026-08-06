---
title: CMYKColor
second_title: Справочник API Aspose.BarCode для Android через Java
description: Класс для цвета CMYK.
type: docs
weight: 19
url: /ru/androidjava/com.aspose.barcode.generation/cmykcolor/
---
**Inheritance:**
java.lang.Object
```
public class CMYKColor
```

Класс для цвета CMYK. Null означает, что CMYK не используется, используется цвет RGB по умолчанию.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CMYKColor(int c, int m, int y, int k)](#CMYKColor-int-int-int-int-) | Инициализирует новый экземпляр класса  CMYKColor  из значений CMYK. |
## Поля

| Поле | Описание |
| --- | --- |
| [C](#C) |  |
| [K](#K) |  |
| [M](#M) |  |
| [Y](#Y) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Сравнивает, являются ли значения цветов одинаковыми |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Хеш-код объекта CMYKColor |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CMYKColor(int c, int m, int y, int k) {#CMYKColor-int-int-int-int-}
```
public CMYKColor(int c, int m, int y, int k)
```


Инициализирует новый экземпляр класса  CMYKColor  из значений CMYK. Значения CMYK находятся в диапазоне 0-100.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| c | int | Значение Cyan [0, 100] |
| m | int | Значение Magenta [0, 100] |
| y | int | Значение Yellow [0, 100] |
| k | int | Значение Black [0, 100] |

### C {#C}
```
public float C
```


### K {#K}
```
public float K
```


### M {#M}
```
public float M
```


### Y {#Y}
```
public float Y
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Сравнивает, являются ли значения цветов одинаковыми

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | CMYKColor для сравнения |

**Returns:**
boolean - Являются ли значения одинаковыми
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


Хеш-код объекта CMYKColor

**Returns:**
int - Хеш-код объекта CMYKColor
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

