---
title: QRErrorLevel
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: مستوى تصحيح الأخطاء Reed-Solomon.
type: docs
weight: 104
url: /ar/androidjava/com.aspose.barcode.generation/qrerrorlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QRErrorLevel extends Enum<QRErrorLevel>
```

مستوى تصحيح الأخطاء Reed-Solomon. من منخفض إلى عالي: LEVEL\_L, LEVEL\_M, LEVEL\_Q, LEVEL\_H.
## الحقول

| حقل | الوصف |
| --- | --- |
| [LEVEL_H](#LEVEL-H) | يمكن تطبيق تصحيح الأخطاء المستوى H على الباركود QR وRectMicroQR. |
| [LEVEL_L](#LEVEL-L) | يمكن تطبيق تصحيح الأخطاء المستوى L على الباركود QR وMicroQR. |
| [LEVEL_M](#LEVEL-M) | يمكن تطبيق تصحيح الأخطاء المستوى M على باركود QR، باركود RectMicroQR، وباركود MicroQR بالإصدارات من M2 إلى M4. |
| [LEVEL_Q](#LEVEL-Q) | يمكن تطبيق تصحيح الأخطاء المستوى Q على باركود QR وباركود MicroQR بالإصدار M4. |
## Methods

| Method | الوصف |
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
### LEVEL_H {#LEVEL-H}
```
public static final QRErrorLevel LEVEL_H
```


يمكن تطبيق تصحيح الأخطاء المستوى H على باركود QR وRectMicroQR. يسمح باستعادة 30% من نص الكود.

### LEVEL_L {#LEVEL-L}
```
public static final QRErrorLevel LEVEL_L
```


يمكن تطبيق تصحيح الأخطاء المستوى L على باركود QR وMicroQR. يسمح باستعادة 7% من نص الكود.

### LEVEL_M {#LEVEL-M}
```
public static final QRErrorLevel LEVEL_M
```


يمكن تطبيق تصحيح الأخطاء المستوى M على باركود QR، باركود RectMicroQR، وباركود MicroQR بالإصدارات من M2 إلى M4. يسمح باستعادة 15% من نص الكود.

### LEVEL_Q {#LEVEL-Q}
```
public static final QRErrorLevel LEVEL_Q
```


يمكن تطبيق تصحيح الأخطاء المستوى Q على باركود QR وباركود MicroQR بالإصدار M4. يسمح باستعادة 25% من نص الكود.

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
### fromValue(int value) {#fromValue-int-}
```
public static QRErrorLevel fromValue(int value)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

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

