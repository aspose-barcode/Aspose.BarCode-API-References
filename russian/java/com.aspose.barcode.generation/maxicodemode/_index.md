---
title: "MaxiCodeMode"
second_title: "Aspose.BarCode for Java API Reference"
description: "Содержит режимы кодирования MaxiCode."
type: docs
weight: 94
url: /ru/java/com.aspose.barcode.generation/maxicodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MaxiCodeMode extends Enum<MaxiCodeMode>
```

Содержит режимы кодирования MaxiCode.
## Поля

| Поле | Описание |
| --- | --- |
| [MODE_2](#MODE-2) | Режим 2 кодирует почтовую информацию в первом сообщении и данные во втором сообщении. |
| [MODE_3](#MODE-3) | Режим 3 кодирует почтовую информацию в первом сообщении и данные во втором сообщении. |
| [MODE_4](#MODE-4) | Режим 4 кодирует данные в первом и втором сообщениях с короткой коррекцией ECC. |
| [MODE_5](#MODE-5) | Режим 5 кодирует данные в первом и втором сообщениях с длинной коррекцией ECC. |
| [MODE_6](#MODE-6) | Режим 6 кодирует данные в первом и втором сообщениях с короткой коррекцией ECC. |
## Методы

| Метод | Описание |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
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
### MODE_2 {#MODE-2}
```
public static final MaxiCodeMode MODE_2
```


Режим 2 кодирует почтовую информацию в первом сообщении и данные во втором сообщении. Имеет 9-значный почтовый индекс и используется только в США.

### MODE_3 {#MODE-3}
```
public static final MaxiCodeMode MODE_3
```


Режим 3 кодирует почтовую информацию в первом сообщении и данные во втором сообщении. Имеет 6-символьный буквенно-цифровой почтовый индекс и используется по всему миру.

### MODE_4 {#MODE-4}
```
public static final MaxiCodeMode MODE_4
```


Режим 4 кодирует данные в первом и втором сообщениях с короткой коррекцией ECC.

### MODE_5 {#MODE-5}
```
public static final MaxiCodeMode MODE_5
```


Режим 5 кодирует данные в первом и втором сообщениях с длинной коррекцией ECC.

### MODE_6 {#MODE-6}
```
public static final MaxiCodeMode MODE_6
```


Режим 6 кодирует данные в первом и втором сообщениях с короткой коррекцией ECC. Используется для кодирования устройств.

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
public static MaxiCodeMode fromValue(int value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode)
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
public static MaxiCodeMode valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode)
### values() {#values--}
```
public static MaxiCodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.MaxiCodeMode[]
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

