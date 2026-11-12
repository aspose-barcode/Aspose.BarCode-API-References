---
title: "QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Menyimpan informasi QR Structured Append dari barcode yang dikenali."
type: docs
weight: 810
url: /id/nodejs/aspose.barcode/qrextendedparameters/
---

## QRExtendedParameters class

Menyimpan informasi QR Structured Append dari barcode yang dikenali.

```js
new QRExtendedParameters()
```

**Example:**

```js
//This sample shows how to get QR Structured Append data

let reader = new BarCodeReader("test.png", null,  DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
   console.log("QR Structured Append Index: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodeIndex());
   console.log("QR Structured Append ParityData: " + result.getExtended().getQR().getQRStructuredAppendModeParityData());
}
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [equals(obj)](#equals) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai QRExtendedParameters yang ditentukan. |
| [getErrorLevel()](#geterrorlevel) | Level koreksi kesalahan Reed-Solomon dari barcode yang dikenali. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH. |
| [getMicroQRVersion()](#getmicroqrversion) | Versi MicroQR Code yang dikenali. Dari M1 hingga M4. |
| [getQRErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Level koreksi kesalahan Reed-Solomon dari barcode yang dikenali. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH. |
| [getQRStructuredAppendModeBarCodeIndex()](#getqrstructuredappendmodebarcodeindex) ~~(deprecated)~~ | Mendapatkan indeks barcode mode penambahan terstruktur QR. Indeks dimulai dari 0. Nilai default adalah -1. Nilai: Jumlah dari |
| [getQRStructuredAppendModeBarCodesQuantity()](#getqrstructuredappendmodebarcodesquantity) ~~(deprecated)~~ | Mendapatkan jumlah barcode mode penambahan terstruktur QR. Nilai default adalah -1. Nilai: Jumlah dari QR structured appen |
| [getQRStructuredAppendModeParityData()](#getqrstructuredappendmodeparitydata) ~~(deprecated)~~ | Mendapatkan data parity mode penambahan terstruktur QR. Nilai default adalah -1. Nilai: Indeks dari QR structured append mode ba |
| [getQRVersion()](#getqrversion) ~~(deprecated)~~ | Versi QR Code yang dikenali. Dari Version1 hingga Version40. |
| [getRectMicroQRVersion()](#getrectmicroqrversion) | Versi RectMicroQR Code yang dikenali. Dari R7x43 hingga R17x139. |
| [getStructuredAppendModeBarCodeIndex()](#getstructuredappendmodebarcodeindex) | Mendapatkan indeks barcode mode penambahan terstruktur QR. Indeks dimulai dari 0. Nilai default adalah -1. Nilai: Jumlah o |
| [getStructuredAppendModeBarCodesQuantity()](#getstructuredappendmodebarcodesquantity) | Mendapatkan jumlah barcode mode penambahan terstruktur QR. Nilai default adalah -1. Nilai: Jumlah dari QR structured appe |
| [getStructuredAppendModeParityData()](#getstructuredappendmodeparitydata) | Mendapatkan data parity mode penambahan terstruktur QR. Nilai default adalah -1. Nilai: Indeks dari QR structured append mode b |
| [getVersion()](#getversion) | Versi QR Code yang dikenali. Dari Version1 hingga Version40. |
| [hashCode()](#hashcode) | Mengembalikan kode hash untuk instance ini. |
| [isEmpty()](#isempty) | Menguji apakah semua parameter hanya memiliki nilai default Nilai |
| [toString()](#tostring) | Mengembalikan representasi string yang dapat dibaca manusia dari QRExtendedParameters. |

### equals(obj) {#equals}

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai QRExtendedParameters yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| obj | Nilai objek untuk dibandingkan dengan instance ini. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getErrorLevel() {#geterrorlevel}

Level koreksi kesalahan Reed-Solomon dari barcode yang dikenali. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH.

### getMicroQRVersion() {#getmicroqrversion}

Versi MicroQR Code yang dikenali. Dari M1 hingga M4.

**Returns:** Version of recognized MicroQR Code. From M1 to M4.

### getQRErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Level koreksi kesalahan Reed-Solomon dari barcode yang dikenali. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH.

**Returns:** Reed-Solomon error correction level of recognized barcode.

### getQRStructuredAppendModeBarCodeIndex() {#getqrstructuredappendmodebarcodeindex}

> **Deprecated.** See method description for replacement.

Mendapatkan indeks barcode mode penambahan terstruktur QR. Indeks dimulai dari 0. Nilai default adalah -1.Nilai: Jumlah barcode mode penambahan terstruktur QR.

### getQRStructuredAppendModeBarCodesQuantity() {#getqrstructuredappendmodebarcodesquantity}

> **Deprecated.** See method description for replacement.

Mendapatkan jumlah barcode mode penambahan terstruktur QR. Nilai default adalah -1.Nilai: Jumlah barcode mode penambahan terstruktur QR.

### getQRStructuredAppendModeParityData() {#getqrstructuredappendmodeparitydata}

> **Deprecated.** See method description for replacement.

Mendapatkan data paritas mode penambahan terstruktur QR. Nilai default adalah -1.Nilai: Indeks barcode mode penambahan terstruktur QR.

### getQRVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Versi QR Code yang dikenali. Dari Version1 hingga Version40.

**Returns:** Version of recognized QR Code

### getRectMicroQRVersion() {#getrectmicroqrversion}

Versi RectMicroQR Code yang dikenali. Dari R7x43 hingga R17x139.

**Returns:** Version of recognized RectMicroQR Code

### getStructuredAppendModeBarCodeIndex() {#getstructuredappendmodebarcodeindex}

Mendapatkan indeks barcode mode penambahan terstruktur QR. Indeks dimulai dari 0. Nilai default adalah -1. Nilai: Jumlah barcode mode penambahan terstruktur QR.

**Returns:** the index of the QR structured append mode barcode.

### getStructuredAppendModeBarCodesQuantity() {#getstructuredappendmodebarcodesquantity}

Mendapatkan jumlah barcode mode penambahan terstruktur QR. Nilai default adalah -1. Nilai: Jumlah barcode mode penambahan terstruktur QR.

**Returns:** the QR structured append mode barcodes quantity.

### getStructuredAppendModeParityData() {#getstructuredappendmodeparitydata}

Mendapatkan data paritas mode penambahan terstruktur QR. Nilai default adalah -1. Nilai: Indeks barcode mode penambahan terstruktur QR.

**Returns:** the QR structured append mode parity data.

### getVersion() {#getversion}

Versi QR Code yang dikenali. Dari Version1 hingga Version40.

### hashCode() {#hashcode}

Mengembalikan kode hash untuk instance ini.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Menguji apakah semua parameter hanya memiliki nilai default Nilai

**Returns:** true if all parameters has only default values; otherwise, `false `.

### toString() {#tostring}

Mengembalikan representasi string yang dapat dibaca manusia dari QRExtendedParameters.

**Returns:** A string that represents this QRExtendedParameters.
