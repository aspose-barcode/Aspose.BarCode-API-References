---
title: PatchFormat
second_title: Справочник API Aspose.BarCode для Android через Java
description: Формат PatchCode.
type: docs
weight: 97
url: /ru/androidjava/com.aspose.barcode.generation/patchformat/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PatchFormat extends Enum<PatchFormat>
```

Формат PatchCode. Выберите PatchOnly для генерации одного PatchCode. Используйте формат page для создания страницы Patch с PatchCodes в качестве границ.
## Поля

| Поле | Описание |
| --- | --- |
| [A4](#A4) | Создаёт страницу формата A4 с PatchCodes в качестве границ и необязательным QR в центре. |
| [A4_LANDSCAPE](#A4-LANDSCAPE) | Создаёт страницу формата A4 альбомной ориентации с PatchCodes в качестве границ и необязательным QR в центре. |
| [PATCH_ONLY](#PATCH-ONLY) | Создаёт только PatchCode. |
| [US_LETTER](#US-LETTER) | Создаёт страницу формата US Letter с PatchCodes в качестве границ и необязательным QR в центре. |
| [US_LETTER_LANDSCAPE](#US-LETTER-LANDSCAPE) | Создаёт страницу формата US Letter альбомной ориентации с PatchCodes в качестве границ и необязательным QR в центре. |
## Методы

| Метод | Описание |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### A4 {#A4}
```
public static final PatchFormat A4
```


Создаёт страницу формата A4 с PatchCodes в качестве границ и необязательным QR в центре.

### A4_LANDSCAPE {#A4-LANDSCAPE}
```
public static final PatchFormat A4_LANDSCAPE
```


Создаёт страницу формата A4 альбомной ориентации с PatchCodes в качестве границ и необязательным QR в центре.

### PATCH_ONLY {#PATCH-ONLY}
```
public static final PatchFormat PATCH_ONLY
```


Создаёт только PatchCode.

### US_LETTER {#US-LETTER}
```
public static final PatchFormat US_LETTER
```


Создаёт страницу формата US Letter с PatchCodes в качестве границ и необязательным QR в центре.

### US_LETTER_LANDSCAPE {#US-LETTER-LANDSCAPE}
```
public static final PatchFormat US_LETTER_LANDSCAPE
```


Создаёт страницу формата US Letter альбомной ориентации с PatchCodes в качестве границ и необязательным QR в центре.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PatchFormat valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PatchFormat](../../com.aspose.barcode.generation/patchformat)
### values() {#values--}
```
public static PatchFormat[] values()
```




**Returns:**
com.aspose.barcode.generation.PatchFormat[]
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

