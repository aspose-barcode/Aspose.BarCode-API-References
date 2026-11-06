---
title: "Code128SubType"
second_title: "Aspose.BarCode for Android via Java API 참조"
description: "Code128 하위 집합 유형을 포함합니다"
type: docs
weight: 51
url: /ko/androidjava/com.aspose.barcode.barcoderecognition/code128subtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Code128SubType extends Enum<Code128SubType>
```

Code128 하위 집합 유형을 포함합니다
## 필드

| 필드 | 설명 |
| --- | --- |
| [CODE_SET_A](#CODE-SET-A) | ASCII 문자 00부터 95까지 (0\u20139, A\u2013Z 및 제어 코드), 특수 문자 및 FNC 1\u20134. |
| [CODE_SET_B](#CODE-SET-B) | ASCII 문자 32에서 127까지 (0\u20139, A\u2013Z, a\u2013z), 특수 문자 및 FNC 1\u20134. |
| [CODE_SET_C](#CODE-SET-C) | 00\u201399 (단일 코드 포인트로 두 자리 숫자를 인코딩) 및 FNC1. |
## 메서드

| 메서드 | 설명 |
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
### CODE_SET_A {#CODE-SET-A}
```
public static final Code128SubType CODE_SET_A
```


ASCII 문자 00부터 95까지 (0\u20139, A\u2013Z 및 제어 코드), 특수 문자 및 FNC 1\u20134.

### CODE_SET_B {#CODE-SET-B}
```
public static final Code128SubType CODE_SET_B
```


ASCII 문자 32에서 127까지 (0\u20139, A\u2013Z, a\u2013z), 특수 문자 및 FNC 1\u20134.

### CODE_SET_C {#CODE-SET-C}
```
public static final Code128SubType CODE_SET_C
```


00\u201399 (단일 코드 포인트로 두 자리 숫자를 인코딩) 및 FNC1.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static Code128SubType fromValue(int value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

**Returns:**
[Code128SubType](../../com.aspose.barcode.barcoderecognition/code128subtype)
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
public static Code128SubType valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Code128SubType](../../com.aspose.barcode.barcoderecognition/code128subtype)
### values() {#values--}
```
public static Code128SubType[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.Code128SubType[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

