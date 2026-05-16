---
title: EnableChecksum
second_title: Aspose.BarCode for Android via Java API Reference
description: 1D 바코드 생성 시 체크섬을 활성화합니다.
type: docs
weight: 86
url: /ko/androidjava/com.aspose.barcode.generation/enablechecksum/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EnableChecksum extends Enum<EnableChecksum>
```

1D 바코드 생성 시 체크섬을 활성화합니다.

기본값은 체크섬이 반드시 포함되어야 하는 심볼에 대해서는 Yes로, 체크섬이 선택적인 경우에는 No로 처리됩니다.

체크섬은 사용되지 않음: Codabar

체크섬 사용 가능: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

체크섬이 항상 사용됨: 나머지 심볼
## 필드

| 필드 | 설명 |
| --- | --- |
| [DEFAULT](#DEFAULT) | 명세서에서 체크섬이 요구되는 경우 - 첨부됩니다. |
| [NO](#NO) | 체크섬을 사용하지 마십시오. |
| [YES](#YES) | 가능하면 항상 체크섬을 사용하십시오. |
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
### DEFAULT {#DEFAULT}
```
public static final EnableChecksum DEFAULT
```


명세서에서 체크섬이 요구되는 경우 - 첨부됩니다.

### NO {#NO}
```
public static final EnableChecksum NO
```


체크섬을 사용하지 마십시오.

### YES {#YES}
```
public static final EnableChecksum YES
```


가능하면 항상 체크섬을 사용하십시오.

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
public static EnableChecksum valueOf(String name)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[EnableChecksum](../../com.aspose.barcode.generation/enablechecksum)
### values() {#values--}
```
public static EnableChecksum[] values()
```




**Returns:**
com.aspose.barcode.generation.EnableChecksum[]
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

