---
title: Unit
second_title: Справочник API Aspose.BarCode для Android через Java
description: Указывает значение размера в разных единицах: пиксели, дюймы и т.д..
type: docs
weight: 69
url: /ru/androidjava/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

Указывает значение размера в разных единицах (пиксели, дюймы и т.д.).

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, имеют ли этот экземпляр и указанный объект, который также должен быть объектом  Unit , одинаковое значение. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Получает значение размера в единицах документа. |
| [getInches()](#getInches--) | Получает значение размера в дюймах. |
| [getMillimeters()](#getMillimeters--) | Получает значение размера в миллиметрах. |
| [getPixels()](#getPixels--) | Получает значение размера в пикселях. |
| [getPoint()](#getPoint--) | Получает значение размера в пунктах. |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | Возвращает хеш-код этого объекта. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | Устанавливает значение размера в единицах документа. |
| [setInches(float value)](#setInches-float-) | Устанавливает значение размера в дюймах. |
| [setMillimeters(float value)](#setMillimeters-float-) | Устанавливает значение размера в миллиметрах. |
| [setPixels(float value)](#setPixels-float-) | Устанавливает значение размера в пикселях. |
| [setPoint(float value)](#setPoint-float-) | Sets size value in point. |
| [toString()](#toString--) | Returns a human-readable string representation of this  Unit . |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, имеют ли этот экземпляр и указанный объект, который также должен быть объектом  Unit , одинаковое значение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | The  Unit  to compare to this instance. |

**Returns:**
boolean - true if obj is a  Unit  and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public float getDocument()
```


Получает значение размера в единицах документа.

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


Получает значение размера в дюймах.

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


Получает значение размера в миллиметрах.

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


Получает значение размера в пикселях.

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


Получает значение размера в пунктах.

**Returns:**
float
### getResolution() {#getResolution--}
```
public float getResolution()
```




**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код этого объекта.

**Returns:**
int — 32‑битный знаковый целочисленный хеш‑код.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDocument(float value) {#setDocument-float-}
```
public void setDocument(float value)
```


Устанавливает значение размера в единицах документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


Устанавливает значение размера в дюймах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


Устанавливает значение размера в миллиметрах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


Устанавливает значение размера в пикселях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


Sets size value in point.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this  Unit .

**Returns:**
java.lang.String - A string that represents this  Unit .
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dpi | float |  |

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

