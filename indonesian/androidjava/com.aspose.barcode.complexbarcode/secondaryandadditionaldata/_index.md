---
title: SecondaryAndAdditionalData
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Kelas untuk menyimpan data sekunder dan tambahan HIBC LIC.
type: docs
weight: 35
url: /id/androidjava/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

Kelas untuk menyimpan data sekunder dan tambahan HIBC LIC.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai  SecondaryAndAdditionalData  yang ditentukan. |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | Mengidentifikasi tanggal pembuatan. |
| [getExpiryDate()](#getExpiryDate--) | Mengidentifikasi tanggal kedaluwarsa. |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | Mengidentifikasi format tanggal kedaluwarsa. |
| [getLotNumber()](#getLotNumber--) | Mengidentifikasi nomor lot atau batch. |
| [getQuantity()](#getQuantity--) | Mengidentifikasi kuantitas, harus berupa nilai integer dari 0 hingga 500. |
| [getSerialNumber()](#getSerialNumber--) | Mengidentifikasi nomor seri. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | Membuat instance data tambahan sekunder dan suplemental dari format string sesuai spesifikasi HIBC LIC. |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | Mengidentifikasi tanggal pembuatan. |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | Mengidentifikasi tanggal kedaluwarsa. |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | Mengidentifikasi format tanggal kedaluwarsa. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Mengidentifikasi nomor lot atau batch. |
| [setQuantity(int value)](#setQuantity-int-) | Mengidentifikasi kuantitas, harus berupa nilai integer dari 0 hingga 500. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Mengidentifikasi nomor seri. |
| [toString()](#toString--) | Mengonversi data ke format string sesuai spesifikasi HIBC LIC. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SecondaryAndAdditionalData() {#SecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai  SecondaryAndAdditionalData  yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Nilai  SecondaryAndAdditionalData  untuk dibandingkan dengan instance ini. |

**Returns:**
boolean -  **true**  jika obj memiliki nilai yang sama dengan instance ini; jika tidak,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDateOfManufacture() {#getDateOfManufacture--}
```
public LocalDateTime getDateOfManufacture()
```


Mengidentifikasi tanggal pembuatan. Tanggal pembuatan dapat diatur ke DateTime.MinValue agar tidak menggunakan bidang ini. Nilai default: DateTime.MinValue

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


Mengidentifikasi tanggal kedaluwarsa. Akan digunakan jika ExpiryDateFormat tidak diatur ke None.

**Returns:**
java.time.LocalDateTime
### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public HIBCLICDateFormat getExpiryDateFormat()
```


Mengidentifikasi format tanggal kedaluwarsa.

**Returns:**
[HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat)
### getLotNumber() {#getLotNumber--}
```
public String getLotNumber()
```


Mengidentifikasi nomor lot atau batch. Nomor lot/batch harus berupa string alfanumerik dengan panjang hingga 18 simbol. .

**Returns:**
java.lang.String
### getQuantity() {#getQuantity--}
```
public int getQuantity()
```


Mengidentifikasi kuantitas, harus berupa nilai integer dari 0 hingga 500. Kuantitas dapat diatur ke -1 agar tidak menggunakan bidang ini. Nilai default: -1

**Returns:**
int
### getSerialNumber() {#getSerialNumber--}
```
public String getSerialNumber()
```


Mengidentifikasi nomor seri. Nomor seri harus berupa string alfanumerik dengan panjang hingga 18 simbol.

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




### parseFromString(String secondaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String secondaryDataCodetext)
```


Membuat instance data tambahan sekunder dan suplemental dari format string sesuai spesifikasi HIBC LIC.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | String yang diformat. |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


Mengidentifikasi tanggal pembuatan. Tanggal pembuatan dapat diatur ke DateTime.MinValue agar tidak menggunakan bidang ini. Nilai default: DateTime.MinValue

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


Mengidentifikasi tanggal kedaluwarsa. Akan digunakan jika ExpiryDateFormat tidak diatur ke None.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


Mengidentifikasi format tanggal kedaluwarsa.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


Mengidentifikasi nomor lot atau batch. Nomor lot/batch harus berupa string alfanumerik dengan panjang hingga 18 simbol. .

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


Mengidentifikasi kuantitas, harus berupa nilai integer dari 0 hingga 500. Kuantitas dapat diatur ke -1 agar tidak menggunakan bidang ini. Nilai default: -1

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


Mengidentifikasi nomor seri. Nomor seri harus berupa string alfanumerik dengan panjang hingga 18 simbol.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

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

