---
title: "QrExtCompactionMode"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "QrExtCodetextBuilder에 의해 추가된 코드텍스트에 대한 QR 압축 모드를 지정합니다."
type: docs
weight: 103
url: /ko/java/com.aspose.barcode.generation/qrextcompactionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QrExtCompactionMode extends Enum<QrExtCompactionMode>
```

QrExtCodetextBuilder에 의해 추가된 코드텍스트에 대한 QR 압축 모드를 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [ALPHA_NUMERIC](#ALPHA-NUMERIC) | QR 알파벳-숫자 모드로 코드 텍스트를 인코딩합니다. |
| [AUTO](#AUTO) | 인코더는 가장 효율적인 QR 압축 모드를 자동으로 선택합니다. |
| [BYTES](#BYTES) | QR 바이트 모드로 코드 텍스트를 인코딩합니다. |
| [KANJI](#KANJI) | QR 한자 모드로 코드 텍스트를 인코딩합니다. |
| [NUMERIC](#NUMERIC) | QR 숫자 모드로 코드 텍스트를 인코딩합니다. |
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
### ALPHA_NUMERIC {#ALPHA-NUMERIC}
```
public static final QrExtCompactionMode ALPHA_NUMERIC
```


QR 알파벳-숫자 모드로 코드 텍스트를 인코딩합니다.

### AUTO {#AUTO}
```
public static final QrExtCompactionMode AUTO
```


인코더는 가장 효율적인 QR 압축 모드를 자동으로 선택합니다.

### BYTES {#BYTES}
```
public static final QrExtCompactionMode BYTES
```


QR 바이트 모드로 코드 텍스트를 인코딩합니다.

### KANJI {#KANJI}
```
public static final QrExtCompactionMode KANJI
```


QR 한자 모드로 코드 텍스트를 인코딩합니다.

### NUMERIC {#NUMERIC}
```
public static final QrExtCompactionMode NUMERIC
```


QR 숫자 모드로 코드 텍스트를 인코딩합니다. 0-9 숫자만 허용됩니다.

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
public static QrExtCompactionMode fromValue(int value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

**Returns:**
[QrExtCompactionMode](../../com.aspose.barcode.generation/qrextcompactionmode)
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
public static QrExtCompactionMode valueOf(String name)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[QrExtCompactionMode](../../com.aspose.barcode.generation/qrextcompactionmode)
### values() {#values--}
```
public static QrExtCompactionMode[] values()
```




**Returns:**
com.aspose.barcode.generation.QrExtCompactionMode[]
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

