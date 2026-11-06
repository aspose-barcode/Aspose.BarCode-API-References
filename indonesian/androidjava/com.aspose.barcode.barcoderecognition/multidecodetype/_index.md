---
title: "MultiDecodeType"
second_title: "Referensi API Aspose.BarCode untuk Android via Java"
description: "Tipe decode komposit."
type: docs
weight: 35
url: /id/androidjava/com.aspose.barcode.barcoderecognition/multidecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultiDecodeType extends BaseDecodeType
```

Tipe decode komposit.

Contoh ini menunjukkan cara membuat tipe MultiDecode gabungan yang menggabungkan SingleDecodeType dan tipe MultiDecode.

```

```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MultiDecodeType(SingleDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Menginisialisasi instance baru dari kelas [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype). |
| [MultiDecodeType(BaseDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Menginisialisasi instance baru dari kelas [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Menambahkan satu lagi [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) ke MultiDecodeType. |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Periksa apakah ini berisi semua tipe dari tipe barcode. |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Apakah berisi salah satu tipe. |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) yang ditentukan. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Mengembalikan nilai yang menunjukkan apakah koleksi tipe decode ini hanya berisi nilai [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) yang ditentukan. |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) yang ditentukan. |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Mengecualikan [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) dari MultiDecodeType dan mengembalikan instance MultiDecodeType baru. |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | Mewakili daftar tipe tunggal. |
| [getSingleTypesCount()](#getSingleTypesCount--) | Mengembalikan jumlah tipe tunggal. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Metode yang dioverride yang merepresentasikan MultiDecodeType sebagai string. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Mengonversi representasi string dari BaseDecodeType ke instance-nya, setelah menentukan tipe konkret. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Mengonversi representasi string dari MultiDecodeType ke instance-nya. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Mengonversi representasi string dari SingleDecodeType ke instance-nya. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiDecodeType(SingleDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultiDecodeType(SingleDecodeType[] barcodeTypes)
```


Menginisialisasi instance baru dari kelas [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Array tipe decode tunggal |

### MultiDecodeType(BaseDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultiDecodeType(BaseDecodeType[] barcodeTypes)
```


Menginisialisasi instance baru dari kelas [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Array tipe decode multi dan tunggal |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


Menambahkan satu lagi [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) ke MultiDecodeType.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Sebuah Single DecodeType yang akan ditambahkan ke daftar |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


Periksa apakah ini berisi semua tipe dari tipe barcode.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Masukkan tipe barcode tunggal atau multi |

**Returns:**
boolean - Nilai adalah true jika semua tipe termasuk ke dalam
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


Apakah berisi salah satu tipe.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe decode |

**Returns:**
boolean - Nilai adalah true jika ada tipe yang termasuk
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | Sebuah nilai [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) untuk dibandingkan dengan instance ini. |

**Returns:**
boolean -  **true**  jika obj memiliki nilai yang sama dengan instance ini; jika tidak,  **false** .
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Mengembalikan nilai yang menunjukkan apakah koleksi tipe decode ini hanya berisi nilai [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Sebuah nilai [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) untuk dibandingkan dengan koleksi tipe decode ini. |

**Returns:**
boolean -  **true**  jika koleksi ini hanya berisi tipe decode yang ditentukan; sebaliknya,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Nilai System.Object untuk dibandingkan dengan instance ini. |

**Returns:**
boolean -  **true**  jika obj memiliki nilai yang sama dengan instance ini; jika tidak,  **false** .
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


Mengecualikan [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) dari MultiDecodeType dan mengembalikan instance MultiDecodeType baru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Sebuah Single DecodeType yang akan dikecualikan. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - New MultiDecodeType instance with excluded SingleDecodeType.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSingleTypes() {#getSingleTypes--}
```
public final List<SingleDecodeType> getSingleTypes()
```


Mewakili daftar tipe tunggal.

**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType> - Daftar tipe tunggal
### getSingleTypesCount() {#getSingleTypesCount--}
```
public final int getSingleTypesCount()
```


Mengembalikan jumlah tipe tunggal.

**Returns:**
int
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




### toString() {#toString--}
```
public String toString()
```


Metode yang dioverride yang merepresentasikan MultiDecodeType sebagai string.

**Returns:**
java.lang.String - Sebuah string yang mewakili instance MultiDecodeType sebagai "singleDecodeType1, singleDecodeType2, ..."

 **"AllSupportedTypes"**  returns when all types are included.
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


Mengonversi representasi string dari BaseDecodeType menjadi instance-nya, setelah menentukan tipe konkret. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parsingType | java.lang.String | String yang berisi representasi MultiDecodeType untuk dikonversi. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

Jika tidak, mengembalikan tipe tak tentu. atau MultiDecodeType (\"None\").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Mengonversi representasi string dari MultiDecodeType menjadi instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parsingType | java.lang.String | String yang berisi representasi MultiDecodeType untuk dikonversi. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

Jika tidak, mengembalikan tipe tak tentu. atau MultiDecodeType (\"None\").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Mengonversi representasi string dari SingleDecodeType menjadi instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parsingType | java.lang.String | String yang berisi SingleDecodeType dalam format seperti \"EAN8\" atau \"EAN13\" atau \"CodaBar\"... untuk dikonversi. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

Jika tidak, mengembalikan tipe tak tentu. atau SingleDecodeType (-1, \"None\").
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

