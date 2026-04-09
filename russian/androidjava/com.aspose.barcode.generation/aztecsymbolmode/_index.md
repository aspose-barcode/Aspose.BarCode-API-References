---
title: AztecSymbolMode
second_title: Справочник API Aspose.BarCode для Android через Java
description: Указывает режим символов Aztec.
type: docs
weight: 74
url: /ru/androidjava/com.aspose.barcode.generation/aztecsymbolmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum AztecSymbolMode extends Enum<AztecSymbolMode>
```

Указывает режим символов Aztec.

--------------------

> ```
> BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC);
>       generator.setCodeText("125");
>       generator.getParameters().getBarcode().getAztec().setAztecSymbolMode(AztecSymbolMode.RUNE);
>       generator.save("test.png");
> ```
## Поля

| Поле | Описание |
| --- | --- |
| [AUTO](#AUTO) | Указывает автоматически выбирать лучший символ (COMPACT или FULL-range) для Aztec. |
| [COMPACT](#COMPACT) | Указывает символ COMPACT для Aztec. |
| [FULL_RANGE](#FULL-RANGE) | Указывает символ FULL-range для Aztec. |
| [RUNE](#RUNE) | Указывает символ RUNE для Aztec. |
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
public static final AztecSymbolMode AUTO
```


Указывает автоматически выбирать лучший символ (COMPACT или FULL-range) для Aztec. Это значение по умолчанию.

### COMPACT {#COMPACT}
```
public static final AztecSymbolMode COMPACT
```


Указывает символ COMPACT для Aztec. Символ Aztec COMPACT допускает только 1, 2, 3 или 4 слоя.

### FULL_RANGE {#FULL-RANGE}
```
public static final AztecSymbolMode FULL_RANGE
```


Указывает символ FULL-range для Aztec. Символ Aztec FULL-range допускает от 1 до 32 слоёв.

### RUNE {#RUNE}
```
public static final AztecSymbolMode RUNE
```


Указывает символ RUNE для Aztec. Aztec Runes — это серия небольших, но отличимых машинно‑читаемых меток. Они допускают только числовые значения от 0 до 255.

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
public static AztecSymbolMode valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode)
### values() {#values--}
```
public static AztecSymbolMode[] values()
```




**Returns:**
com.aspose.barcode.generation.AztecSymbolMode[]
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

