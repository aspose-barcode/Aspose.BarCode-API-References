---
title: "BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Menyimpan data barcode yang dikenali seperti tipe SingleDecodeType, `string` codetext, BarCodeRegionParameters region, dan parameter lainnya"
type: docs
weight: 110
url: /id/nodejs/aspose.barcode/barcoderesult/
---

## BarCodeResult class

Menyimpan data barcode yang dikenali seperti tipe SingleDecodeType, `string` codetext, BarCodeRegionParameters region, dan parameter lainnya

```js
new BarCodeResult()
```

**Example:**

```js
//This sample shows how to obtain BarCodeResult.
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("BarCode Confidence: " + result.getConfidence());
    console.log("BarCode ReadingQuality: " + result.getReadingQuality());
    console.log("BarCode Angle: " + result.getRegion().getAngle());
}
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [deepClone()](#deepclone) | Membuat salinan kelas BarCodeResult. |
| [equals(other)](#equals) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai BarCodeResult yang ditentukan. |
| [getCodeBytes()](#getcodebytes) | Mendapatkan byte kode yang terenkode Nilai: Byte kode barcode |
| [getCodeText(encoding)](#getcodetext) | Mendapatkan teks kode dengan enkoding. Contoh ini menunjukkan cara menggunakan `getCodeText`: let gen = new BarcodeGenerator(EncodeType |
| [getCodeType()](#getcodetype) | Mendapatkan tipe barcode Nilai: Informasi tipe dari barcode yang dikenali |
| [getCodeTypeName()](#getcodetypename) | Mendapatkan nama tipe barcode Nilai: Nama tipe dari barcode yang dikenali |
| [getConfidence()](#getconfidence) | Mendapatkan tingkat kepercayaan pengenalan barcode yang dikenali Nilai: BarCodeConfidence.Strong tidak memiliki palsu atau misre |
| [getExtended()](#getextended) | Mendapatkan parameter tambahan dari barcode yang dikenali Nilai: Parameter tambahan dari barcode yang dikenali |
| [getReadingQuality()](#getreadingquality) | Mendapatkan kualitas pembacaan. Berfungsi untuk barcode 1D dan pos. Nilai: Persentase kualitas pembacaan |
| [getRegion()](#getregion) | Mendapatkan wilayah barcode Nilai: Wilayah barcode yang dikenali |
| [hashCode()](#hashcode) | Mengembalikan kode hash untuk instance ini. |
| [toString()](#tostring) | Mengembalikan representasi string yang dapat dibaca manusia dari BarCodeResult ini. |

### deepClone() {#deepclone}

Membuat salinan kelas BarCodeResult.

**Returns:** Returns copy of BarCodeResult class.

### equals(other) {#equals}

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai BarCodeResult yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| lainnya | Nilai BarCodeResult untuk dibandingkan dengan instance ini. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCodeBytes() {#getcodebytes}

Mendapatkan byte kode yang terenkode Nilai: Byte kode barcode

### getCodeText(encoding) {#getcodetext}

Mendapatkan teks kode dengan enkoding. Contoh ini menunjukkan cara menggunakan `getCodeText`: let gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null); gen.setCodeText("車種名", "932"); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.DATA_MATRIX); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText("932")); }

| Parameter | Deskripsi |
| --- | --- |
| enkoding | Enkoding untuk codetext. |

**Returns:** A string containing recognized code text.

### getCodeType() {#getcodetype}

Mendapatkan tipe barcode Nilai: Informasi tipe dari barcode yang dikenali

### getCodeTypeName() {#getcodetypename}

Mendapatkan nama tipe barcode Nilai: Nama tipe dari barcode yang dikenali

### getConfidence() {#getconfidence}

Mendapatkan tingkat kepercayaan pengenalan barcode yang dikenali Nilai: BarCodeConfidence.Strong tidak memiliki palsu atau kesalahan pengenalan, BarCodeConfidence.Moderate kadang dapat memiliki palsu atau codetext yang tidak tepat karena tingkat kepercayaan ini untuk barcode dengan checksum lemah atau bahkan tanpa checksum, BarCodeConfidence.NONE selalu memiliki codetext yang tidak tepat dan dapat menjadi pengenalan palsu

### getExtended() {#getextended}

Mendapatkan parameter tambahan dari barcode yang dikenali Nilai: Parameter tambahan dari barcode yang dikenali

### getReadingQuality() {#getreadingquality}

Mendapatkan kualitas pembacaan. Berfungsi untuk barcode 1D dan pos. Nilai: Persentase kualitas pembacaan

### getRegion() {#getregion}

Mendapatkan wilayah barcode Nilai: Wilayah barcode yang dikenali

### hashCode() {#hashcode}

Mengembalikan kode hash untuk instance ini.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Mengembalikan representasi string yang dapat dibaca manusia dari BarCodeResult ini.

**Returns:** A string that represents this BarCodeResult.
