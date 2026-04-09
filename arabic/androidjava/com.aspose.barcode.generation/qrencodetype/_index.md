---
title: QREncodeType
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: وضع اختيار QR / MicroQR.
type: docs
weight: 103
url: /ar/androidjava/com.aspose.barcode.generation/qrencodetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QREncodeType extends Enum<QREncodeType>
```

وضع محدد QR / MicroQR. اختر FORCE\\_QR للرموز QR القياسية، AUTO لـ MicroQR. يُستخدم FORCE\\_MICRO\\_QR لتوليد رمز MicroQR قوي إذا كان ذلك ممكنًا.
## الحقول

| حقل | الوصف |
| --- | --- |
| [AUTO](#AUTO) | يبدأ الوضع التفاوض على إصدار الباركود من MicroQR V1 |
| [FORCE_MICRO_QR](#FORCE-MICRO-QR) | يبدأ الوضع التفاوض على إصدار الباركود من من MicroQR V1 إلى V4. |
| [FORCE_QR](#FORCE-QR) | يبدأ الوضع التفاوض على إصدار الباركود من QR V1 |
## Methods

| Method | الوصف |
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


يبدأ الوضع التفاوض على إصدار الباركود من MicroQR V1

### FORCE_MICRO_QR {#FORCE-MICRO-QR}
```
public static final QREncodeType FORCE_MICRO_QR
```


يبدأ الوضع التفاوض على إصدار الباركود من من MicroQR V1 إلى V4. إذا تعذر ترميز البيانات إلى MicroQR، يتم إلقاء استثناء.

### FORCE_QR {#FORCE-QR}
```
public static final QREncodeType FORCE_QR
```


يبدأ الوضع التفاوض على إصدار الباركود من QR V1

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
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
| Parameter | Type | الوصف |
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
| Parameter | Type | الوصف |
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
| Parameter | Type | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

