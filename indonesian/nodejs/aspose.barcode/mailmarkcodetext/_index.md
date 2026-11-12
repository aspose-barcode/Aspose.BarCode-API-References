---
title: "MailmarkCodetext"
linktitle: "MailmarkCodetext"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode Royal Mailmark 4-status."
type: docs
weight: 580
url: /id/nodejs/aspose.barcode/mailmarkcodetext/
---

## MailmarkCodetext class

Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode Royal Mailmark 4-status.

```js
new MailmarkCodetext()
```

Menginisialisasi instance baru dari kelas `MailmarkCodetext`.

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Mendapatkan tipe barcode. |
| [getClass_()](#getclass-) | "0" - Null atau Tes "1" - 1C (Ritel) "2" - 2C (Ritel) "3" - 3C (Ritel) "4" - Premium (RetailPublishing Mail) (untuk pote |
| [getConstructedCodetext()](#getconstructedcodetext) | Membangun codetext dari data Mailmark. |
| [getDestinationPostCodePlusDPS()](#getdestinationpostcodeplusdps) | PC dan DP harus mematuhi format PAF. String sembilan karakter yang menunjukkan internasional "XY11 " (catat 5 spasi trailing s |
| [getFormat()](#getformat) | "0" – Null atau Tes "1" – Huruf "2" – Huruf Besar |
| [getItemID()](#getitemid) | Nilai maksimum adalah 99999999. |
| [getSupplychainID()](#getsupplychainid) | Nilai maksimum adalah 99 untuk Barcode C dan 999999 untuk Barcode L. |
| [getVersionID()](#getversionid) | Saat ini "1" – Untuk barcode Mailmark (0 dan 2 hingga 9 serta A sampai Z disiapkan untuk penggunaan di masa depan) |
| [initFromString(constructedCodetext)](#initfromstring) | Menginisialisasi data Mailmark dari codetext yang dibangun. |
| [setClass_()](#setclass-) | "0" - Null atau Tes "1" - 1C (Ritel) "2" - 2C (Ritel) "3" - 3C (Ritel) "4" - Premium (RetailPublishing Mail) (untuk pote |
| [setDestinationPostCodePlusDPS()](#setdestinationpostcodeplusdps) | PC dan DP harus mematuhi format PAF. String sembilan karakter yang menunjukkan internasional "XY11 " (catat 5 spasi trailing s |
| [setFormat()](#setformat) | "0" – Null atau Tes "1" – LetterN "2" – Huruf Besar |
| [setItemID()](#setitemid) | Nilai maksimum adalah 99999999. |
| [setSupplychainID()](#setsupplychainid) | Nilai maksimum adalah 99 untuk Barcode C dan 999999 untuk Barcode L. |
| [setVersionID()](#setversionid) | Saat ini "1" – Untuk barcode Mailmark (0 dan 2 hingga 9 serta A sampai Z disiapkan untuk penggunaan di masa depan) |

### getBarcodeType() {#getbarcodetype}

Mendapatkan tipe barcode.

**Returns:** Barcode type.

### getClass_() {#getclass-}

"0" - Null atau Tes "1" - 1C (Ritel) "2" - 2C (Ritel) "3" - 3C (Ritel) "4" - Premium (RetailPublishing Mail) (untuk penggunaan potensial di masa depan) "5" - Deferred (Ritel) "6" - Air (Ritel) (untuk penggunaan potensial di masa depan) "7" - Surface (Ritel) (untuk penggunaan potensial di masa depan) "8" - Premium (Akses Jaringan) "9" - Standard (Akses Jaringan)

### getConstructedCodetext() {#getconstructedcodetext}

Membangun codetext dari data Mailmark.

**Returns:** Constructed codetext

### getDestinationPostCodePlusDPS() {#getdestinationpostcodeplusdps}

PC dan DP harus mematuhi format PAF. String sembilan karakter yang menunjukkan internasional "XY11 " (catat 5 spasi trailing) atau pola karakter yang menunjukkan kode penyortiran domestik. Kode penyortiran domestik terdiri dari kode pos keluar, kode pos masuk, dan Sufiks Titik Pengiriman.

### getFormat() {#getformat}

"0" – Null atau Tes "1" – Huruf "2" – Huruf Besar

### getItemID() {#getitemid}

Nilai maksimum adalah 99999999.

### getSupplychainID() {#getsupplychainid}

Nilai maksimum adalah 99 untuk Barcode C dan 999999 untuk Barcode L.

### getVersionID() {#getversionid}

Saat ini "1" – Untuk barcode Mailmark (0 dan 2 hingga 9 serta A sampai Z disiapkan untuk penggunaan di masa depan)

### initFromString(constructedCodetext) {#initfromstring}

Menginisialisasi data Mailmark dari codetext yang dibangun.

| Parameter | Deskripsi |
| --- | --- |
| constructedCodetext | Codetext yang dibangun. |

### setClass_() {#setclass-}

"0" - Null atau Tes "1" - 1C (Ritel) "2" - 2C (Ritel) "3" - 3C (Ritel) "4" - Premium (RetailPublishing Mail) (untuk penggunaan potensial di masa depan) "5" - Deferred (Ritel) "6" - Air (Ritel) (untuk penggunaan potensial di masa depan) "7" - Surface (Ritel) (untuk penggunaan potensial di masa depan) "8" - Premium (Akses Jaringan) "9" - Standard (Akses Jaringan)

### setDestinationPostCodePlusDPS() {#setdestinationpostcodeplusdps}

PC dan DP harus mematuhi format PAF. String sembilan karakter yang menunjukkan internasional "XY11 " (catat 5 spasi trailing) atau pola karakter yang menunjukkan kode penyortiran domestik. Kode penyortiran domestik terdiri dari kode pos keluar, kode pos masuk, dan Sufiks Titik Pengiriman.

### setFormat() {#setformat}

"0" – Null atau Tes "1" – LetterN "2" – Huruf Besar

### setItemID() {#setitemid}

Nilai maksimum adalah 99999999.

### setSupplychainID() {#setsupplychainid}

Nilai maksimum adalah 99 untuk Barcode C dan 999999 untuk Barcode L.

### setVersionID() {#setversionid}

Saat ini "1" – Untuk barcode Mailmark (0 dan 2 hingga 9 serta A sampai Z disiapkan untuk penggunaan di masa depan)
