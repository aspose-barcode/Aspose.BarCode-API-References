---
title: "MailmarkCodetext"
second_title: "Referensi API Aspose.BarCode untuk Android via Java"
description: "Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode Royal Mailmark 4-state."
type: docs
weight: 24
url: /id/androidjava/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode Royal Mailmark 4-state.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | Menginisialisasi instance baru dari kelas  MailmarkCodetext  . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Mendapatkan tipe barcode. |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | "0" - Null atau Tes "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (untuk penggunaan potensial di masa depan) "5" - Deferred (Retail) "6" - Air (Retail) (untuk penggunaan potensial di masa depan) "7" - Surface (Retail) (untuk penggunaan potensial di masa depan) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [getConstructedCodetext()](#getConstructedCodetext--) | Membuat codetext dari data Mailmark. |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | PC dan DP harus mematuhi format PAF. |
| [getFormat()](#getFormat--) | "0" \\u2013 Null atau Tes "1" \\u2013 Surat "2" \\u2013 Surat Besar |
| [getItemID()](#getItemID--) | Nilai maksimum adalah 99999999. |
| [getSupplychainID()](#getSupplychainID--) | Nilai maksimum adalah 99 untuk Barcode C dan 999999 untuk Barcode L. |
| [getVersionID()](#getVersionID--) | Saat ini "1" \\u2013 Untuk barcode Mailmark (0 dan 2 hingga 9 serta A sampai Z cadangan untuk penggunaan di masa depan) |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Menginisialisasi data Mailmark dari codetext yang dibangun. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | "0" - Null atau Tes "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (untuk penggunaan potensial di masa depan) "5" - Deferred (Retail) "6" - Air (Retail) (untuk penggunaan potensial di masa depan) "7" - Surface (Retail) (untuk penggunaan potensial di masa depan) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | PC dan DP harus mematuhi format PAF. |
| [setFormat(int value)](#setFormat-int-) | "0" \\u2013 Null atau Tes "1" \\u2013 Surat "2" \\u2013 Surat Besar |
| [setItemID(int value)](#setItemID-int-) | Nilai maksimum adalah 99999999. |
| [setSupplychainID(int value)](#setSupplychainID-int-) | Nilai maksimum adalah 99 untuk Barcode C dan 999999 untuk Barcode L. |
| [setVersionID(int value)](#setVersionID-int-) | Saat ini "1" \\u2013 Untuk barcode Mailmark (0 dan 2 hingga 9 serta A sampai Z cadangan untuk penggunaan di masa depan) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


Menginisialisasi instance baru dari kelas  MailmarkCodetext  .

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Mendapatkan tipe barcode.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClass_() {#getClass---}
```
public String getClass_()
```


"0" - Null atau Tes "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (untuk penggunaan potensial di masa depan) "5" - Deferred (Retail) "6" - Air (Retail) (untuk penggunaan potensial di masa depan) "7" - Surface (Retail) (untuk penggunaan potensial di masa depan) "8" - Premium (Network Access) "9" - Standard (Network Access)

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Membuat codetext dari data Mailmark.

**Returns:**
java.lang.String - Teks kode yang dibangun
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


PC dan DP harus mematuhi format PAF. String sembilan karakter yang menunjukkan kode internasional "XY11 " (catat 5 spasi di akhir) atau pola karakter yang menunjukkan kode penyortiran domestik. Kode penyortiran domestik terdiri dari kode pos keluar, kode pos masuk, dan Sufiks Titik Pengiriman.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


"0" \\u2013 Null atau Tes "1" \\u2013 Surat "2" \\u2013 Surat Besar

**Returns:**
int
### getItemID() {#getItemID--}
```
public int getItemID()
```


Nilai maksimum adalah 99999999.

**Returns:**
int
### getSupplychainID() {#getSupplychainID--}
```
public int getSupplychainID()
```


Nilai maksimum adalah 99 untuk Barcode C dan 999999 untuk Barcode L.

**Returns:**
int
### getVersionID() {#getVersionID--}
```
public int getVersionID()
```


Saat ini "1" \\u2013 Untuk barcode Mailmark (0 dan 2 hingga 9 serta A sampai Z cadangan untuk penggunaan di masa depan)

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Menginisialisasi data Mailmark dari codetext yang dibangun.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Teks kode yang dibangun. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setClass(String value) {#setClass-java.lang.String-}
```
public void setClass(String value)
```


"0" - Null atau Tes "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (untuk penggunaan potensial di masa depan) "5" - Deferred (Retail) "6" - Air (Retail) (untuk penggunaan potensial di masa depan) "7" - Surface (Retail) (untuk penggunaan potensial di masa depan) "8" - Premium (Network Access) "9" - Standard (Network Access)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


PC dan DP harus mematuhi format PAF. String sembilan karakter yang menunjukkan kode internasional "XY11 " (catat 5 spasi di akhir) atau pola karakter yang menunjukkan kode penyortiran domestik. Kode penyortiran domestik terdiri dari kode pos keluar, kode pos masuk, dan Sufiks Titik Pengiriman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


"0" \\u2013 Null atau Tes "1" \\u2013 Surat "2" \\u2013 Surat Besar

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Nilai maksimum adalah 99999999.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


Nilai maksimum adalah 99 untuk Barcode C dan 999999 untuk Barcode L.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


Saat ini "1" \\u2013 Untuk barcode Mailmark (0 dan 2 hingga 9 serta A sampai Z cadangan untuk penggunaan di masa depan)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

