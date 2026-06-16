---
title: SwissQRBill
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Data tagihan SwissQR
type: docs
weight: 36
url: /id/androidjava/com.aspose.barcode.complexbarcode/swissqrbill/
---
**Inheritance:**
java.lang.Object
```
public final class SwissQRBill
```

Data tagihan SwissQR
## Methods

| Method | Deskripsi |
| --- | --- |
| [createAndSetCreditorReference(String rawReference)](#createAndSetCreditorReference-java.lang.String-) | Membuat dan mengatur referensi kreditur ISO11649 dari string mentah dengan menambahkan awalan "RF" pada String dan checksum modulo 97. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah objek yang ditentukan sama dengan objek saat ini. |
| [getAccount()](#getAccount--) | Mendapatkan nomor akun kreditur. |
| [getAlternativeSchemes()](#getAlternativeSchemes--) | Mendapatkan atau mengatur skema pembayaran alternatif. |
| [getAmount()](#getAmount--) | Mendapatkan jumlah pembayaran. |
| [getBillInformation()](#getBillInformation--) | Mendapatkan informasi tagihan terstruktur tambahan. |
| [getClass()](#getClass--) |  |
| [getCreditor()](#getCreditor--) | Mendapatkan alamat kreditur. |
| [getCurrency()](#getCurrency--) | Mendapatkan mata uang pembayaran. |
| [getDebtor()](#getDebtor--) | Mendapatkan alamat debitur. |
| [getReference()](#getReference--) | Mendapatkan referensi pembayaran kreditur. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | Mendapatkan pesan tidak terstruktur tambahan. |
| [getVersion()](#getVersion--) | Mendapatkan versi standar tagihan SwissQR. |
| [hashCode()](#hashCode--) | Mendapatkan kode hash untuk instance ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccount(String value)](#setAccount-java.lang.String-) | Mengatur nomor rekening kreditur. |
| [setAlternativeSchemes(List<AlternativeScheme> value)](#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--) | Mendapatkan atau mengatur skema pembayaran alternatif. |
| [setAmount(double value)](#setAmount-double-) | Mengatur jumlah pembayaran. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Mengatur informasi tagihan terstruktur tambahan. |
| [setCreditor(Address value)](#setCreditor-com.aspose.barcode.complexbarcode.Address-) | Mengatur alamat kreditur. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | Mengatur mata uang pembayaran. |
| [setDebtor(Address value)](#setDebtor-com.aspose.barcode.complexbarcode.Address-) | Mengatur alamat debitur. |
| [setReference(String value)](#setReference-java.lang.String-) | Mengatur referensi pembayaran kreditur. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Mengatur pesan tidak terstruktur tambahan. |
| [setVersion(QrBillStandardVersion value)](#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-) | Mengatur versi standar tagihan SwissQR. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createAndSetCreditorReference(String rawReference) {#createAndSetCreditorReference-java.lang.String-}
```
public void createAndSetCreditorReference(String rawReference)
```


Membuat dan mengatur referensi kreditur ISO11649 dari string mentah dengan menambahkan awalan "RF" pada String dan checksum modulo 97.

Spasi putih dihapus dari referensi

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| rawReference | java.lang.String | Referensi mentah. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah objek yang ditentukan sama dengan objek saat ini.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek yang akan dibandingkan dengan objek saat ini. |

**Returns:**
boolean -  true  jika objek yang ditentukan sama dengan objek saat ini; jika tidak,  false .
### getAccount() {#getAccount--}
```
public String getAccount()
```


Mendapatkan nomor akun kreditur.

Nomor rekening harus berupa IBAN yang valid dari bank di Swiss atau Liechtenstein. Spasi diizinkan dalam nomor rekening.

Nilai: Nomor rekening kreditur.

**Returns:**
java.lang.String
### getAlternativeSchemes() {#getAlternativeSchemes--}
```
public List<AlternativeScheme> getAlternativeSchemes()
```


Mendapatkan atau mengatur skema pembayaran alternatif.

Maksimum dua skema dengan parameter diperbolehkan.

Nilai: Skema pembayaran alternatif.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme>
### getAmount() {#getAmount--}
```
public double getAmount()
```


Mendapatkan jumlah pembayaran.

Nilai yang valid berada di antara 0.01 dan 999,999,999.99.

Nilai: Jumlah pembayaran.

**Returns:**
double
### getBillInformation() {#getBillInformation--}
```
public String getBillInformation()
```


Mendapatkan informasi tagihan terstruktur tambahan.

Nilai: Informasi tagihan terstruktur.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreditor() {#getCreditor--}
```
public Address getCreditor()
```


Mendapatkan alamat kreditur.

Nilai: Alamat kreditur.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getCurrency() {#getCurrency--}
```
public String getCurrency()
```


Mendapatkan mata uang pembayaran.

Nilai yang valid adalah "CHF" dan "EUR".

Nilai: Mata uang pembayaran.

**Returns:**
java.lang.String
### getDebtor() {#getDebtor--}
```
public Address getDebtor()
```


Mendapatkan alamat debitur.

Debitur bersifat opsional. Jika diabaikan, baik mengatur bidang ini menjadi  null  atau mengatur alamat dengan semua nilai  null  atau kosong dianggap ok.

Nilai: Alamat debitur.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getReference() {#getReference--}
```
public String getReference()
```


Mendapatkan referensi pembayaran kreditur.

Referensi wajib untuk IBAN SwissQR, yaitu IBAN dalam rentang CHxx30000xxxxxx hingga CHxx31999xxxxx.

Jika ditentukan, referensi harus berupa referensi SwissQR yang valid (sesuai format referensi ISR) atau referensi kreditur yang valid menurut ISO 11649 ("RFxxxx"). Kedua-duanya dapat berisi spasi untuk pemformatan.

Nilai: Referensi pembayaran kreditur.

**Returns:**
java.lang.String
### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public String getUnstructuredMessage()
```


Mendapatkan pesan tidak terstruktur tambahan.

Nilai: Pesan tidak terstruktur.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public QrBillStandardVersion getVersion()
```


Mendapatkan versi standar tagihan SwissQR.

Nilai: Versi standar tagihan SwissQR.

**Returns:**
[QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mendapatkan kode hash untuk instance ini.

**Returns:**
int - Kode hash untuk objek saat ini.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAccount(String value) {#setAccount-java.lang.String-}
```
public void setAccount(String value)
```


Mengatur nomor rekening kreditur.

Nomor rekening harus berupa IBAN yang valid dari bank di Swiss atau Liechtenstein. Spasi diizinkan dalam nomor rekening.

Nilai: Nomor rekening kreditur.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setAlternativeSchemes(List<AlternativeScheme> value) {#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--}
```
public void setAlternativeSchemes(List<AlternativeScheme> value)
```


Mendapatkan atau mengatur skema pembayaran alternatif.

Maksimum dua skema dengan parameter diperbolehkan.

Nilai: Skema pembayaran alternatif.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme> |  |

### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


Mengatur jumlah pembayaran.

Nilai yang valid berada di antara 0.01 dan 999,999,999.99.

Nilai: Jumlah pembayaran.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public void setBillInformation(String value)
```


Mengatur informasi tagihan terstruktur tambahan.

Nilai: Informasi tagihan terstruktur.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setCreditor(Address value) {#setCreditor-com.aspose.barcode.complexbarcode.Address-}
```
public void setCreditor(Address value)
```


Mengatur alamat kreditur.

Nilai: Alamat kreditur.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public void setCurrency(String value)
```


Mengatur mata uang pembayaran.

Nilai yang valid adalah "CHF" dan "EUR".

Nilai: Mata uang pembayaran.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setDebtor(Address value) {#setDebtor-com.aspose.barcode.complexbarcode.Address-}
```
public void setDebtor(Address value)
```


Mengatur alamat debitur.

Debitur bersifat opsional. Jika diabaikan, baik mengatur bidang ini menjadi  null  atau mengatur alamat dengan semua nilai  null  atau kosong dianggap ok.

Nilai: Alamat debitur.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setReference(String value) {#setReference-java.lang.String-}
```
public void setReference(String value)
```


Mengatur referensi pembayaran kreditur.

Referensi wajib untuk IBAN SwissQR, yaitu IBAN dalam rentang CHxx30000xxxxxx hingga CHxx31999xxxxx.

Jika ditentukan, referensi harus berupa referensi SwissQR yang valid (sesuai format referensi ISR) atau referensi kreditur yang valid menurut ISO 11649 ("RFxxxx"). Kedua-duanya dapat berisi spasi untuk pemformatan.

Nilai: Referensi pembayaran kreditur.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public void setUnstructuredMessage(String value)
```


Mengatur pesan tidak terstruktur tambahan.

Nilai: Pesan tidak terstruktur.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setVersion(QrBillStandardVersion value) {#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-}
```
public void setVersion(QrBillStandardVersion value)
```


Mengatur versi standar tagihan SwissQR.

Nilai: Versi standar tagihan SwissQR.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion) |  |

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

