---
title: "PrimaryData"
second_title: "Referensi API Aspose.BarCode untuk Android via Java"
description: "Kelas untuk menyimpan data utama HIBC LIC."
type: docs
weight: 33
url: /id/androidjava/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

Kelas untuk menyimpan data utama HIBC LIC.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai  PrimaryData  yang ditentukan. |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Mengidentifikasi tanggal kode identifikasi pelabel. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Mengidentifikasi nomor produk atau katalog. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Mengidentifikasi ID satuan ukuran. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | Membuat instance data utama dari format string sesuai spesifikasi HIBC LIC. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Mengidentifikasi tanggal kode identifikasi pelabel. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Mengidentifikasi nomor produk atau katalog. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Mengidentifikasi ID satuan ukuran. |
| [toString()](#toString--) | Mengonversi data ke format string sesuai spesifikasi HIBC LIC. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrimaryData() {#PrimaryData--}
```
public PrimaryData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai  PrimaryData  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Nilai  PrimaryData  untuk dibandingkan dengan instance ini. |

**Returns:**
boolean -  **true**  jika obj memiliki nilai yang sama dengan instance ini; jika tidak,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public String getLabelerIdentificationCode()
```


Mengidentifikasi tanggal kode identifikasi pelabel. Kode identifikasi pelabel harus berupa string alfanumerik 4 simbol, dengan karakter pertama selalu berupa huruf.

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


Mengidentifikasi nomor produk atau katalog. Nomor produk atau katalog harus berupa string alfanumerik dengan panjang hingga 18 simbol.

**Returns:**
java.lang.String
### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public int getUnitOfMeasureID()
```


Mengidentifikasi ID satuan ukuran. ID satuan ukuran harus berupa nilai integer dari 0 hingga 9.

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




### parseFromString(String primaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String primaryDataCodetext)
```


Membuat instance data utama dari format string sesuai spesifikasi HIBC LIC.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | String terformat. |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


Mengidentifikasi tanggal kode identifikasi pelabel. Kode identifikasi pelabel harus berupa string alfanumerik 4 simbol, dengan karakter pertama selalu berupa huruf.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


Mengidentifikasi nomor produk atau katalog. Nomor produk atau katalog harus berupa string alfanumerik dengan panjang hingga 18 simbol.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


Mengidentifikasi ID satuan ukuran. ID satuan ukuran harus berupa nilai integer dari 0 hingga 9.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### toString() {#toString--}
```
public String toString()
```


Mengonversi data ke format string sesuai spesifikasi HIBC LIC.

**Returns:**
java.lang.String - String yang diformat.
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

