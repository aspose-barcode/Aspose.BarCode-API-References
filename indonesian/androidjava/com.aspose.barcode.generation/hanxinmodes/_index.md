---
title: HanXinModes
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Mode enkoding Han Xin Code.
type: docs
weight: 91
url: /id/androidjava/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Mode pengkodean Han Xin Code. Disarankan untuk menggunakan Auto dengan karakter ASCII / Cina atau Unicode untuk karakter Unicode.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [AUTO](#AUTO) | Urutan mode Numerik, Teks, ECI, Byte Biner, dan 4 mode GB18030 berubah secara otomatis. |
| [BINARY](#BINARY) | Mode byte biner mengkodekan data biner dalam bentuk apa pun dan mengkodekannya dalam byte biner masing-masing. |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Setiap Karakter Cina umum di Wilayah Satu direpresentasikan dengan 12 bit. |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Setiap Karakter Cina umum di Wilayah Dua direpresentasikan dengan 12 bit. |
| [ECI](#ECI) | Mode Interpretasi Saluran Diperluas (ECI) |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | Setiap karakter Wilayah GB18030 4-byte direpresentasikan dengan 21 bit. |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | Setiap karakter Wilayah GB18030 2-byte direpresentasikan dengan 15 bit. |
| [GS_1](#GS-1) | Mode GS1 menunjukkan bahwa data yang direpresentasikan dalam Han Xin Code adalah data GS1 dari sistem GS1 yang didefinisikan oleh Spesifikasi Umum GS1. |
| [NUMERIC](#NUMERIC) | Mode numerik mengkodekan data dari set digit desimal (digit 0-9, nilai byte 30HEX hingga 39HEX). |
| [TEXT](#TEXT) | Mode teks mengkodekan data dari simbol umum yang didefinisikan dalam ISO/IEC 646, yaitu, |
| [UNICODE](#UNICODE) | Mode Unicode merancang cara untuk merepresentasikan data teks apa pun yang merujuk pada pengkodean/karakter set UTF8 dalam Han Xin Code. |
| [URI](#URI) | Mode URI menunjukkan bahwa data yang direpresentasikan dalam Han Xin Code adalah referensi Uniform Resource Identifier (URI) ke RFC 3986. |
## Methods

| Method | Deskripsi |
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
public static final HanXinModes AUTO
```


Urutan mode Numerik, Teks, ECI, Byte Biner, dan 4 mode GB18030 berubah secara otomatis.

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


Mode byte biner mengkodekan data biner dalam bentuk apa pun dan mengkodekannya dalam byte biner masing-masing. Setiap byte dalam mode Byte Biner direpresentasikan dengan 8 bit.

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Setiap Karakter Cina umum di Wilayah Satu direpresentasikan dengan 12 bit. Karakter Cina umum di Wilayah satu mencakup karakter yang nilai byte pertamanya berada dalam rentang B0HEX hingga D7HEX dan nilai byte keduanya berada dalam rentang A1HEX hingga FEHEX (3760 karakter), serta karakter yang nilai byte pertamanya berada dalam rentang A1HEX hingga A3HEX, dan nilai byte keduanya berada dalam rentang A1HEX hingga FEHEX (282 karakter), dan karakter yang nilai byte-nya berada dalam rentang A8A1HEX hingga A8C0HEX (32 karakter).

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Setiap Karakter Cina umum di Wilayah Dua direpresentasikan dengan 12 bit. Karakter Cina umum di Wilayah Dua mencakup karakter yang nilai byte pertamanya berada dalam rentang D8HEX hingga F7HEX, dan nilai byte keduanya berada dalam rentang A1HEX hingga FEHEX.

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Mode Interpretasi Saluran Diperluas (ECI)

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


Setiap karakter Wilayah GB18030 4-byte direpresentasikan dengan 21 bit. Wilayah GB18030 4-byte mengkodekan data dari semua karakter dalam wilayah empat-byte GB18030 (yaitu, karakter yang nilai byte pertamanya berada dalam rentang 81HEX hingga FEHEX, nilai byte keduanya berada dalam rentang 30HEX hingga 39HEX, nilai byte ketiga berada dalam rentang 81HEX hingga FEHEX, dan nilai byte keempat berada dalam rentang 30HEX hingga 39HEX).

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


Setiap karakter Wilayah GB18030 2-byte direpresentasikan dengan 15 bit. Wilayah GB18030 2-byte mengkodekan data dari semua karakter (termasuk Karakter Cina umum di Wilayah Satu dan Dua) dalam wilayah dua-byte GB18030, (yaitu, karakter Cina yang nilai byte pertamanya berada dalam rentang 81HEX hingga FEHEX dan nilai byte keduanya berada dalam rentang 40HEX hingga 7EHEX atau 80HEX hingga FEHEX).

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


Mode GS1 menunjukkan bahwa data yang direpresentasikan dalam Han Xin Code adalah data GS1 dari sistem GS1 yang didefinisikan oleh Spesifikasi Umum GS1. Contoh string input: "(01)03453120000011(17)191125(10)ABCD1234(21)10".

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


Mode numerik mengkodekan data dari set digit desimal (digit 0-9, nilai byte 30HEX hingga 39HEX). Biasanya, 3 karakter data direpresentasikan dengan 10 bit.

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


Mode teks mengkodekan data dari simbol umum yang didefinisikan dalam ISO/IEC 646, yaitu nilai byte 00 HEX hingga 1B HEX dan 20 HEX hingga 7F HEX.

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Mode Unicode merancang cara untuk merepresentasikan data teks apa pun yang merujuk pada pengkodean/karakter set UTF8 dalam Han Xin Code.

### URI {#URI}
```
public static final HanXinModes URI
```


Mode URI menunjukkan bahwa data yang direpresentasikan dalam Han Xin Code adalah referensi Uniform Resource Identifier (URI) ke RFC 3986.

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
public static HanXinModes valueOf(String name)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
com.aspose.barcode.generation.HanXinModes
### values() {#values--}
```
public static HanXinModes[] values()
```




**Returns:**
com.aspose.barcode.generation.HanXinModes[]
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

