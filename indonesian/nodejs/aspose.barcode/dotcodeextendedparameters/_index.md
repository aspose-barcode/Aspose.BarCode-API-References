---
title: "DotCodeExtendedParameters"
linktitle: "DotCodeExtendedParameters"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Menyimpan data khusus dari barcode DotCode yang dikenali Contoh ini menunjukkan cara mendapatkan nilai mentah DotCode"
type: docs
weight: 380
url: /id/nodejs/aspose.barcode/dotcodeextendedparameters/
---

## DotCodeExtendedParameters class

Menyimpan data khusus dari barcode DotCode yang dikenali Contoh ini menunjukkan cara mendapatkan nilai mentah DotCode

```js
new DotCodeExtendedParameters()
```

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
generator.save("test.png", BarCodeImageFormat.PNG);

let reader = new BarCodeReader("test.png", null, DecodeType.DOT_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    print("BarCode type: " + result.getCodeTypeName());
    print("BarCode codetext: " + result.getCodeText());
    print("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
    print("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
}
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [equals(obj)](#equals) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai `DotCodeExtendedParameters` yang ditentukan. |
| [getDotCodeIsReaderInitialization()](#getdotcodeisreaderinitialization) ~~(deprecated)~~ | Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | Mendapatkan ID barcode mode penambahan terstruktur DotCode. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | Mendapatkan jumlah barcode mode penambahan terstruktur DotCode. Nilai default adalah -1. Jumlah harus berupa nilai dari 1 hingga 35. Nilai: |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Mendapatkan ID barcode mode penambahan terstruktur DotCode. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | Mendapatkan jumlah barcode mode penambahan terstruktur DotCode. Nilai default adalah -1. Jumlah harus berupa nilai dari 1 hingga 35. Nilai: |
| [hashCode()](#hashcode) | Mengembalikan kode hash untuk instance ini. |
| [isReaderInitialization()](#isreaderinitialization) | Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau |
| [toString()](#tostring) | Mengembalikan representasi string yang dapat dibaca manusia dari `DotCodeExtendedParameters` ini. |

### equals(obj) {#equals}

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai `DotCodeExtendedParameters` yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| obj | Sebuah nilai System.Object untuk dibandingkan dengan instance ini. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDotCodeIsReaderInitialization() {#getdotcodeisreaderinitialization}

> **Deprecated.** See method description for replacement.

Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca kode batang. Nilai default adalah false.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

Mendapatkan ID barcode mode penambahan terstruktur DotCode. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. Nilai default adalah -1. Nilai: ID dari barcode mode penambahan terstruktur DotCode.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

Mendapatkan jumlah barcode mode penambahan terstruktur DotCode. Nilai default adalah -1. Jumlah harus berupa nilai dari 1 hingga 35. Nilai: Jumlah barcode mode penambahan terstruktur DotCode.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Mendapatkan ID barcode mode penambahan terstruktur DotCode. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. Nilai default adalah -1. Nilai: ID dari barcode mode penambahan terstruktur DotCode.

**Returns:** the ID of the DotCode structured append mode barcode.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

Mendapatkan jumlah barcode mode penambahan terstruktur DotCode. Nilai default adalah -1. Jumlah harus berupa nilai dari 1 hingga 35. Nilai: Jumlah barcode mode penambahan terstruktur DotCode.

**Returns:** the DotCode structured append mode barcodes count.

### hashCode() {#hashcode}

Mengembalikan kode hash untuk instance ini.

**Returns:** A 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca kode batang. Nilai default adalah false.

### toString() {#tostring}

Mengembalikan representasi string yang dapat dibaca manusia dari `DotCodeExtendedParameters` ini.

**Returns:** A string that represents this `DotCodeExtendedParameters`.
