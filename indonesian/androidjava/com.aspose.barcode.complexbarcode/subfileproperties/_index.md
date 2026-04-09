---
title: USADriveIdCodetext.SubfileProperties
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Offset dan panjang properti subfile USA DL diatur secara otomatis.
type: docs
weight: 12
url: /id/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

Properti subfile DL USA, offset, dan panjang diatur secara otomatis.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 Byte ini berisi nilai numerik 4 digit yang menentukan panjang Subfile dalam byte. Terminator segmen harus termasuk dalam perhitungan panjang subfile. Terminator segmen = 1. |
| [getOffset()](#getOffset--) | Nilai numerik 4 digit yang menentukan jumlah byte dari awal file hingga tempat data yang terkait dengan sub-file tertentu berada. Byte pertama dalam file berada pada offset 0. |
| [getType()](#getType--) | Tipe subfile 2 byte, seperti "DL" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 Byte ini berisi nilai numerik 4 digit yang menentukan panjang Subfile dalam byte. Terminator segmen harus termasuk dalam perhitungan panjang subfile. Terminator segmen = 1. |
| [setOffset(int value)](#setOffset-int-) | Nilai numerik 4 digit yang menentukan jumlah byte dari awal file hingga tempat data yang terkait dengan sub-file tertentu berada. Byte pertama dalam file berada pada offset 0. |
| [setType(String value)](#setType-java.lang.String-) | Tipe subfile 2 byte, seperti "DL" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| tipe | java.lang.String |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
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
### getLength() {#getLength--}
```
public final int getLength()
```


4 Byte ini berisi nilai numerik 4 digit yang menentukan panjang Subfile dalam byte. Terminator segmen harus termasuk dalam perhitungan panjang subfile. Terminator segmen = 1. Setiap subfile harus dimulai dengan Tipe Subfile dua karakter dan dua karakter ini juga harus termasuk dalam panjang.

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


Nilai numerik 4 digit yang menentukan jumlah byte dari awal file hingga tempat data yang terkait dengan sub-file tertentu berada. Byte pertama dalam file berada pada offset 0.

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


Tipe subfile 2 byte, seperti "DL"

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


4 Byte ini berisi nilai numerik 4 digit yang menentukan panjang Subfile dalam byte. Terminator segmen harus termasuk dalam perhitungan panjang subfile. Terminator segmen = 1. Setiap subfile harus dimulai dengan Tipe Subfile dua karakter dan dua karakter ini juga harus termasuk dalam panjang.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


Nilai numerik 4 digit yang menentukan jumlah byte dari awal file hingga tempat data yang terkait dengan sub-file tertentu berada. Byte pertama dalam file berada pada offset 0.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


Tipe subfile 2 byte, seperti "DL"

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

