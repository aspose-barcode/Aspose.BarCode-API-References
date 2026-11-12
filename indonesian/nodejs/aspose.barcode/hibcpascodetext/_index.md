---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC PAS."
type: docs
weight: 480
url: /id/nodejs/aspose.barcode/hibcpascodetext/
---

## HIBCPASCodetext class

Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC PAS.

```js
new HIBCPASCodetext()
```

**Example:**

```js
This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.

 let complexCodetext = new HIBCPASComplexCodetext();
 complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
 complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
 complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
 complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
 let generator = new ComplexBarcodeGenerator(complexCodetext);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(BarCodeImageFormat.PNG), null, DecodeType.HIBC_DATA_MATRIX_PAS);
 reader.readBarCodes();
 let codetext = reader.getFoundBarCodes()[0].getCodeText();
	let readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
 print("Data location: " + readCodetext.getDataLocation());
 print("Data type: " + readCodetext.getRecords()[0].getDataType());
 print("Data: " + readCodetext.getRecords()[0].getData());
 print("Data type: " + readCodetext.getRecords()[1].getDataType());
 print("Data: " + readCodetext.getRecords()[1].getData());
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [_fromMwObject()](#-frommwobject) *(static)* | Konstruktor HIBCPASRecord |
| [addHIBCPASRecord(record)](#addhibcpasrecord) | Menambahkan catatan baru |
| [addRecord(dataType, data)](#addrecord) | Menambahkan catatan baru |
| [clear()](#clear) | Menghapus daftar catatan |
| [equals(obj)](#equals) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai `HIBCPASCodetext` yang ditentukan. |
| [getBarcodeType()](#getbarcodetype) | Mendapatkan tipe barcode. |
| [getConstructedCodetext()](#getconstructedcodetext) | Membuat codetext |
| [getDataLocation()](#getdatalocation) | Mengidentifikasi lokasi data. |
| [getRecords()](#getrecords) | Mendapatkan daftar catatan |
| [hashCode()](#hashcode) | Mengembalikan kode hash untuk instance ini. |
| [initFromString(constructedCodetext)](#initfromstring) | Menginisialisasi instance dari codetext yang dibangun. |
| [setBarcodeType()](#setbarcodetype) | Mendapatkan atau mengatur jenis barcode. Codetext HIBC PAS dapat dienkode menggunakan HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCData |
| [setDataLocation()](#setdatalocation) | Mengidentifikasi lokasi data. |

### _fromMwObject() (static) {#-frommwobject}

Konstruktor HIBCPASRecord

### addHIBCPASRecord(record) {#addhibcpasrecord}

Menambahkan catatan baru

| Parameter | Deskripsi |
| --- | --- |
| catatan | Catatan yang akan ditambahkan |

### addRecord(dataType, data) {#addrecord}

Menambahkan catatan baru

| Parameter | Deskripsi |
| --- | --- |
| dataType | Tipe data |
| data | String data |

### clear() {#clear}

Menghapus daftar catatan

### equals(obj) {#equals}

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai `HIBCPASCodetext` yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| obj | Nilai `HIBCPASCodetext` untuk dibandingkan dengan instance ini. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getBarcodeType() {#getbarcodetype}

Mendapatkan tipe barcode.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Membuat codetext

**Returns:** Constructed codetext

### getDataLocation() {#getdatalocation}

Mengidentifikasi lokasi data.

### getRecords() {#getrecords}

Mendapatkan daftar catatan

**Returns:** List of records

### hashCode() {#hashcode}

Mengembalikan kode hash untuk instance ini.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Menginisialisasi instance dari codetext yang dibangun.

| Parameter | Deskripsi |
| --- | --- |
| constructedCodetext | Codetext yang dibangun. |

### setBarcodeType() {#setbarcodetype}

Mendapatkan atau mengatur jenis barcode. Codetext HIBC PAS dapat dienkode menggunakan tipe enkode HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS, dan HIBCQRPAS. Nilai default: HIBCCode39PAS.

**Returns:** Barcode type.

### setDataLocation() {#setdatalocation}

Mengidentifikasi lokasi data.
