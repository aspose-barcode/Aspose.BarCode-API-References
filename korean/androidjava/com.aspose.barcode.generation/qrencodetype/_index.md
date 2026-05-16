---
title: QREncodeType
second_title: Aspose.BarCode for Android via Java API Reference
description: QR / MicroQR 선택자 모드.
type: docs
weight: 103
url: /ko/androidjava/com.aspose.barcode.generation/qrencodetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QREncodeType extends Enum<QREncodeType>
```

QR / MicroQR 선택 모드입니다. 표준 QR 심볼에는 FORCE\_QR을 선택하고, MicroQR에는 AUTO를 선택합니다. 가능한 경우 강력한 MicroQR 심볼 생성을 위해 FORCE\_MICRO\_QR이 사용됩니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [AUTO](#AUTO) | 모드는 MicroQR V1부터 바코드 버전 협상을 시작합니다. |
| [FORCE_MICRO_QR](#FORCE-MICRO-QR) | 모드는 MicroQR V1부터 V4까지 바코드 버전 협상을 시작합니다. |
| [FORCE_QR](#FORCE-QR) | 모드는 QR V1부터 바코드 버전 협상을 시작합니다. |
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
public static final QREncodeType AUTO
```


모드는 MicroQR V1부터 바코드 버전 협상을 시작합니다.

### FORCE_MICRO_QR {#FORCE-MICRO-QR}
```
public static final QREncodeType FORCE_MICRO_QR
```


모드는 MicroQR V1부터 V4까지 바코드 버전 협상을 시작합니다. 데이터가 MicroQR에 인코딩될 수 없으면 예외가 발생합니다.

### FORCE_QR {#FORCE-QR}
```
public static final QREncodeType FORCE_QR
```


모드는 QR V1부터 바코드 버전 협상을 시작합니다.

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
public static QREncodeType valueOf(String name)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### values() {#values--}
```
public static QREncodeType[] values()
```




**Returns:**
com.aspose.barcode.generation.QREncodeType[]
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

