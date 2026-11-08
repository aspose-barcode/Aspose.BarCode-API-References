---
title: "MaxiCodeMode"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Berisi mode enkoding MaxiCode."
type: docs
weight: 94
url: /id/java/com.aspose.barcode.generation/maxicodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MaxiCodeMode extends Enum<MaxiCodeMode>
```

Berisi mode enkoding MaxiCode.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [MODE_2](#MODE-2) | Mode 2 mengkodekan informasi pos dalam pesan pertama dan data dalam pesan kedua. |
| [MODE_3](#MODE-3) | Mode 3 mengkodekan informasi pos dalam pesan pertama dan data dalam pesan kedua. |
| [MODE_4](#MODE-4) | Mode 4 mengkodekan data dalam pesan pertama dan kedua dengan koreksi ECC pendek. |
| [MODE_5](#MODE-5) | Mode 5 mengkodekan data dalam pesan pertama dan kedua dengan koreksi ECC panjang. |
| [MODE_6](#MODE-6) | Mode 6 mengkodekan data dalam pesan pertama dan kedua dengan koreksi ECC pendek. |
## Metode

| Metode | Deskripsi |
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


Mode 2 mengkodekan informasi pos dalam pesan pertama dan data dalam pesan kedua. Memiliki kode pos 9 digit dan hanya digunakan di USA.

### MODE_3 {#MODE-3}
```
public static final MaxiCodeMode MODE_3
```


Mode 3 mengkodekan informasi pos dalam pesan pertama dan data dalam pesan kedua. Memiliki kode pos alfanumerik 6 karakter dan digunakan di seluruh dunia.

### MODE_4 {#MODE-4}
```
public static final MaxiCodeMode MODE_4
```


Mode 4 mengkodekan data dalam pesan pertama dan kedua dengan koreksi ECC pendek.

### MODE_5 {#MODE-5}
```
public static final MaxiCodeMode MODE_5
```


Mode 5 mengkodekan data dalam pesan pertama dan kedua dengan koreksi ECC panjang.

### MODE_6 {#MODE-6}
```
public static final MaxiCodeMode MODE_6
```


Mode 6 mengkodekan data dalam pesan pertama dan kedua dengan koreksi ECC pendek. Digunakan untuk mengkodekan perangkat.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static MaxiCodeMode fromValue(int value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

