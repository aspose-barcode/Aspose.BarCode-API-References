---
title: QRErrorLevel
second_title: Справочник API Aspose.BarCode для Android через Java
description: Уровень коррекции ошибок Рида-Соломона.
type: docs
weight: 104
url: /ru/androidjava/com.aspose.barcode.generation/qrerrorlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QRErrorLevel extends Enum<QRErrorLevel>
```

Уровень коррекции ошибок Рида-Соломона. От низкого к высокому: LEVEL\_L, LEVEL\_M, LEVEL\_Q, LEVEL\_H.
## Поля

| Поле | Описание |
| --- | --- |
| [LEVEL_H](#LEVEL-H) | Коррекция ошибок уровня H может применяться к штрих-кодам QR и RectMicroQR. |
| [LEVEL_L](#LEVEL-L) | Коррекция ошибок уровня L может применяться к штрих-кодам QR и MicroQR. |
| [LEVEL_M](#LEVEL-M) | Коррекция ошибок уровня M может применяться к штрих-кодам QR, RectMicroQR и MicroQR с версиями от M2 до M4. |
| [LEVEL_Q](#LEVEL-Q) | Коррекция ошибок уровня Q может применяться к штрих-кодам QR и MicroQR с версией M4. |
## Методы

| Метод | Описание |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
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
### LEVEL_H {#LEVEL-H}
```
public static final QRErrorLevel LEVEL_H
```


Коррекция ошибок уровня H может применяться к штрих-кодам QR и RectMicroQR. Позволяет восстановить 30% текста кода.

### LEVEL_L {#LEVEL-L}
```
public static final QRErrorLevel LEVEL_L
```


Коррекция ошибок уровня L может применяться к штрих-кодам QR и MicroQR. Позволяет восстановить 7% текста кода.

### LEVEL_M {#LEVEL-M}
```
public static final QRErrorLevel LEVEL_M
```


Коррекция ошибок уровня M может применяться к штрих-кодам QR, RectMicroQR и MicroQR с версиями от M2 до M4. Позволяет восстановить 15% текста кода.

### LEVEL_Q {#LEVEL-Q}
```
public static final QRErrorLevel LEVEL_Q
```


Коррекция ошибок уровня Q может применяться к штрих-кодам QR и MicroQR с версией M4. Позволяет восстановить 25% текста кода.

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
### fromValue(int value) {#fromValue-int-}
```
public static QRErrorLevel fromValue(int value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
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
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
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
public static QRErrorLevel valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### values() {#values--}
```
public static QRErrorLevel[] values()
```




**Returns:**
com.aspose.barcode.generation.QRErrorLevel[]
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

