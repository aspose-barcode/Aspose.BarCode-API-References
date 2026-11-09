---
title: "MaxiCodeMode"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "MaxiCode 인코딩 모드를 포함합니다."
type: docs
weight: 94
url: /ko/java/com.aspose.barcode.generation/maxicodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MaxiCodeMode extends Enum<MaxiCodeMode>
```

MaxiCode 인코딩 모드를 포함합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [MODE_2](#MODE-2) | 모드 2는 첫 번째 메시지에 우편 정보를, 두 번째 메시지에 데이터를 인코딩합니다. |
| [MODE_3](#MODE-3) | 모드 3은 첫 번째 메시지에 우편 정보를, 두 번째 메시지에 데이터를 인코딩합니다. |
| [MODE_4](#MODE-4) | 모드 4는 짧은 ECC 보정으로 첫 번째와 두 번째 메시지에 데이터를 인코딩합니다. |
| [MODE_5](#MODE-5) | 모드 5는 긴 ECC 보정으로 첫 번째와 두 번째 메시지에 데이터를 인코딩합니다. |
| [MODE_6](#MODE-6) | 모드 6은 짧은 ECC 보정으로 첫 번째와 두 번째 메시지에 데이터를 인코딩합니다. |
## 메서드

| 메서드 | 설명 |
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


모드 2는 첫 번째 메시지에 우편 정보를, 두 번째 메시지에 데이터를 인코딩합니다. 9자리 우편 코드를 가지고 있으며 미국에서만 사용됩니다.

### MODE_3 {#MODE-3}
```
public static final MaxiCodeMode MODE_3
```


모드 3은 첫 번째 메시지에 우편 정보를, 두 번째 메시지에 데이터를 인코딩합니다. 6자리 알파벳-숫자 조합 우편 코드를 가지고 있으며 전 세계에서 사용됩니다.

### MODE_4 {#MODE-4}
```
public static final MaxiCodeMode MODE_4
```


모드 4는 짧은 ECC 보정으로 첫 번째와 두 번째 메시지에 데이터를 인코딩합니다.

### MODE_5 {#MODE-5}
```
public static final MaxiCodeMode MODE_5
```


모드 5는 긴 ECC 보정으로 첫 번째와 두 번째 메시지에 데이터를 인코딩합니다.

### MODE_6 {#MODE-6}
```
public static final MaxiCodeMode MODE_6
```


모드 6은 짧은 ECC 보정으로 첫 번째와 두 번째 메시지에 데이터를 인코딩합니다. 장치를 인코딩하는 데 사용됩니다.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static MaxiCodeMode fromValue(int value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

