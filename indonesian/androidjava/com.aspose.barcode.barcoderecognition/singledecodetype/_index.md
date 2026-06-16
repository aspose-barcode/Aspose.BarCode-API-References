---
title: SingleDecodeType
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Tipe decode tunggal.
type: docs
weight: 48
url: /id/androidjava/com.aspose.barcode.barcoderecognition/singledecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public final class SingleDecodeType extends BaseDecodeType
```

Tipe decode tunggal. Lihat tipe decode untuk mendapatkan instance.

--------------------

> ```
> This sample shows how to get instance of single decode type.
>  
>  SingleDecodeType singleType = DecodeType.QR
> ```
## Methods

| Method | Deskripsi |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Mengembalikan nilai yang menunjukkan apakah instance ini termasuk dalam daftar yang ditentukan. |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) |  |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) yang ditentukan. |
| [getClass()](#getClass--) |  |
| [getString()](#getString--) | Mengonversi instance SingleDecodeType ke representasi string yang setara, menggunakan format berikut: "Index:-1; Name:None". |
| [getString(SingleDecodeType instance)](#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Mengonversi instance SingleDecodeType ke representasi string yang setara, menggunakan format berikut: "Index:-1; Name:None". |
| [getTypeIndex()](#getTypeIndex--) | Mendapatkan indeks tipe decode |
| [getTypeName()](#getTypeName--) | Mendapatkan nama tipe decode |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseSingleDecodeType(String stringDecodeType)](#parseSingleDecodeType-java.lang.String-) | Mengonversi representasi string dari nama SingleDecodeType ke instance-nya. |
| [toString()](#toString--) | Metode yang dioverride yang merepresentasikan SingleDecodeType sebagai string Nama. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Mengonversi representasi string dari BaseDecodeType ke instance-nya, setelah menentukan tipe konkret. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Mengonversi representasi string dari MultiDecodeType ke instance-nya. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Mengonversi representasi string dari SingleDecodeType ke instance-nya. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] types)
```


Mengembalikan nilai yang menunjukkan apakah instance ini termasuk dalam daftar yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Array dari tipe decode tunggal dan multi |

**Returns:**
boolean - Nilai adalah true jika ada tipe yang termasuk ke dalam
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| lainnya | com.aspose.barcode.barcoderecognition.MultiDecodeType |  |

**Returns:**
boolean
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Nilai System.Object untuk dibandingkan dengan instance ini. |

**Returns:**
boolean - True jika obj memiliki nilai yang sama dengan instance ini; jika tidak, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getString() {#getString--}
```
public String getString()
```


Mengonversi instance SingleDecodeType ke representasi string yang setara, menggunakan format berikut: "Index:-1; Name:None".

**Returns:**
java.lang.String - String yang merepresentasikan nilai lengkap dari tipe decode tunggal
### getString(SingleDecodeType instance) {#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public static String getString(SingleDecodeType instance)
```


Mengonversi instance SingleDecodeType ke representasi string yang setara, menggunakan format berikut: "Index:-1; Name:None".

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| instance | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Instance SingleDecodeType yang akan dikonversi |

**Returns:**
java.lang.String - String yang merepresentasikan nilai lengkap dari tipe decode tunggal yang diberikan
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Mendapatkan indeks tipe decode

**Returns:**
short - Indeks tipe decode
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Mendapatkan nama tipe decode

**Returns:**
java.lang.String - Nama tipe decode
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




### parseSingleDecodeType(String stringDecodeType) {#parseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType parseSingleDecodeType(String stringDecodeType)
```


Mengonversi representasi string dari nama SingleDecodeType ke instance-nya.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stringDecodeType | java.lang.String | String yang berisi nama SingleDecodeType untuk dikonversi. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - the instance of , if conversion was successful; otherwise, it returns \{@link \}.
### toString() {#toString--}
```
public String toString()
```


Metode yang dioverride yang merepresentasikan SingleDecodeType sebagai string Nama.

**Returns:**
java.lang.String - Sebuah string yang mewakili nama tipe decode tunggal
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


Mengonversi representasi string dari BaseDecodeType menjadi instansinya, setelah menentukan tipe konkret. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| parsingType | java.lang.String | Sebuah string yang berisi representasi MultiDecodeType untuk dikonversi. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

Jika tidak, ia mengembalikan tipe tak tentu. atau MultiDecodeType ("None").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Mengonversi representasi string dari MultiDecodeType menjadi instansinya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| parsingType | java.lang.String | Sebuah string yang berisi representasi MultiDecodeType untuk dikonversi. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Sebuah MultiDecodeType yang sebenarnya dikembalikan, ketika konversi telah selesai dengan sukses;

Jika tidak, ia mengembalikan tipe tak tentu. atau MultiDecodeType ("None").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Mengonversi representasi string dari SingleDecodeType menjadi instansinya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| parsingType | java.lang.String | Sebuah string yang berisi SingleDecodeType dalam format seperti "EAN8" atau "EAN13" atau "CodaBar"... untuk dikonversi. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

Jika tidak, ia mengembalikan tipe tak tentu. atau SingleDecodeType (-1, "None").
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

