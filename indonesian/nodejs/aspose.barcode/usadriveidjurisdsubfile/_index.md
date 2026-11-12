---
title: "USADriveIdJurisdSubfile"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Kelas untuk bidang spesifik yurisdiksi untuk Surat Izin Mengemudi USA."
type: docs
weight: 950
url: /id/nodejs/aspose.barcode/usadriveidjurisdsubfile/
---

## USADriveIdJurisdSubfile class

Kelas untuk bidang spesifik yurisdiksi untuk Surat Izin Mengemudi USA.

```js
new USADriveIdJurisdSubfile()
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addOrReplace(id, value)](#addorreplace) | Menambahkan DataElement baru dengan identifier dan nilai yang ditentukan, atau mengganti elemen yang ada jika ada entri dengan sa |
| [addOrReplaceNode(node)](#addorreplacenode) | Menambahkan DataElement baru atau menggantinya jika ElementID sudah ada. |
| [clear()](#clear) | Menghapus semua elemen data |
| [findDataElement(id, isOpenOrCreate)](#finddataelement) | Mencari elemen data berdasarkan id 3 huruf |
| [get(indexOrId)](#get) | Mendapatkan elemen data berdasarkan indeks atau ID 3 huruf. |
| [insert(index, node)](#insert) | Menyisipkan DataElement yang ditentukan pada indeks yang diberikan. Jika DataElement dengan ElementID yang sama sudah ada, itu akan b |
| [remove(indexOrId)](#remove) | Mencoba menghapus elemen berdasarkan indeks atau ID 3 huruf. |
| [set(indexOrId, value)](#set) | Menetapkan elemen data berdasarkan indeks atau ID 3 huruf. |
| [size()](#size) | Mengembalikan jumlah elemen data |

### addOrReplace(id, value) {#addorreplace}

Menambahkan DataElement baru dengan identifier dan nilai yang ditentukan, atau mengganti elemen yang ada jika ada entri dengan ElementID yang sama sudah ada.

| Parameter | Deskripsi |
| --- | --- |
| id | Identifier 3 huruf yang secara unik menentukan elemen data terkait yurisdiksi. |
| nilai | Nilai teks yang diberikan ke elemen data; nilai ini akan menimpa yang sudah ada jika elemen tersebut sudah ada. |

**Returns:** The DataElement instance that was added to the collection or updated in place.

### addOrReplaceNode(node) {#addorreplacenode}

Menambahkan DataElement baru atau menggantinya jika ElementID sudah ada.

| Parameter | Deskripsi |
| --- | --- |
| node | DataElement untuk ditambahkan |

**Returns:** Added/replaced data element

### clear() {#clear}

Menghapus semua elemen data

### findDataElement(id, isOpenOrCreate) {#finddataelement}

Mencari elemen data berdasarkan id 3 huruf

| Parameter | Deskripsi |
| --- | --- |
| id | id 3 huruf |
| isOpenOrCreate | Jika true, akan dibuat jika tidak ditemukan |

**Returns:** Found data element

### get(indexOrId) {#get}

Mendapatkan elemen data berdasarkan indeks atau ID 3 huruf.

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indexOrId | number\ | string | Indeks integer atau ID elemen 3 huruf. |

**Returns:** DataElement — Corresponding data element.

### insert(index, node) {#insert}

Menyisipkan DataElement yang ditentukan pada indeks yang diberikan. Jika DataElement dengan ElementID yang sama sudah ada, itu akan diganti.

| Parameter | Deskripsi |
| --- | --- |
| index | Indeks berbasis nol tempat elemen harus disisipkan. |
| node | Instansi DataElement untuk disisipkan atau diganti pada posisi target. |

**Returns:** The DataElement that was inserted or used to replace an existing entry.

### remove(indexOrId) {#remove}

Mencoba menghapus elemen berdasarkan indeks atau ID 3 huruf.

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indexOrId | number\ | string | Indeks integer atau ID elemen 3 huruf. |

**Returns:** boolean — true if the element was removed; otherwise, false.

### set(indexOrId, value) {#set}

Menetapkan elemen data berdasarkan indeks atau ID 3 huruf.

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indexOrId | number\ | string | Indeks integer atau ID elemen 3 huruf. |
| nilai | DataElement | Elemen data untuk diatur. |

### size() {#size}

Mengembalikan jumlah elemen data
