---
title: AztecSymbolMode
second_title: Aspose.BarCode for Android via Java API Reference
description: Aztec 심볼 모드를 지정합니다.
type: docs
weight: 74
url: /ko/androidjava/com.aspose.barcode.generation/aztecsymbolmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum AztecSymbolMode extends Enum<AztecSymbolMode>
```

Aztec 심볼 모드를 지정합니다.

--------------------

> ```
> BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC);
>       generator.setCodeText("125");
>       generator.getParameters().getBarcode().getAztec().setAztecSymbolMode(AztecSymbolMode.RUNE);
>       generator.save("test.png");
> ```
## 필드

| 필드 | 설명 |
| --- | --- |
| [AUTO](#AUTO) | Aztec에 대해 최적 심볼(COMPACT 또는 FULL-range)을 자동으로 선택하도록 지정합니다. |
| [COMPACT](#COMPACT) | Aztec에 대한 COMPACT 심볼을 지정합니다. |
| [FULL_RANGE](#FULL-RANGE) | Aztec에 대한 FULL-range 심볼을 지정합니다. |
| [RUNE](#RUNE) | Aztec에 대한 RUNE 심볼을 지정합니다. |
## Methods

| Method | 설명 |
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


Aztec에 대해 최적 심볼(COMPACT 또는 FULL-range)을 자동으로 선택하도록 지정합니다. 기본값입니다.

### COMPACT {#COMPACT}
```
public static final AztecSymbolMode COMPACT
```


Aztec에 대한 COMPACT 심볼을 지정합니다. Aztec COMPACT 심볼은 1, 2, 3 또는 4 레이어만 허용합니다.

### FULL_RANGE {#FULL-RANGE}
```
public static final AztecSymbolMode FULL_RANGE
```


Aztec에 대한 FULL-range 심볼을 지정합니다. Aztec FULL-range 심볼은 1에서 32 레이어까지 허용합니다.

### RUNE {#RUNE}
```
public static final AztecSymbolMode RUNE
```


Aztec에 대한 RUNE 심볼을 지정합니다. Aztec Runes는 작지만 구별되는 기계 판독 마크의 시리즈입니다. 0에서 255까지의 숫자 값만 허용합니다.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

