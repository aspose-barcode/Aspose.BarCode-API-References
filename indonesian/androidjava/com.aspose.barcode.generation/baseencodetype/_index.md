---
title: BaseEncodeType
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Kelas dasar untuk SymbologyEncodeType.
type: docs
weight: 16
url: /id/androidjava/com.aspose.barcode.generation/baseencodetype/
---
**Inheritance:**
java.lang.Object
```
public class BaseEncodeType
```

Kelas dasar untuk SymbologyEncodeType.
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai BaseEncodeType yang ditentukan. |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | Mendapatkan klasifikasi simbolik ini. |
| [getString()](#getString--) | Mengonversi instance BaseEncodeType ke representasi string yang setara. |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | Mengonversi instance BaseEncodeType ke representasi string yang setara. |
| [getTypeIndex()](#getTypeIndex--) | Mendapatkan indeks tipe enkoding. |
| [getTypeName()](#getTypeName--) | Mendapatkan nama tipe enkoding. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | Mengonversi representasi string dari nama BaseEncodeType ke instance-nya. |
| [toString()](#toString--) | Mengembalikan nama BaseEncodeType yang diberikan sebagai string. |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | Mengonversi representasi string dari BaseEncodeType ke instance-nya. |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | Mengonversi representasi string dari BaseEncodeType ke instance-nya. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai BaseEncodeType yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| lainnya | java.lang.Object | Nilai BaseEncodeType untuk dibandingkan dengan instance ini. |

**Returns:**
boolean -  **true**  jika obj memiliki nilai yang sama dengan instance ini; jika tidak,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassification() {#getClassification--}
```
public BarcodeClassifications getClassification()
```


Mendapatkan klasifikasi simbolik ini.

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


Mengonversi instance BaseEncodeType ke representasi string yang setara. Format stringnya adalah: "Index:0; Name:Codabar".

**Returns:**
java.lang.String - String yang mewakili nilai lengkap dari tipe enkode
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


Mengonversi instance BaseEncodeType ke representasi string yang setara. Format stringnya adalah: "Index:-1; Name:None".

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Instance BaseEncodeType yang akan dikonversi |

**Returns:**
java.lang.String - String yang mewakili nilai lengkap dari tipe enkode yang diberikan
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Mendapatkan indeks tipe enkoding.

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Mendapatkan nama tipe enkoding.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash integer bertanda 32-bit.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parse(String stringEncodeType) {#parse-java.lang.String-}
```
public static BaseEncodeType parse(String stringEncodeType)
```


Mengonversi representasi string dari nama BaseEncodeType ke instance-nya.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stringEncodeType | java.lang.String | String yang berisi nama BaseEncodeType yang akan dikonversi. |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


Mengembalikan nama BaseEncodeType yang diberikan sebagai string.

**Returns:**
java.lang.String - String yang mewakili nama tipe enkode
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


Mengonversi representasi string dari BaseEncodeType menjadi instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| parsingType | java.lang.String | String dalam format "Index:-1; Name:None" untuk dikonversi. |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | Sebuah SingleEncodeType aktual dikembalikan, ketika konversi telah selesai dengan sukses; |

sebaliknya mengembalikan null. |

**Returns:**
boolean -  **true**  jika s berhasil dikonversi; sebaliknya,  **false** .
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


Mengonversi representasi string dari BaseEncodeType menjadi instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| parsingType | java.lang.String | String dalam format "Index:-1; Name:None" untuk dikonversi. |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | Sebuah SingleEncodeType aktual dikembalikan, ketika konversi telah selesai dengan sukses; |

sebaliknya mengembalikan null. |

**Returns:**
boolean -  **true**  jika s berhasil dikonversi; sebaliknya,  **false** .
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

