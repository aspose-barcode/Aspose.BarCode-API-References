---
title: "AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Menyimpan data khusus dari kode batang Aztec yang dikenali. Contoh ini menunjukkan cara mendapatkan nilai mentah Aztec let generator = new BarcodeGenerator(EncodeTypes.AZTEC, \"12345\"); "
type: docs
weight: 60
url: /id/nodejs/aspose.barcode/aztecextendedparameters/
---

## AztecExtendedParameters class

Menyimpan data khusus dari kode batang Aztec yang dikenali. Contoh ini menunjukkan cara mendapatkan nilai mentah Aztec let generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345"); generator.save("test.png", BarcodeImageFormat.PNG);

```js
new AztecExtendedParameters()
```

**Example:**

```js
BarCodeReader reader = new BarCodeReader("test.png", null, DecodeType.AZTEC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode type: " + result.getCodeTypeName());
    console.log("BarCode codetext: " + result.getCodeText());
    console.log("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
    console.log("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
    console.log("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
    console.log("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
}
</pre>
</pre></blockquote></hr></p>
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [equals(obj)](#equals) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai `AztecExtendedParameters` yang ditentukan. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Mendapatkan ID barcode mode penambahan terstruktur Aztec. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. D |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Mendapatkan jumlah barcode mode penambahan terstruktur Aztec. Nilai default adalah 0. Jumlah harus berupa nilai antara 1 hingga 26. Nilai: The |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Mendapatkan File ID dari mode penambahan terstruktur Aztec. Nilai default adalah string kosong Nilai: File ID dari mode penambahan terstruktur Aztec |
| [hashCode()](#hashcode) | Mengembalikan kode hash untuk instance ini. |
| [isReaderInitialization()](#isreaderinitialization) | Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau |
| [toString()](#tostring) | Mengembalikan representasi string yang dapat dibaca manusia dari `AztecExtendedParameters` ini. |

### equals(obj) {#equals}

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai `AztecExtendedParameters` yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| obj | Sebuah nilai System.Object untuk dibandingkan dengan instance ini. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Mendapatkan ID barcode mode penambahan terstruktur Aztec. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. Nilai default adalah 0. Nilai: ID barcode dari mode penambahan terstruktur Aztec.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Mendapatkan jumlah barcode mode penambahan terstruktur Aztec. Nilai default adalah 0. Jumlah harus berupa nilai antara 1 hingga 26. Nilai: Jumlah barcode dari mode penambahan terstruktur Aztec.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Mendapatkan File ID dari mode penambahan terstruktur Aztec. Nilai default adalah string kosong Nilai: File ID dari mode penambahan terstruktur Aztec.

### hashCode() {#hashcode}

Mengembalikan kode hash untuk instance ini.

**Returns:** 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca kode batang. Nilai default adalah false.

### toString() {#tostring}

Mengembalikan representasi string yang dapat dibaca manusia dari `AztecExtendedParameters` ini.

**Returns:** A string that represents this `AztecExtendedParameters`.
