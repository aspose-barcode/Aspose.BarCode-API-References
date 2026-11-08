---
title: "QRErrorLevel"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "مستوى تصحيح الأخطاء Reed-Solomon."
type: docs
weight: 101
url: /ar/java/com.aspose.barcode.generation/qrerrorlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QRErrorLevel extends Enum<QRErrorLevel>
```

مستوى تصحيح الأخطاء Reed‑Solomon. من منخفض إلى عالي: LEVEL\_L، LEVEL\_M، LEVEL\_Q، LEVEL\_H.
## الحقول

| حقل | الوصف |
| --- | --- |
| [LEVEL_H](#LEVEL-H) | يمكن تطبيق مستوى تصحيح الأخطاء H على باركودات QR وRectMicroQR. |
| [LEVEL_L](#LEVEL-L) | يمكن تطبيق مستوى تصحيح الأخطاء L على باركودات QR وMicroQR. |
| [LEVEL_M](#LEVEL-M) | يمكن تطبيق مستوى تصحيح الأخطاء M على باركودات QR، وباركودات RectMicroQR، وباركودات MicroQR بالإصدارات من M2 إلى M4. |
| [LEVEL_Q](#LEVEL-Q) | يمكن تطبيق مستوى تصحيح الأخطاء Q على باركودات QR وباركودات MicroQR بالإصدار M4. |
## الدوال

| دالة | الوصف |
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


يمكن تطبيق مستوى تصحيح الأخطاء H على باركودات QR وRectMicroQR. يسمح باستعادة 30٪ من نص الرمز.

### LEVEL_L {#LEVEL-L}
```
public static final QRErrorLevel LEVEL_L
```


يمكن تطبيق مستوى تصحيح الأخطاء L على باركودات QR وMicroQR. يسمح باستعادة 7٪ من نص الرمز.

### LEVEL_M {#LEVEL-M}
```
public static final QRErrorLevel LEVEL_M
```


يمكن تطبيق مستوى تصحيح الأخطاء M على باركودات QR، وباركودات RectMicroQR، وباركودات MicroQR بالإصدارات من M2 إلى M4. يسمح باستعادة 15٪ من نص الرمز.

### LEVEL_Q {#LEVEL-Q}
```
public static final QRErrorLevel LEVEL_Q
```


يمكن تطبيق مستوى تصحيح الأخطاء Q على باركودات QR وباركودات MicroQR بالإصدار M4. يسمح باستعادة 25٪ من نص الرمز.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
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
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static QRErrorLevel fromValue(int value)
```




**Parameters:**
| معامل | النوع | الوصف |
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
| معامل | النوع | الوصف |
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
public final native void wait(long arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

