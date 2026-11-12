---
title: "Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode Royal Mail 2D Mailmark."
type: docs
weight: 570
url: /id/nodejs/aspose.barcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode Royal Mail 2D Mailmark.

```js
new Mailmark2DCodetext()
```

Buat instance default dari kelas Mailmark2DCodetext.

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Mendapatkan tipe barcode. |
| [getClass_()](#getclass-) | Mengidentifikasi kelas item. Nilai yang valid: '1' - 1C (Ritel) '2' - 2C (Ritel) '3' - Ekonomi (Ritel) '5' - Deffere |
| [getConstructedCodetext()](#getconstructedcodetext) | Membangun codetext dari data Mailmark. |
| [getCustomerContent()](#getcustomercontent) | Ruang opsional untuk penggunaan oleh pelanggan. Panjang maksimum per Tipe: Tipe 7: 6 karakter Tipe 9: 45 karakter Tipe 29: 25 karakter |
| [getCustomerContentEncodeMode()](#getcustomercontentencodemode) | Mode enkode barcode Datamatrix. Nilai default: DataMatrixEncodeMode.C40. |
| [getDataMatrixType()](#getdatamatrixtype) | Tipe Mailmark 2D menentukan ukuran barcode Data Matrix. |
| [getDestinationPostCodeAndDPS()](#getdestinationpostcodeanddps) | Berisi Kode Pos dari Alamat Pengiriman dengan DPS. Jika di daratan, Kode Pos/DP berisi jumlah karakter berikut |
| [getInformationTypeID()](#getinformationtypeid) | Mengidentifikasi muatan barcode Royal Mail Mailmark untuk setiap tipe produk. Nilai yang valid: '0' - Domestik Terurut & Tidak Terurut |
| [getItemID()](#getitemid) | Mengidentifikasi item unik dalam Supply Chain ID. Setiap kode batang Mailmark harus membawa ID sehingga dapat di un |
| [getReturnToSenderPostCode()](#getreturntosenderpostcode) | Berisi Kode Pos Pengembalian ke Pengirim tetapi tanpa DPS. PC (tanpa DPS) harus mematuhi format PAF®. |
| [getRTSFlag()](#getrtsflag) | Bendera yang menunjukkan tingkat layanan Pengembalian ke Pengirim yang diminta. |
| [getSupplyChainID()](#getsupplychainid) | Mengidentifikasi grup unik pelanggan yang terlibat dalam pengiriman surat. Nilai maksimum: 9999999. |
| [getUPUCountryID()](#getupucountryid) | Mengidentifikasi ID Negara UPU. Panjang maksimum: 4 karakter. |
| [getVersionID()](#getversionid) | Mengidentifikasi versi kode batang yang relevan untuk setiap Information Type ID. Nilai valid: Saat ini '1'. '0' & '2' sampai '9' an |
| [initFromString(constructedCodetext)](#initfromstring) | Menginisialisasi data Mailmark dari codetext yang dibangun. |
| [setClass_(value)](#setclass-) | Mengidentifikasi kelas item. Nilai yang valid: '1' - 1C (Ritel) '2' - 2C (Ritel) '3' - Ekonomi (Ritel) '5' - Deffere |
| [setCustomerContent(value)](#setcustomercontent) | Ruang opsional untuk penggunaan oleh pelanggan. Panjang maksimum per Tipe: Tipe 7: 6 karakter Tipe 9: 45 karakter Tipe 29: 25 karakter |
| [setCustomerContentEncodeMode(value)](#setcustomercontentencodemode) | Mode enkode barcode Datamatrix. Nilai default: DataMatrixEncodeMode.C40. |
| [setDataMatrixType(value)](#setdatamatrixtype) | Tipe Mailmark 2D menentukan ukuran barcode Data Matrix. |
| [setDestinationPostCodeAndDPS(value)](#setdestinationpostcodeanddps) | Berisi Kode Pos dari Alamat Pengiriman dengan DPS. Jika di daratan, Kode Pos/DP berisi jumlah karakter berikut |
| [setInformationTypeID(value)](#setinformationtypeid) | Mengidentifikasi muatan barcode Royal Mail Mailmark untuk setiap tipe produk. Nilai yang valid: '0' - Domestik Terurut & Tidak Terurut |
| [setItemID(value)](#setitemid) | Mengidentifikasi item unik dalam Supply Chain ID. Setiap kode batang Mailmark harus membawa ID sehingga dapat di un |
| [setReturnToSenderPostCode(value)](#setreturntosenderpostcode) | Berisi Kode Pos Pengembalian ke Pengirim tetapi tanpa DPS. PC (tanpa DPS) harus mematuhi format PAF®. |
| [setRTSFlag()](#setrtsflag) | Bendera yang menunjukkan tingkat layanan Pengembalian ke Pengirim yang diminta. |
| [setSupplyChainID(value)](#setsupplychainid) | Mengidentifikasi grup unik pelanggan yang terlibat dalam pengiriman surat. Nilai maksimum: 9999999. |
| [setUPUCountryID(value)](#setupucountryid) | Mengidentifikasi ID Negara UPU. Panjang maksimum: 4 karakter. |
| [setVersionID(value)](#setversionid) | Mengidentifikasi versi kode batang yang relevan untuk setiap Information Type ID. Nilai valid: Saat ini '1'. '0' & '2' sampai '9' an |

### getBarcodeType() {#getbarcodetype}

Mendapatkan tipe barcode.

**Returns:** Barcode type.

### getClass_() {#getclass-}

Mengidentifikasi kelas item. Nilai valid: '1' - 1C (Ritel) '2' - 2C (Ritel) '3' - Ekonomi (Ritel) '5' - Tertunda (Ritel) '8' - Premium (Akses Jaringan) '9' - Standar (Akses Jaringan)

**Returns:** class of the item

### getConstructedCodetext() {#getconstructedcodetext}

Membangun codetext dari data Mailmark.

**Returns:** Constructed codetext

### getCustomerContent() {#getcustomercontent}

Ruang opsional untuk penggunaan pelanggan. Panjang maksimum per Tipe: Tipe 7: 6 karakter Tipe 9: 45 karakter Tipe 29: 25 karakter

**Returns:** Customer content

### getCustomerContentEncodeMode() {#getcustomercontentencodemode}

Mode enkode barcode Datamatrix. Nilai default: DataMatrixEncodeMode.C40.

**Returns:** Encode mode of Datamatrix barcode.

### getDataMatrixType() {#getdatamatrixtype}

Tipe Mailmark 2D menentukan ukuran barcode Data Matrix.

**Returns:** Size of Data Matrix barcode

### getDestinationPostCodeAndDPS() {#getdestinationpostcodeanddps}

Berisi Kode Pos Alamat Pengiriman dengan DPS. Jika di daratan, Kode Pos/DP berisi jumlah karakter berikut. Area (1 atau 2 karakter) Distrik (1 atau 2 karakter) Sektor (1 karakter) Unit (2 karakter) DPS (2 karakter). Kode Pos dan DPS harus mematuhi format PAF® yang valid.

**Returns:** the Postcode of the Delivery Address with DPS

### getInformationTypeID() {#getinformationtypeid}

Mengidentifikasi muatan kode batang Royal Mail Mailmark untuk setiap tipe produk. Nilai valid: '0' - Domestik Terurut & Tidak Terurut 'A' - Pos Online 'B' - Franking 'C' - Konsolidasi

**Returns:** Information type ID

### getItemID() {#getitemid}

Mengidentifikasi item unik dalam Supply Chain ID. Setiap kode batang Mailmark harus membawa ID sehingga dapat diidentifikasi secara unik setidaknya selama 90 hari. Nilai maksimum: 99999999.

**Returns:** item within the Supply Chain ID

### getReturnToSenderPostCode() {#getreturntosenderpostcode}

Berisi Kode Pos Pengembalian ke Pengirim tetapi tanpa DPS. PC (tanpa DPS) harus mematuhi format PAF®.

**Returns:** Return to Sender Post Code but no DPS

### getRTSFlag() {#getrtsflag}

Bendera yang menunjukkan tingkat layanan Pengembalian ke Pengirim yang diminta.

**Returns:** RTS Flag

### getSupplyChainID() {#getsupplychainid}

Mengidentifikasi grup unik pelanggan yang terlibat dalam pengiriman surat. Nilai maksimum: 9999999.

**Returns:** Supply chain ID

### getUPUCountryID() {#getupucountryid}

Mengidentifikasi ID Negara UPU. Panjang maksimum: 4 karakter.

**Returns:** Country ID

### getVersionID() {#getversionid}

Mengidentifikasi versi kode batang yang relevan untuk setiap Information Type ID. Nilai valid: Saat ini '1'. '0' & '2' sampai '9' dan 'A' sampai 'Z' cadangan untuk penggunaan potensial di masa depan.

**Returns:** Version ID

### initFromString(constructedCodetext) {#initfromstring}

Menginisialisasi data Mailmark dari codetext yang dibangun.

| Parameter | Deskripsi |
| --- | --- |
| constructedCodetext | Codetext yang dibangun. |

### setClass_(value) {#setclass-}

Mengidentifikasi kelas item. Nilai valid: '1' - 1C (Ritel) '2' - 2C (Ritel) '3' - Ekonomi (Ritel) '5' - Tertunda (Ritel) '8' - Premium (Akses Jaringan) '9' - Standar (Akses Jaringan)

| Parameter | Deskripsi |
| --- | --- |
| nilai | kelas item |

### setCustomerContent(value) {#setcustomercontent}

Ruang opsional untuk penggunaan pelanggan. Panjang maksimum per Tipe: Tipe 7: 6 karakter Tipe 9: 45 karakter Tipe 29: 25 karakter

| Parameter | Deskripsi |
| --- | --- |
| nilai | Konten pelanggan |

### setCustomerContentEncodeMode(value) {#setcustomercontentencodemode}

Mode enkode barcode Datamatrix. Nilai default: DataMatrixEncodeMode.C40.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Mode enkode kode batang Datamatrix. |

### setDataMatrixType(value) {#setdatamatrixtype}

Tipe Mailmark 2D menentukan ukuran barcode Data Matrix.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Ukuran kode batang Data Matrix |

### setDestinationPostCodeAndDPS(value) {#setdestinationpostcodeanddps}

Berisi Kode Pos Alamat Pengiriman dengan DPS. Jika di daratan, Kode Pos/DP berisi jumlah karakter berikut. Area (1 atau 2 karakter) Distrik (1 atau 2 karakter) Sektor (1 karakter) Unit (2 karakter) DPS (2 karakter). Kode Pos dan DPS harus mematuhi format PAF® yang valid.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Kode Pos Alamat Pengiriman dengan DPS |

### setInformationTypeID(value) {#setinformationtypeid}

Mengidentifikasi muatan kode batang Royal Mail Mailmark untuk setiap tipe produk. Nilai valid: '0' - Domestik Terurut & Tidak Terurut 'A' - Pos Online 'B' - Franking 'C' - Konsolidasi

| Parameter | Deskripsi |
| --- | --- |
| nilai | ID tipe informasi |

### setItemID(value) {#setitemid}

Mengidentifikasi item unik dalam Supply Chain ID. Setiap kode batang Mailmark harus membawa ID sehingga dapat diidentifikasi secara unik setidaknya selama 90 hari. Nilai maksimum: 99999999.

| Parameter | Deskripsi |
| --- | --- |
| nilai | item dalam Supply Chain ID |

### setReturnToSenderPostCode(value) {#setreturntosenderpostcode}

Berisi Kode Pos Pengembalian ke Pengirim tetapi tanpa DPS. PC (tanpa DPS) harus mematuhi format PAF®.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Kode Pos Pengembalian ke Pengirim tetapi tanpa DPS |

### setRTSFlag() {#setrtsflag}

Bendera yang menunjukkan tingkat layanan Pengembalian ke Pengirim yang diminta.

**Returns:** RTS Flag

### setSupplyChainID(value) {#setsupplychainid}

Mengidentifikasi grup unik pelanggan yang terlibat dalam pengiriman surat. Nilai maksimum: 9999999.

| Parameter | Deskripsi |
| --- | --- |
| nilai | ID rantai pasokan |

### setUPUCountryID(value) {#setupucountryid}

Mengidentifikasi ID Negara UPU. Panjang maksimum: 4 karakter.

| Parameter | Deskripsi |
| --- | --- |
| nilai | ID negara |

### setVersionID(value) {#setversionid}

Mengidentifikasi versi kode batang yang relevan untuk setiap Information Type ID. Nilai valid: Saat ini '1'. '0' & '2' sampai '9' dan 'A' sampai 'Z' cadangan untuk penggunaan potensial di masa depan.

| Parameter | Deskripsi |
| --- | --- |
| nilai | ID versi |
