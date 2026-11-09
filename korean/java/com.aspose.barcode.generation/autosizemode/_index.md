---
title: "AutoSizeMode"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "자동 크기 조정 모드의 다양한 유형을 지정합니다."
type: docs
weight: 70
url: /ko/java/com.aspose.barcode.generation/autosizemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum AutoSizeMode extends Enum<AutoSizeMode>
```

자동 크기 조정 모드의 다양한 유형을 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [INTERPOLATION](#INTERPOLATION) | 바코드를 지정된 크기로 크기 조정합니다. |
| [NEAREST](#NEAREST) | 바코드를 ImageWidth 및 ImageHeight 속성으로 지정된 가장 가까운 최소 크기로 크기 조정합니다. |
| [NONE](#NONE) | 자동 크기 조정이 비활성화되었습니다. |
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
### INTERPOLATION {#INTERPOLATION}
```
public static final AutoSizeMode INTERPOLATION
```


바코드를 지정된 크기로 크기 조정합니다. 크기는 ImageWidth 및 ImageHeight 속성으로 지정할 수 있습니다. 스케일링 후 생성된 바코드가 유효하지 않을 수 있습니다 (읽을 수 없음).

### NEAREST {#NEAREST}
```
public static final AutoSizeMode NEAREST
```


바코드를 ImageWidth 및 ImageHeight 속성으로 지정된 가장 가까운 최소 크기로 크기 조정합니다. 기본 종횡비를 유지합니다.

### NONE {#NONE}
```
public static final AutoSizeMode NONE
```


자동 크기 조정이 비활성화되었습니다.

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
public static AutoSizeMode fromValue(int value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
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
public static AutoSizeMode valueOf(String name)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### values() {#values--}
```
public static AutoSizeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.AutoSizeMode[]
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

