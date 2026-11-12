---
title: "Alamat"
linktitle: "Alamat"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Alamat kreditur atau debitur."
type: docs
weight: 10
url: /id/nodejs/aspose.barcode/address/
---

## Address class

Alamat kreditur atau debitur. Anda dapat mengatur jalan, nomor rumah, kode pos, dan kota (tipe alamat terstruktur) atau baris alamat 1 dan 2 (tipe elemen alamat gabungan). Tipe secara otomatis ditetapkan begitu salah satu bidang ini diisi. Sebelum mengisi bidang, tipe alamat belum ditentukan. Jika bidang dari kedua tipe diisi, tipe alamat menjadi konflik. Nama dan kode negara harus selalu diisi kecuali semua bidang kosong.

```js
new Address()
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [clear()](#clear) | Menghapus semua bidang dan mengatur tipe menjadi AddressType.UNDETERMINED. |
| [equals(obj)](#equals) | Menentukan apakah objek yang ditentukan sama dengan objek saat ini. |
| [getAddressLine1()](#getaddressline1) | Mendapatkan baris alamat 1. Baris alamat 1 berisi nama jalan, nomor rumah, atau kotak pos. Menetapkan bidang ini mengatur addr |
| [getAddressLine2()](#getaddressline2) | Mendapatkan baris alamat 2. Baris alamat 2 berisi kode pos dan kota. Menetapkan bidang ini mengatur tipe alamat menjadi Addre |
| [getCountryCode()](#getcountrycode) | Mendapatkan kode negara ISO dua huruf. Kode negara wajib kecuali seluruh alamat berisi nilai null atau kosong |
| [getHouseNo()](#gethouseno) | Mendapatkan nomor rumah. Menetapkan bidang ini mengatur tipe alamat menjadi AddressType.STRUCTURED kecuali sudah AddressTyp |
| [getName()](#getname) | Mendapatkan nama, baik nama depan dan belakang orang alami atau nama perusahaan orang hukum. |
| [getPostalCode()](#getpostalcode) | Mendapatkan kode pos. Menetapkan bidang ini mengatur tipe alamat menjadi AddressType.STRUCTURED kecuali sudah AddressType |
| [getStreet()](#getstreet) | Mendapatkan jalan. Jalan harus ditentukan tanpa nomor rumah. Menetapkan bidang ini mengatur tipe alamat menjadi AddressT |
| [getTown()](#gettown) | Mendapatkan kota atau kota kecil. Menetapkan bidang ini mengatur tipe alamat menjadi AddressType.STRUCTURED kecuali sudah AddressTyp |
| [getType()](#gettype) | Mendapatkan tipe alamat. Tipe alamat secara otomatis diatur dengan mengatur jalan / nomor rumah atau baris alamat 1 a |
| [hashCode()](#hashcode) | Mendapatkan kode hash untuk instance ini. |
| [setAddressLine1(value:)](#setaddressline1) | Mengatur baris alamat 1. Baris alamat 1 berisi nama jalan, nomor rumah, atau kotak pos. Menetapkan bidang ini mengatur addr |
| [setAddressLine2(value:)](#setaddressline2) | Mengatur baris alamat 2. Baris alamat 2 berisi kode pos dan kota. Mengatur bidang ini mengatur tipe alamat menjadi Addre |
| [setCountryCode(value)](#setcountrycode) | Mengatur kode negara ISO dua huruf. Kode negara wajib kecuali seluruh alamat berisi null atau emtpy val |
| [setHouseNo(value:)](#sethouseno) | Mengatur nomor rumah. Mengatur bidang ini mengatur tipe alamat menjadi AddressType.STRUCTURED kecuali sudah menjadi AddressTyp |
| [setName(value:)](#setname) | Mengatur nama, baik nama depan dan belakang orang alami maupun nama perusahaan orang hukum. |
| [setPostalCode(value)](#setpostalcode) | Mengatur kode pos. Mengatur bidang ini mengatur tipe alamat menjadi AddressType.STRUCTURED kecuali sudah menjadi AddressType |
| [setStreet(value:)](#setstreet) | Mengatur jalan. Jalan harus ditentukan tanpa nomor rumah. Mengatur bidang ini mengatur tipe alamat menjadi AddressT |
| [setTown(value)](#settown) | Mengatur kota atau kabupaten. Mengatur bidang ini mengatur tipe alamat menjadi AddressType.STRUCTURED kecuali sudah menjadi AddressTyp |

### clear() {#clear}

Menghapus semua bidang dan mengatur tipe menjadi AddressType.UNDETERMINED.

### equals(obj) {#equals}

Menentukan apakah objek yang ditentukan sama dengan objek saat ini.

| Parameter | Deskripsi |
| --- | --- |
| obj | Objek yang dibandingkan dengan objek saat ini. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAddressLine1() {#getaddressline1}

Mendapatkan baris alamat 1. Baris alamat 1 berisi nama jalan, nomor rumah, atau kotak pos. Mengatur bidang ini mengatur tipe alamat menjadi AddressType.COMBINED_ELEMENTS kecuali sudah menjadi AddressType.STRUCTURED, dalam hal ini menjadi AddressType.CONFLICTING. Bidang ini hanya digunakan untuk alamat dengan elemen gabungan dan bersifat opsional.

**Returns:** The address line 1.

### getAddressLine2() {#getaddressline2}

Mendapatkan baris alamat 2. Baris alamat 2 berisi kode pos dan kota. Mengatur bidang ini mengatur tipe alamat menjadi AddressType.COMBINED_ELEMENTS kecuali sudah menjadi AddressType.STRUCTURED, dalam hal ini menjadi AddressType.CONFLICTING. Bidang ini hanya digunakan untuk alamat dengan elemen gabungan. Untuk tipe ini, bidang ini wajib.

**Returns:** The address line 2.

### getCountryCode() {#getcountrycode}

Mendapatkan kode negara ISO dua huruf. Kode negara wajib kecuali seluruh alamat berisi null atau emtpy values.

**Returns:** The ISO country code.

### getHouseNo() {#gethouseno}

Mendapatkan nomor rumah. Mengatur bidang ini mengatur tipe alamat menjadi AddressType.STRUCTURED kecuali sudah menjadi AddressType.COMBINED_ELEMENTS, dalam hal ini menjadi AddressType.CONFLICTING. Bidang ini hanya digunakan untuk alamat terstruktur dan bersifat opsional.

**Returns:** The house number.

### getName() {#getname}

Mendapatkan nama, baik nama depan dan belakang orang alami atau nama perusahaan orang hukum.

**Returns:** The name.

### getPostalCode() {#getpostalcode}

Mendapatkan kode pos. Mengatur bidang ini mengatur tipe alamat menjadi AddressType.STRUCTURED kecuali sudah menjadi AddressType.COMBINED_ELEMENTS, dalam hal ini menjadi AddressType.CONFLICTING. Bidang ini hanya digunakan untuk alamat terstruktur. Untuk tipe ini, bidang ini wajib.

**Returns:** The postal code.

### getStreet() {#getstreet}

Mendapatkan jalan. Jalan harus ditentukan tanpa nomor rumah. Mengatur bidang ini mengatur tipe alamat menjadi AddressType.STRUCTURED kecuali sudah menjadi AddressType.COMBINED_ELEMENTS, dalam hal ini menjadi AddressType.CONFLICTING. Bidang ini hanya digunakan untuk alamat terstruktur dan bersifat opsional.

**Returns:** The street.

### getTown() {#gettown}

Mendapatkan kota atau kabupaten. Mengatur bidang ini mengatur tipe alamat menjadi AddressType.STRUCTURED kecuali sudah menjadi AddressType.COMBINED_ELEMENTS, dalam hal ini menjadi AddressType.CONFLICTING. Bidang ini hanya digunakan untuk alamat terstruktur. Untuk tipe ini, bidang ini wajib.

**Returns:** The town or city.

### getType() {#gettype}

Mendapatkan tipe alamat. Tipe alamat secara otomatis diatur dengan mengatur jalan / nomor rumah atau baris alamat 1 dan 2. Sebelum mengatur bidang, tipe alamat adalah Undetermined. Jika bidang dari kedua tipe diatur, tipe alamat menjadi Conflicting.

**Returns:** The address type.

### hashCode() {#hashcode}

Mendapatkan kode hash untuk instance ini.

**Returns:** A hash code for the current object .

### setAddressLine1(value:) {#setaddressline1}

Mengatur baris alamat 1. Baris alamat 1 berisi nama jalan, nomor rumah, atau kotak pos. Mengatur bidang ini mengatur tipe alamat menjadi AddressType.COMBINED_ELEMENTS kecuali sudah menjadi AddressType.STRUCTURED, dalam hal ini menjadi AddressType.CONFLICTING. Bidang ini hanya digunakan untuk alamat dengan elemen gabungan dan bersifat opsional.

| Parameter | Deskripsi |
| --- | --- |
| nilai: | Baris alamat 1. |

### setAddressLine2(value:) {#setaddressline2}

Mengatur baris alamat 2. Baris alamat 2 berisi kode pos dan kota. Mengatur bidang ini mengatur tipe alamat menjadi AddressType.COMBINED_ELEMENTS kecuali sudah menjadi AddressType.STRUCTURED, dalam hal ini menjadi AddressType.CONFLICTING. Bidang ini hanya digunakan untuk alamat dengan elemen gabungan. Untuk tipe ini, bidang ini wajib.

| Parameter | Deskripsi |
| --- | --- |
| nilai: | Baris alamat 2. |

### setCountryCode(value) {#setcountrycode}

Mengatur kode negara ISO dua huruf. Kode negara wajib kecuali seluruh alamat berisi null atau emtpy values.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Kode negara ISO. |

### setHouseNo(value:) {#sethouseno}

Mengatur nomor rumah. Mengatur bidang ini mengatur tipe alamat menjadi AddressType.STRUCTURED kecuali sudah AddressType.COMBINED_ELEMENTS, dalam hal ini menjadi AddressType.CONFLICTING. Bidang ini hanya digunakan untuk alamat terstruktur dan bersifat opsional.

| Parameter | Deskripsi |
| --- | --- |
| nilai: | Nomor rumah. |

### setName(value:) {#setname}

Mengatur nama, baik nama depan dan belakang orang alami maupun nama perusahaan orang hukum.

| Parameter | Deskripsi |
| --- | --- |
| nilai: | Nama. |

### setPostalCode(value) {#setpostalcode}

Mengatur kode pos. Mengatur bidang ini mengatur tipe alamat menjadi AddressType.STRUCTURED kecuali sudah AddressType.COMBINED_ELEMENTS, dalam hal ini menjadi AddressType.CONFLICTING. Bidang ini hanya digunakan untuk alamat terstruktur. Untuk tipe ini, bersifat wajib.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Kode pos. |

### setStreet(value:) {#setstreet}

Mengatur jalan. Jalan harus ditentukan tanpa nomor rumah. Mengatur bidang ini mengatur tipe alamat menjadi AddressType.STRUCTURED kecuali sudah AddressType.COMBINED_ELEMENTS, dalam hal ini menjadi AddressType.CONFLICTING. Bidang ini hanya digunakan untuk alamat terstruktur dan bersifat opsional.

| Parameter | Deskripsi |
| --- | --- |
| nilai: | Jalan. |

### setTown(value) {#settown}

Mengatur kota atau kota kecil. Mengatur bidang ini mengatur tipe alamat menjadi AddressType.STRUCTURED kecuali sudah AddressType.COMBINED_ELEMENTS, dalam hal ini menjadi AddressType.CONFLICTING. Bidang ini hanya digunakan untuk alamat terstruktur. Untuk tipe ini, bersifat wajib.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Kota atau kota kecil. |
