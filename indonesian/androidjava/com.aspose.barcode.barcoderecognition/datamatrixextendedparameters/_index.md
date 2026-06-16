---
title: DataMatrixExtendedParameters
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Menyimpan data khusus dari DataMatrix yang dikenali
type: docs
weight: 31
url: /id/androidjava/com.aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DataMatrixExtendedParameters extends BaseExtendedParameters
```

Menyimpan data khusus dari DataMatrix yang dikenali

--------------------

> ```
> This sample shows how to get DataMatrix raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345");
>  generator.save("c:\\test.png");
> 
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.DATA_MATRIX);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText);
>      System.out.println("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId());
>      System.out.println("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount());
>      System.out.println("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId());
>      System.out.println("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming)_);
>  }
> ```
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai DataMatrixExtendedParameters yang ditentukan. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Mendapatkan ID barcode mode structured append DataMatrix. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Mendapatkan jumlah barcode mode penambahan terstruktur DataMatrix. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Mendapatkan ID barcode mode structured append DataMatrix. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [isEmpty()](#isEmpty--) | Menguji apakah semua parameter hanya memiliki nilai default |
| [isReaderProgramming()](#isReaderProgramming--) | Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca kode batang. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-) | Mengembalikan nilai yang menunjukkan apakah nilai DataMatrixExtendedParameters pertama sama dengan nilai kedua. |
| [op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-) | Mengembalikan nilai yang menunjukkan apakah nilai DataMatrixExtendedParameters pertama berbeda dari nilai kedua. |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari DataMatrixExtendedParameters ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai DataMatrixExtendedParameters yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Nilai System.Object untuk dibandingkan dengan instance ini. |

**Returns:**
boolean -  **true**  jika obj memiliki nilai yang sama dengan instance ini; jika tidak,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public int getStructuredAppendBarcodeId()
```


Mendapatkan ID barcode mode penambahan terstruktur DataMatrix. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. Nilai default adalah -1.

Nilai: ID barcode mode penambahan terstruktur DataMatrix.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


Mendapatkan jumlah barcode mode penambahan terstruktur DataMatrix. Nilai default adalah -1. Jumlah harus berupa nilai antara 1 hingga 35.

Nilai: Jumlah barcode mode penambahan terstruktur DataMatrix.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public int getStructuredAppendFileId()
```


Mendapatkan ID barcode mode penambahan terstruktur DataMatrix. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. Nilai default adalah -1.

Nilai: ID barcode mode penambahan terstruktur DataMatrix.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash integer bertanda 32-bit.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Menguji apakah semua parameter hanya memiliki nilai default

Nilai: Mengembalikan  **true**  jika semua parameter hanya memiliki nilai default; jika tidak,  **false** .

**Returns:**
boolean
### isReaderProgramming() {#isReaderProgramming--}
```
public boolean isReaderProgramming()
```


Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca kode batang. Nilai default adalah false.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-}
```
public static boolean op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)
```


Mengembalikan nilai yang menunjukkan apakah nilai DataMatrixExtendedParameters pertama sama dengan nilai kedua.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| first | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Nilai pertama yang dibandingkan |
| second | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Nilai kedua yang dibandingkan |

**Returns:**
boolean -  **true**  jika nilai pertama sama dengan nilai kedua; jika tidak,  **false** .
### op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-}
```
public static boolean op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)
```


Mengembalikan nilai yang menunjukkan apakah nilai DataMatrixExtendedParameters pertama berbeda dari nilai kedua.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| first | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Nilai pertama yang dibandingkan |
| second | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Nilai kedua yang dibandingkan |

**Returns:**
boolean -  **true**  jika nilai pertama berbeda dari nilai kedua; jika tidak,  **false** .
### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari DataMatrixExtendedParameters ini.

**Returns:**
java.lang.String - Sebuah string yang merepresentasikan DataMatrixExtendedParameters ini.
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

