---
title: "DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Menyimpan data khusus dari kode batang DataMatrix yang dikenali Contoh ini menunjukkan cara mendapatkan nilai mentah DataMatrix let generator = new BarcodeGenerator(EncodeTypes.DATA_MA"
type: docs
weight: 350
url: /id/nodejs/aspose.barcode/datamatrixextendedparameters/
---

## DataMatrixExtendedParameters class

Menyimpan data khusus dari kode batang DataMatrix yang dikenali Contoh ini menunjukkan cara mendapatkan nilai mentah DataMatrix let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345")) generator.save("test.png", BarcodeImageFormat.PNG); let reader = new BarCodeReader("test.png", null, DecodeType.DATA_MATRIX)) let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode type: " + result.getCodeTypeName()); console.log("BarCode codetext: " + result.getCodeText()); console.log("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId()); console.log("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount()); console.log("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId()); console.log("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming()); }

```js
new DataMatrixExtendedParameters()
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [equals(obj)](#equals) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai `DataMatrixExtendedParameters` yang ditentukan. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Mendapatkan ID barcode mode structured append DataMatrix. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode cou |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Mendapatkan jumlah barcode mode structured append DataMatrix. Nilai default adalah -1. Jumlah harus berupa nilai antara 1 hingga 35. Valu |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Mendapatkan ID barcode mode structured append DataMatrix. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode cou |
| [hashCode()](#hashcode) | Mengembalikan kode hash untuk instance ini. |
| [isReaderProgramming()](#isreaderprogramming) | Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau |
| [toString()](#tostring) | Mengembalikan representasi string yang dapat dibaca manusia dari `DataMatrixExtendedParameters` ini. |

### equals(obj) {#equals}

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai `DataMatrixExtendedParameters` yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| obj | Sebuah nilai System.Object untuk dibandingkan dengan instance ini. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Mendapatkan ID barcode mode structured append DataMatrix. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. Nilai default adalah -1. Nilai: ID barcode mode structured append DataMatrix.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Mendapatkan jumlah barcode mode penambahan terstruktur DataMatrix. Nilai default adalah -1. Jumlah harus berupa nilai antara 1 hingga 35. Nilai: Jumlah barcode mode penambahan terstruktur DataMatrix.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Mendapatkan ID barcode mode structured append DataMatrix. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. Nilai default adalah -1. Nilai: ID barcode mode structured append DataMatrix.

### hashCode() {#hashcode}

Mengembalikan kode hash untuk instance ini.

**Returns:** A 32-bit signed integer hash code.

### isReaderProgramming() {#isreaderprogramming}

Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca kode batang. Nilai default adalah false.

### toString() {#tostring}

Mengembalikan representasi string yang dapat dibaca manusia dari `DataMatrixExtendedParameters` ini.

**Returns:** A string that represents this `DataMatrixExtendedParameters`.
