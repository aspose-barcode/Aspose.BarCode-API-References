---
title: Alamat
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Alamat kreditor atau debitor.
type: docs
weight: 10
url: /id/androidjava/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

Alamat kreditor atau debitor.

Anda dapat mengatur jalan, nomor rumah, kode pos, dan kota (tipe *structured address*) atau baris alamat 1 dan 2 (tipe *combined address elements*). Tipe secara otomatis ditetapkan setelah salah satu bidang ini diisi. Sebelum mengisi bidang, tipe alamat adalah *undetermined*. Jika bidang dari kedua tipe diisi, tipe alamat menjadi *conflicting*. Nama dan kode negara harus selalu diisi kecuali semua bidang kosong.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [Address()](#Address--) | Membuat instance dari Alamat |
## Methods

| Method | Deskripsi |
| --- | --- |
| [clear()](#clear--) | Menghapus semua bidang dan mengatur tipe menjadi AddressType.Undetermined. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah objek yang ditentukan sama dengan objek saat ini. |
| [getAddressLine1()](#getAddressLine1--) | Mendapatkan baris alamat 1. |
| [getAddressLine2()](#getAddressLine2--) | Mendapatkan baris alamat 2. |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | Mendapatkan kode negara ISO dua huruf. |
| [getHouseNo()](#getHouseNo--) | Mendapatkan nomor rumah. |
| [getName()](#getName--) | Mendapatkan nama, baik nama depan dan belakang orang alami atau nama perusahaan orang hukum. |
| [getPostalCode()](#getPostalCode--) | Mendapatkan kode pos. |
| [getStreet()](#getStreet--) | Mendapatkan jalan. |
| [getTown()](#getTown--) | Mendapatkan kota atau kota. |
| [getType()](#getType--) | Mendapatkan tipe alamat. |
| [hashCode()](#hashCode--) | Mendapatkan kode hash untuk instance ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Mengatur baris alamat 1. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Mengatur baris alamat 2. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Mengatur kode negara ISO dua huruf. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Mengatur nomor rumah. |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama, baik nama depan dan belakang orang alami atau nama perusahaan orang hukum. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Mengatur kode pos. |
| [setStreet(String value)](#setStreet-java.lang.String-) | Mengatur jalan. |
| [setTown(String value)](#setTown-java.lang.String-) | Mengatur kota atau kota. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


Membuat instance dari Alamat

### clear() {#clear--}
```
public void clear()
```


Menghapus semua bidang dan mengatur tipe menjadi AddressType.Undetermined.

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
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


Mendapatkan baris alamat 1.

Baris alamat 1 berisi nama jalan, nomor rumah, atau P.O. box.

Mengatur bidang ini mengatur tipe alamat menjadi AddressType.CombinedElements kecuali sudah AddressType.Structured, dalam hal ini menjadi AddressType.Conflicting.

Bidang ini hanya digunakan untuk alamat elemen gabungan dan bersifat opsional.

Nilai: Baris alamat 1.

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


Mendapatkan baris alamat 2.

Baris alamat 2 berisi kode pos dan kota.

Mengatur bidang ini mengatur tipe alamat menjadi AddressType.CombinedElements kecuali sudah AddressType.Structured, dalam hal ini menjadi AddressType.Conflicting.

Bidang ini hanya digunakan untuk alamat elemen gabungan. Untuk tipe ini, wajib diisi.

Nilai: Baris alamat 2.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryCode() {#getCountryCode--}
```
public String getCountryCode()
```


Mendapatkan kode negara ISO dua huruf.

Kode negara wajib kecuali seluruh alamat berisi  null  atau nilai kosong.

Nilai: Kode negara ISO.

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


Mendapatkan nomor rumah.

Mengatur bidang ini mengatur tipe alamat menjadi  AddressType.Structured  kecuali sudah  AddressType.CombinedElements , dalam hal ini menjadi  AddressType.Conflicting .

Bidang ini hanya digunakan untuk alamat terstruktur dan bersifat opsional.

Nilai: Nomor rumah.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama, baik nama depan dan belakang orang alami atau nama perusahaan orang hukum.

Nilai: Nama.

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Mendapatkan kode pos.

Mengatur bidang ini mengatur tipe alamat menjadi  AddressType.Structured  kecuali sudah  AddressType.CombinedElements , dalam hal ini menjadi  AddressType.Conflicting .

Bidang ini hanya digunakan untuk alamat terstruktur. Untuk tipe ini, wajib.

Nilai: Kode pos.

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


Mendapatkan jalan.

Jalan harus ditentukan tanpa nomor rumah.

Mengatur bidang ini mengatur tipe alamat menjadi  AddressType.Structured  kecuali sudah  AddressType.CombinedElements , dalam hal ini menjadi  AddressType.Conflicting .

Bidang ini hanya digunakan untuk alamat terstruktur dan bersifat opsional.

Nilai: Jalan.

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


Mendapatkan kota atau kota.

Mengatur bidang ini mengatur tipe alamat menjadi  AddressType.Structured  kecuali sudah  AddressType.CombinedElements , dalam hal ini menjadi  AddressType.Conflicting .

Bidang ini hanya digunakan untuk alamat terstruktur. Untuk tipe ini, wajib.

Nilai: Kota atau kota.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


Mendapatkan tipe alamat.

Tipe alamat secara otomatis diatur dengan mengatur jalan / nomor rumah atau baris alamat 1 dan 2. Sebelum mengatur bidang, tipe alamat adalah  *Undetermined* . Jika bidang dari kedua tipe diatur, tipe alamat menjadi  *Conflicting* .

Nilai: Tipe alamat.

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
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




### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public void setAddressLine1(String value)
```


Mengatur baris alamat 1.

Baris alamat 1 berisi nama jalan, nomor rumah, atau P.O. box.

Mengatur bidang ini mengatur tipe alamat menjadi AddressType.CombinedElements kecuali sudah AddressType.Structured, dalam hal ini menjadi AddressType.Conflicting.

Bidang ini hanya digunakan untuk alamat elemen gabungan dan bersifat opsional.

Nilai: Baris alamat 1.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


Mengatur baris alamat 2.

Baris alamat 2 berisi kode pos dan kota.

Mengatur bidang ini mengatur tipe alamat menjadi AddressType.CombinedElements kecuali sudah AddressType.Structured, dalam hal ini menjadi AddressType.Conflicting.

Bidang ini hanya digunakan untuk alamat elemen gabungan. Untuk tipe ini, wajib diisi.

Nilai: Baris alamat 2.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


Mengatur kode negara ISO dua huruf.

Kode negara wajib kecuali seluruh alamat berisi  null  atau nilai kosong.

Nilai: Kode negara ISO.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


Mengatur nomor rumah.

Mengatur bidang ini mengatur tipe alamat menjadi  AddressType.Structured  kecuali sudah  AddressType.CombinedElements , dalam hal ini menjadi  AddressType.Conflicting .

Bidang ini hanya digunakan untuk alamat terstruktur dan bersifat opsional.

Nilai: Nomor rumah.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Mengatur nama, baik nama depan dan belakang orang alami atau nama perusahaan orang hukum.

Nilai: Nama.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


Mengatur kode pos.

Mengatur bidang ini mengatur tipe alamat menjadi  AddressType.Structured  kecuali sudah  AddressType.CombinedElements , dalam hal ini menjadi  AddressType.Conflicting .

Bidang ini hanya digunakan untuk alamat terstruktur. Untuk tipe ini, wajib.

Nilai: Kode pos.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


Mengatur jalan.

Jalan harus ditentukan tanpa nomor rumah.

Mengatur bidang ini mengatur tipe alamat menjadi  AddressType.Structured  kecuali sudah  AddressType.CombinedElements , dalam hal ini menjadi  AddressType.Conflicting .

Bidang ini hanya digunakan untuk alamat terstruktur dan bersifat opsional.

Nilai: Jalan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


Mengatur kota atau kota.

Mengatur bidang ini mengatur tipe alamat menjadi  AddressType.Structured  kecuali sudah  AddressType.CombinedElements , dalam hal ini menjadi  AddressType.Conflicting .

Bidang ini hanya digunakan untuk alamat terstruktur. Untuk tipe ini, wajib.

Nilai: Kota atau kota.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

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

