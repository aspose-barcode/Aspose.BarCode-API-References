---
title: HanXinModes
second_title: Справочник API Aspose.BarCode для Android через Java
description: Режим кодирования Han Xin Code.
type: docs
weight: 91
url: /ru/androidjava/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Режим кодирования Han Xin Code. Рекомендуется использовать Auto с символами ASCII / китайскими или Unicode для символов Unicode.
## Поля

| Поле | Описание |
| --- | --- |
| [AUTO](#AUTO) | Последовательность режимов Numeric, Text, ECI, Binary Bytes и 4 GB18030 меняется автоматически. |
| [BINARY](#BINARY) | Режим Binary byte кодирует двоичные данные в любой форме и записывает их в их двоичный байт. |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Каждый общий китайский символ в регионе One представляется 12 битами. |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Каждый общий китайский символ в регионе Two представляется 12 битами. |
| [ECI](#ECI) | Режим Extended Channel Interpretation (ECI) |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | Каждый символ GB18030 4‑байтового региона представляется 21 битом. |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | Каждый символ GB18030 2‑байтового региона представляется 15 битами. |
| [GS_1](#GS-1) | Режим GS1 указывает, что данные, представленные в Han Xin Code, являются данными GS1 системы, определёнными в GS1 General Specification. |
| [NUMERIC](#NUMERIC) | Режим Numeric кодирует данные из набора десятичных цифр (цифры 0‑9, байтовые значения 30HEX‑39HEX). |
| [TEXT](#TEXT) | Режим Text кодирует данные из общих символов, определённых в ISO/IEC 646, т.е. |
| [UNICODE](#UNICODE) | Режим Unicode разрабатывает способ представления любых текстовых данных, ссылающихся на кодировку/набор символов UTF8 в Han Xin Code. |
| [URI](#URI) | Режим URI указывает, что данные, представленные в Han Xin Code, являются ссылкой Uniform Resource Identifier (URI) согласно RFC 3986. |
## Методы

| Метод | Описание |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
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
### AUTO {#AUTO}
```
public static final HanXinModes AUTO
```


Последовательность режимов Numeric, Text, ECI, Binary Bytes и 4 GB18030 меняется автоматически.

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


Режим Binary byte кодирует двоичные данные в любой форме и записывает их в их двоичный байт. Каждый байт в режиме Binary Byte представляется 8 битами.

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Каждый общий китайский символ в регионе One представляется 12 битами. Общие китайские символы в регионе One включают символы, у которых первое байтовое значение находится в диапазоне B0HEX‑D7HEX и второе байтовое значение — в диапазоне A1HEX‑FEHEX (3760 символов), а также символы, у которых первое байтовое значение находится в диапазоне A1HEX‑A3HEX и второе байтовое значение — в диапазоне A1HEX‑FEHEX (282 символа), и символы, у которых байтовые значения находятся в диапазоне A8A1HEX‑A8C0HEX (32 символа).

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Каждый общий китайский символ в регионе Two представляется 12 битами. Общие китайские символы в регионе Two включают символы, у которых первое байтовое значение находится в диапазоне D8HEX‑F7HEX, а второе байтовое значение — в диапазоне A1HEX‑FEHEX.

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Режим Extended Channel Interpretation (ECI)

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


Каждый символ GB18030 4‑байтового региона представляется 21 битом. Регион GB18030 4‑байтовый кодирует данные из всех символов в 4‑байтовом регионе GB18030 (т.е. символы, у которых первое байтовое значение находится в диапазоне 81HEX‑FEHEX, второе байтовое значение — в диапазоне 30HEX‑39HEX, третье байтовое значение — в диапазоне 81HEX‑FEHEX, и четвёртое байтовое значение — в диапазоне 30HEX‑39HEX).

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


Каждый символ GB18030 2‑байтового региона представляется 15 битами. Регион GB18030 2‑байтовый кодирует данные из всех символов (включая общие китайские символы в регионах One и Two) в двойном байтовом регионе GB18030, (т.е. китайские символы, у которых первое байтовое значение находится в диапазоне 81HEX‑FEHEX, а второе байтовое значение — в диапазоне 40HEX‑7EHEX или 80HEX‑FEHEX).

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


Режим GS1 указывает, что данные, представленные в Han Xin Code, являются данными GS1 системы, определёнными в GS1 General Specification. Пример входной строки: "(01)03453120000011(17)191125(10)ABCD1234(21)10".

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


Режим Numeric кодирует данные из набора десятичных цифр (цифры 0‑9, байтовые значения 30HEX‑39HEX). Обычно 3 символа данных представляются 10 битами.

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


Режим Text кодирует данные из общих символов, определённых в ISO/IEC 646, т.е. байтовые значения 00 HEX‑1B HEX и 20 HEX‑7F HEX.

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Режим Unicode разрабатывает способ представления любых текстовых данных, ссылающихся на кодировку/набор символов UTF8 в Han Xin Code.

### URI {#URI}
```
public static final HanXinModes URI
```


Режим URI указывает, что данные, представленные в Han Xin Code, являются ссылкой Uniform Resource Identifier (URI) согласно RFC 3986.

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
public static HanXinModes valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
com.aspose.barcode.generation.HanXinModes
### values() {#values--}
```
public static HanXinModes[] values()
```




**Returns:**
com.aspose.barcode.generation.HanXinModes[]
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

