---
title: Pdf417EncodeMode
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Mode enkoding kode batang Pdf417.
type: docs
weight: 99
url: /id/androidjava/com.aspose.barcode.generation/pdf417encodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Pdf417EncodeMode extends Enum<Pdf417EncodeMode>
```

Mode enkoding kode batang Pdf417.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [AUTO](#AUTO) | Dalam mode Auto, CodeText dikodekan dengan kepadatan data maksimum. |
| [BINARY](#BINARY) | Dalam mode Binary, CodeText dikodekan dengan kepadatan data maksimum. |
| [ECI](#ECI) | Dalam mode ECI, seluruh pesan di-encode ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI. |
| [EXTENDED](#EXTENDED) |  |
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
### AUTO {#AUTO}
```
public static final Pdf417EncodeMode AUTO
```


Dalam mode Auto, CodeText di-encode dengan kepadatan data maksimum. Karakter Unicode di-encode ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI. Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian dilempar.

### BINARY {#BINARY}
```
public static final Pdf417EncodeMode BINARY
```


Dalam mode Binary, CodeText di-encode dengan kepadatan data maksimum. Jika ditemukan karakter Unicode, sebuah pengecualian dilempar.

### ECI {#ECI}
```
public static final Pdf417EncodeMode ECI
```


Dalam mode ECI, seluruh pesan di-encode ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI. Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian dilempar. Harap dicatat bahwa beberapa pemindai lama (sebelum 2006) mungkin tidak mendukung mode ini.

### EXTENDED {#EXTENDED}
```
public static final Pdf417EncodeMode EXTENDED
```


Mode diperluas yang mendukung beberapa mode ECI.

Lebih baik menggunakan Pdf417ExtCodetextBuilder untuk menghasilkan codetext yang diperluas.

Gunakan properti Display2DText untuk mengatur teks yang terlihat dengan menghapus karakter pengelola.

Pengidentifikasi ECI ditetapkan sebagai satu garis miring dan pengidentifikasi enam digit "\\000026" - pengidentifikasi ECI UTF8

Semua karakter unicode setelah pengidentifikasi ECI secara otomatis di-encode ke dalam set karakter yang benar.

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
public static Pdf417EncodeMode fromValue(int value)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
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
public static Pdf417EncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### values() {#values--}
```
public static Pdf417EncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.Pdf417EncodeMode[]
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

