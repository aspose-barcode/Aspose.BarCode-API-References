---
title: BaseDecodeType
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Kelas dasar untuk MultiDecodeType dan SingleDecodeType.
type: docs
weight: 23
url: /id/androidjava/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

Kelas dasar untuk MultiDecodeType dan SingleDecodeType.

--------------------

> ```
> This sample shows how to use BaseDecodeType with SingleDecodeType and MultiDecodeType
>  
>  BaseDecodeType decodeOne = DecodeType.CODE_128;
>  BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.CODE_128, DecodeType.CODE_39_STANDARD, DecodeType.CODE_39_FULL_ASCII);
> ```
## Methods

| Method | Deskripsi |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Menentukan apakah salah satu tipe decode yang diberikan termasuk ke dalam |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) yang ditentukan. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) yang ditentukan. |
| [equals(Object other)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) yang ditentukan. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Mengonversi representasi string dari BaseDecodeType ke instance-nya, setelah menentukan tipe konkret. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Mengonversi representasi string dari MultiDecodeType ke instance-nya. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Mengonversi representasi string dari SingleDecodeType ke instance-nya. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


Menentukan apakah salah satu tipe decode yang diberikan termasuk ke dalam

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe yang akan diverifikasi. |

**Returns:**
boolean - Nilai adalah true jika ada tipe yang termasuk ke dalam.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| lainnya | com.aspose.barcode.barcoderecognition.MultiDecodeType | Sebuah nilai java.lang.Object untuk dibandingkan dengan instansi ini. |

**Returns:**
boolean - True jika obj memiliki nilai yang sama dengan instance ini; jika tidak, false.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Sebuah nilai java.lang.Object untuk dibandingkan dengan instansi ini. |

**Returns:**
boolean - True jika obj memiliki nilai yang sama dengan instance ini; jika tidak, false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| lainnya | java.lang.Object | Sebuah nilai java.lang.Object untuk dibandingkan dengan instansi ini. |

**Returns:**
boolean - True jika obj memiliki nilai yang sama dengan instance ini; jika tidak, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

