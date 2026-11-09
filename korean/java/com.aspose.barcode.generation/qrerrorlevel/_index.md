---
title: "QRErrorLevel"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "Reed-Solomon 오류 정정 수준."
type: docs
weight: 101
url: /ko/java/com.aspose.barcode.generation/qrerrorlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QRErrorLevel extends Enum<QRErrorLevel>
```

Reed-Solomon 오류 정정 수준. 낮은 수준부터 높은 수준까지: LEVEL\_L, LEVEL\_M, LEVEL\_Q, LEVEL\_H.
## 필드

| 필드 | 설명 |
| --- | --- |
| [LEVEL_H](#LEVEL-H) | 오류 정정 레벨 H는 QR 및 RectMicroQR 바코드에 적용될 수 있습니다. |
| [LEVEL_L](#LEVEL-L) | 오류 정정 레벨 L은 QR 및 MicroQR 바코드에 적용될 수 있습니다. |
| [LEVEL_M](#LEVEL-M) | 오류 정정 레벨 M은 QR 바코드, RectMicroQR 바코드 및 M2에서 M4 버전의 MicroQR 바코드에 적용될 수 있습니다. |
| [LEVEL_Q](#LEVEL-Q) | 오류 정정 레벨 Q는 QR 바코드와 M4 버전의 MicroQR 바코드에 적용될 수 있습니다. |
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
### LEVEL_H {#LEVEL-H}
```
public static final QRErrorLevel LEVEL_H
```


오류 정정 레벨 H는 QR 및 RectMicroQR 바코드에 적용될 수 있습니다. 코드 텍스트의 30%를 복구할 수 있습니다

### LEVEL_L {#LEVEL-L}
```
public static final QRErrorLevel LEVEL_L
```


오류 정정 레벨 L은 QR 및 MicroQR 바코드에 적용될 수 있습니다. 코드 텍스트의 7%를 복구할 수 있습니다.

### LEVEL_M {#LEVEL-M}
```
public static final QRErrorLevel LEVEL_M
```


오류 정정 레벨 M은 QR 바코드, RectMicroQR 바코드 및 M2에서 M4 버전의 MicroQR 바코드에 적용될 수 있습니다. 코드 텍스트의 15%를 복구할 수 있습니다

### LEVEL_Q {#LEVEL-Q}
```
public static final QRErrorLevel LEVEL_Q
```


오류 정정 레벨 Q는 QR 바코드와 M4 버전의 MicroQR 바코드에 적용될 수 있습니다. 코드 텍스트의 25%를 복구할 수 있습니다

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
public static QRErrorLevel fromValue(int value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

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

