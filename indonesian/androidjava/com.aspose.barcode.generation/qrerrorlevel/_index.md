---
title: QRErrorLevel
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Tingkat koreksi kesalahan Reed-Solomon.
type: docs
weight: 104
url: /id/androidjava/com.aspose.barcode.generation/qrerrorlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QRErrorLevel extends Enum<QRErrorLevel>
```

Tingkat koreksi kesalahan Reed-Solomon. Dari rendah ke tinggi: LEVEL\_L, LEVEL\_M, LEVEL\_Q, LEVEL\_H.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [LEVEL_H](#LEVEL-H) | Koreksi kesalahan Tingkat H dapat diterapkan pada kode batang QR dan RectMicroQR. |
| [LEVEL_L](#LEVEL-L) | Koreksi kesalahan Tingkat L dapat diterapkan pada kode batang QR dan MicroQR. |
| [LEVEL_M](#LEVEL-M) | Koreksi kesalahan Tingkat M dapat diterapkan pada kode batang QR, kode batang RectMicroQR, dan kode batang MicroQR dengan versi dari M2 hingga M4. |
| [LEVEL_Q](#LEVEL-Q) | Koreksi kesalahan Tingkat Q dapat diterapkan pada kode batang QR dan kode batang MicroQR dengan versi M4. |
## Methods

| Method | Deskripsi |
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


Koreksi kesalahan Tingkat H dapat diterapkan pada kode batang QR dan RectMicroQR. Memungkinkan pemulihan 30% dari teks kode.

### LEVEL_L {#LEVEL-L}
```
public static final QRErrorLevel LEVEL_L
```


Koreksi kesalahan Tingkat L dapat diterapkan pada kode batang QR dan MicroQR. Memungkinkan pemulihan 7% dari teks kode.

### LEVEL_M {#LEVEL-M}
```
public static final QRErrorLevel LEVEL_M
```


Koreksi kesalahan Tingkat M dapat diterapkan pada kode batang QR, kode batang RectMicroQR, dan kode batang MicroQR dengan versi dari M2 hingga M4. Memungkinkan pemulihan 15% dari teks kode.

### LEVEL_Q {#LEVEL-Q}
```
public static final QRErrorLevel LEVEL_Q
```


Koreksi kesalahan Tingkat Q dapat diterapkan pada kode batang QR dan kode batang MicroQR dengan versi M4. Memungkinkan pemulihan 25% dari teks kode.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
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
| Parameter | Type | Deskripsi |
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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static QRErrorLevel fromValue(int value)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

