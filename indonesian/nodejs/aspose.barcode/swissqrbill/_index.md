---
title: "SwissQRBill"
linktitle: "SwissQRBill"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Data tagihan SwissQR"
type: docs
weight: 920
url: /id/nodejs/aspose.barcode/swissqrbill/
---

## SwissQRBill class

Data tagihan SwissQR

```js
new SwissQRBill()
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [createAndSetCreditorReference(rawReference)](#createandsetcreditorreference) | Membuat dan mengatur referensi kreditur ISO11649 dari string mentah dengan menambahkan awalan "RF" pada String dan modulo 97 che |
| [equals(obj)](#equals) | Menentukan apakah objek yang ditentukan sama dengan objek saat ini. |
| [getAccount()](#getaccount) | Mendapatkan nomor rekening kreditur. Nomor rekening harus berupa IBAN yang valid dari bank di Swiss atau Liechtenstein. Space |
| [getAlternativeSchemes()](#getalternativeschemes) | Mendapatkan atau mengatur skema pembayaran alternatif. Maksimum dua skema dengan parameter diizinkan. |
| [getAmount()](#getamount) | Mendapatkan jumlah pembayaran. Nilai yang valid antara 0.01 dan 999,999,999.99. |
| [getBillInformation()](#getbillinformation) | Mendapatkan informasi tagihan terstruktur tambahan. |
| [getCreditor()](#getcreditor) | Mendapatkan alamat kreditur. |
| [getCurrency()](#getcurrency) | Mendapatkan mata uang pembayaran. Nilai yang valid adalah "CHF" dan "EUR". |
| [getDebtor()](#getdebtor) | Mendapatkan alamat debitur. Debitur bersifat opsional. Jika diabaikan, baik mengatur bidang ini menjadi null atau mengatur sebuah alamat |
| [getReference()](#getreference) | Mendapatkan referensi pembayaran kreditur. Referensi wajib untuk IBAN SwissQR, yaitu IBAN dalam rentang CHxx30000xxxxx |
| [getUnstructuredMessage()](#getunstructuredmessage) | Mendapatkan pesan tidak terstruktur tambahan. |
| [getVersion()](#getversion) | Mendapatkan versi standar tagihan SwissQR. |
| [hashCode()](#hashcode) | Mendapatkan kode hash untuk instance ini. |
| [setAccount(value:)](#setaccount) | Mengatur nomor akun kreditur. Nomor akun harus berupa IBAN yang valid dari bank di Swiss atau Liechtenstein. Spasi |
| [setAlternativeSchemes(value:)](#setalternativeschemes) | Mendapatkan atau mengatur skema pembayaran alternatif. Maksimum dua skema dengan parameter diizinkan. |
| [setAmount(value)](#setamount) | Mengatur jumlah pembayaran. Nilai yang valid antara 0.01 dan 999,999,999.99. |
| [setBillInformation(value:)](#setbillinformation) | Mengatur informasi tagihan terstruktur tambahan. |
| [setCreditor(value:)](#setcreditor) | Mengatur alamat kreditur. |
| [setCurrency(value)](#setcurrency) | Mengatur mata uang pembayaran. |
| [setDebtor(value:)](#setdebtor) | Mengatur alamat debitur. Debitur bersifat opsional. Jika diabaikan, baik mengatur bidang ini menjadi null atau mengatur sebuah alamat |
| [setReference(value)](#setreference) | Mengatur referensi pembayaran kreditur. Referensi wajib untuk IBAN SwissQR, yaitu IBAN dalam rentang CHxx30000xxxxx |
| [setUnstructuredMessage(value:)](#setunstructuredmessage) | Mengatur pesan tidak terstruktur tambahan. |
| [setVersion(value)](#setversion) | Mengatur versi standar tagihan SwissQR. |

### createAndSetCreditorReference(rawReference) {#createandsetcreditorreference}

Membuat dan mengatur referensi kreditur ISO11649 dari string mentah dengan menambahkan awalan "RF" dan checksum modulo 97. Spasi dihapus dari referensi

| Parameter | Deskripsi |
| --- | --- |
| rawReference | Referensi mentah. |

**Throws:** ArgumentException rawReference contains invalid characters.

### equals(obj) {#equals}

Menentukan apakah objek yang ditentukan sama dengan objek saat ini.

| Parameter | Deskripsi |
| --- | --- |
| obj | Objek yang dibandingkan dengan objek saat ini. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAccount() {#getaccount}

Mendapatkan nomor akun kreditur. Nomor akun harus berupa IBAN yang valid dari bank di Swiss atau Liechtenstein. Spasi diizinkan dalam nomor akun.

**Returns:** The creditor account number.

### getAlternativeSchemes() {#getalternativeschemes}

Mendapatkan atau mengatur skema pembayaran alternatif. Maksimum dua skema dengan parameter diizinkan.

**Returns:** The alternative payment schemes.

### getAmount() {#getamount}

Mendapatkan jumlah pembayaran. Nilai yang valid antara 0.01 dan 999,999,999.99.

**Returns:** The payment amount.

### getBillInformation() {#getbillinformation}

Mendapatkan informasi tagihan terstruktur tambahan.

**Returns:** The structured bill information.

### getCreditor() {#getcreditor}

Mendapatkan alamat kreditur.

**Returns:** The creditor address.

### getCurrency() {#getcurrency}

Mendapatkan mata uang pembayaran. Nilai yang valid adalah "CHF" dan "EUR".

**Returns:** The payment currency.

### getDebtor() {#getdebtor}

Mendapatkan alamat debitur. Debitur bersifat opsional. Jika diabaikan, baik mengatur bidang ini menjadi null atau mengatur sebuah alamat dengan semua nilai null atau kosong dianggap ok.

**Returns:** The debtor address.

### getReference() {#getreference}

Mendapatkan referensi pembayaran kreditur. Referensi wajib untuk IBAN SwissQR, yaitu IBAN dalam rentang CHxx30000xxxxxx hingga CHxx31999xxxxx. Jika ditentukan, referensi harus berupa referensi SwissQR yang valid (sesuai format referensi ISR) atau referensi kreditur yang valid menurut ISO 11649 ("RFxxxx"). Kedua dapat berisi spasi untuk pemformatan.

**Returns:** The creditor payment reference.

### getUnstructuredMessage() {#getunstructuredmessage}

Mendapatkan pesan tidak terstruktur tambahan.

**Returns:** The unstructured message.

### getVersion() {#getversion}

Mendapatkan versi standar tagihan SwissQR.

**Returns:** The SwissQR bill standard version.

### hashCode() {#hashcode}

Mendapatkan kode hash untuk instance ini.

**Returns:** A hash code for the current object.

### setAccount(value:) {#setaccount}

Mengatur nomor akun kreditur. Nomor akun harus berupa IBAN yang valid dari bank di Swiss atau Liechtenstein. Spasi diizinkan dalam nomor akun.

| Parameter | Deskripsi |
| --- | --- |
| nilai: | Nomor akun kreditur. |

### setAlternativeSchemes(value:) {#setalternativeschemes}

Mendapatkan atau mengatur skema pembayaran alternatif. Maksimum dua skema dengan parameter diizinkan.

| Parameter | Deskripsi |
| --- | --- |
| nilai: | Skema pembayaran alternatif. |

### setAmount(value) {#setamount}

Mengatur jumlah pembayaran. Nilai yang valid antara 0.01 dan 999,999,999.99.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Jumlah pembayaran. |

### setBillInformation(value:) {#setbillinformation}

Mengatur informasi tagihan terstruktur tambahan.

| Parameter | Deskripsi |
| --- | --- |
| nilai: | Informasi tagihan terstruktur. |

### setCreditor(value:) {#setcreditor}

Mengatur alamat kreditur.

| Parameter | Deskripsi |
| --- | --- |
| nilai: | Alamat kreditur. |

### setCurrency(value) {#setcurrency}

Mengatur mata uang pembayaran.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Nilai yang valid adalah "CHF" dan "EUR". |

### setDebtor(value:) {#setdebtor}

Mengatur alamat debitur. Debitur bersifat opsional. Jika diabaikan, baik mengatur bidang ini menjadi null atau mengatur alamat dengan semua nilai null atau kosong juga diperbolehkan.

| Parameter | Deskripsi |
| --- | --- |
| nilai: | Alamat debitur. |

### setReference(value) {#setreference}

Mengatur referensi pembayaran kreditur. Referensi wajib untuk IBAN SwissQR, yaitu IBAN dalam rentang CHxx30000xxxxxx hingga CHxx31999xxxxx. Jika ditentukan, referensi harus berupa referensi SwissQR yang valid (sesuai format referensi ISR) atau referensi kreditur yang valid menurut ISO 11649 ("RFxxxx"). Kedua-duanya dapat berisi spasi untuk pemformatan.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Referensi pembayaran kreditur. |

### setUnstructuredMessage(value:) {#setunstructuredmessage}

Mengatur pesan tidak terstruktur tambahan.

| Parameter | Deskripsi |
| --- | --- |
| nilai: | Pesan tidak terstruktur. |

### setVersion(value) {#setversion}

Mengatur versi standar tagihan SwissQR.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Versi standar tagihan SwissQR. |
