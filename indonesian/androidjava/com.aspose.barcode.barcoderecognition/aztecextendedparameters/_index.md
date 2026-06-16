---
title: AztecExtendedParameters
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Menyimpan data khusus dari kode batang Aztec yang dikenali
type: docs
weight: 12
url: /id/androidjava/com.aspose.barcode.barcoderecognition/aztecextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class AztecExtendedParameters extends BaseExtendedParameters
```

Menyimpan data khusus dari kode batang Aztec yang dikenali

--------------------

> ```
> This sample shows how to get Aztec raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345");
>  generator.save("c:\\test.png");
> 
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.AZTEC);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText());
>      System.out.println("Aztec barcode ID: " + result.getExtended.getAztec.getStructuredAppendBarcodeId());
>      System.out.println("Aztec barcodes count: " + result.getExtended.getAztec.getStructuredAppendBarcodesCount());
>      System.out.println("Aztec file ID: " + result.getExtended.getAztec.getStructuredAppendFileId());
>      System.out.println("Aztec is reader initialization: " + result.getExtended.getAztec.isReaderInitialization());
>  }
> ```
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai AztecExtendedParameters yang ditentukan. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Mendapatkan ID barcode mode penambahan terstruktur Aztec. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Mendapatkan jumlah barcode mode penambahan terstruktur Aztec. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Mendapatkan ID File dari mode penambahan terstruktur Aztec. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [isEmpty()](#isEmpty--) | Menguji apakah semua parameter hanya memiliki nilai default |
| [isReaderInitialization()](#isReaderInitialization--) | Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca kode batang. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari AztecExtendedParameters ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai AztecExtendedParameters yang ditentukan.

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


Mendapatkan ID barcode mode penambahan terstruktur Aztec. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. Nilai default adalah 0.

Nilai: ID barcode dari mode penambahan terstruktur Aztec.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


Mendapatkan jumlah barcode mode penambahan terstruktur Aztec. Nilai default adalah 0. Jumlah harus berupa nilai antara 1 hingga 26.

Nilai: Jumlah barcode dari mode penambahan terstruktur Aztec.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public String getStructuredAppendFileId()
```


Mendapatkan ID File dari mode penambahan terstruktur Aztec. Nilai default adalah string kosong

Nilai: ID File dari mode penambahan terstruktur Aztec.

**Returns:**
java.lang.String
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
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
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




### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari AztecExtendedParameters ini.

**Returns:**
java.lang.String - Sebuah string yang mewakili AztecExtendedParameters ini.
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

