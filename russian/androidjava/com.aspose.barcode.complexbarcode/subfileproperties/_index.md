---
title: USADriveIdCodetext.SubfileProperties
second_title: Справочник API Aspose.BarCode для Android через Java
description: Смещение и длина свойств подфайла USA DL устанавливаются автоматически.
type: docs
weight: 12
url: /ru/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

Свойства подпроекта DL США, смещение и длина задаются автоматически.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 Эти байты содержат 4‑значное числовое значение, указывающее длину Subfile в байтах. Терминатор сегмента должен быть включён при расчёте длины подфайла. Терминатор сегмента = 1. |
| [getOffset()](#getOffset--) | 4‑значное числовое значение, указывающее количество байтов от начала файла до места, где находятся данные, относящиеся к конкретному sub‑file. Первый байт в файле находится по смещению 0. |
| [getType()](#getType--) | 2‑байтовый тип subfile, например "DL" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 Эти байты содержат 4‑значное числовое значение, указывающее длину Subfile в байтах. Терминатор сегмента должен быть включён при расчёте длины подфайла. Терминатор сегмента = 1. |
| [setOffset(int value)](#setOffset-int-) | 4‑значное числовое значение, указывающее количество байтов от начала файла до места, где находятся данные, относящиеся к конкретному sub‑file. Первый байт в файле находится по смещению 0. |
| [setType(String value)](#setType-java.lang.String-) | 2‑байтовый тип subfile, например "DL" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | java.lang.String |  |

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
### getLength() {#getLength--}
```
public final int getLength()
```


4 Эти байты содержат 4‑значное числовое значение, указывающее длину Subfile в байтах. Терминатор сегмента должен быть включён при расчёте длины подфайла. Терминатор сегмента = 1. Каждый subfile должен начинаться с двухсимвольного Subfile Type, и эти два символа также должны быть включены в длину.

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


4‑значное числовое значение, указывающее количество байтов от начала файла до места, где находятся данные, относящиеся к конкретному sub‑file. Первый байт в файле находится по смещению 0.

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


2‑байтовый тип subfile, например "DL"

**Returns:**
java.lang.String
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




### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


4 Эти байты содержат 4‑значное числовое значение, указывающее длину Subfile в байтах. Терминатор сегмента должен быть включён при расчёте длины подфайла. Терминатор сегмента = 1. Каждый subfile должен начинаться с двухсимвольного Subfile Type, и эти два символа также должны быть включены в длину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


4‑значное числовое значение, указывающее количество байтов от начала файла до места, где находятся данные, относящиеся к конкретному sub‑file. Первый байт в файле находится по смещению 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


2‑байтовый тип subfile, например "DL"

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

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

