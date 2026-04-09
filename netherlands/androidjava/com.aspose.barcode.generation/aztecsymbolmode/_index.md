---
title: AztecSymbolMode
second_title: Aspose.BarCode for Android via Java API-referentie
description: Specificeert de Aztec-symboolmodus.
type: docs
weight: 74
url: /nl/androidjava/com.aspose.barcode.generation/aztecsymbolmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum AztecSymbolMode extends Enum<AztecSymbolMode>
```

Specificeert de Aztec-symboolmodus.

--------------------

> ```
> BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC);
>       generator.setCodeText("125");
>       generator.getParameters().getBarcode().getAztec().setAztecSymbolMode(AztecSymbolMode.RUNE);
>       generator.save("test.png");
> ```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [AUTO](#AUTO) | Specificeert om automatisch het beste symbool (COMPACT of FULL-range) voor Aztec te selecteren. |
| [COMPACT](#COMPACT) | Specificeert het COMPACT-symbool voor Aztec. |
| [FULL_RANGE](#FULL-RANGE) | Specificeert het FULL-range symbool voor Aztec. |
| [RUNE](#RUNE) | Specificeert het RUNE-symbool voor Aztec. |
## Methods

| Method | Beschrijving |
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


Specificeert om automatisch het beste symbool (COMPACT of FULL-range) voor Aztec te selecteren. Dit is de standaardwaarde.

### COMPACT {#COMPACT}
```
public static final AztecSymbolMode COMPACT
```


Specificeert het COMPACT-symbool voor Aztec. Het Aztec COMPACT-symbool staat alleen 1, 2, 3 of 4 lagen toe.

### FULL_RANGE {#FULL-RANGE}
```
public static final AztecSymbolMode FULL_RANGE
```


Specificeert het FULL-range symbool voor Aztec. Het Aztec FULL-range-symbool staat van 1 tot 32 lagen toe.

### RUNE {#RUNE}
```
public static final AztecSymbolMode RUNE
```


Specificeert het RUNE-symbool voor Aztec. Aztec Runes zijn een reeks kleine maar onderscheidende machinaal leesbare tekens. Het staat alleen numerieke waarden van 0 tot 255 toe.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

