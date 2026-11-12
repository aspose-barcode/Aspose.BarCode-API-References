---
title: "BarcodeSettings"
linktitle: "BarcodeSettings"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Parameter decoding BarCode utama."
type: docs
weight: 150
url: /id/nodejs/aspose.barcode/barcodesettings/
---

## BarcodeSettings class

Parameter decoding BarCode utama. Berisi parameter yang memengaruhi data yang dikenali.

```js
new BarcodeSettings(settings)
```

Konstruktor penyalinan BarcodeSettings

| Parameter | Deskripsi |
| --- | --- |
| pengaturan | Sumber data |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getAustraliaPost()](#getaustraliapost) | Mendapatkan parameter decoding AustraliaPost |
| [getChecksumValidation()](#getchecksumvalidation) | Aktifkan validasi checksum selama pengenalan untuk barcode 1D dan Postal. Nilai default dianggap Ya untuk simbol yang |
| [getDetectEncoding()](#getdetectencoding) | Bendera yang memaksa mesin mendeteksi pengkodean codetext untuk set kode Unicode. Nilai default adalah true. |
| [getStripFNC()](#getstripfnc) | Hapus karakter FNC1, FNC2, FNC3 dari codetext. Nilai default adalah false. |
| [isOnlyRequestedTypes()](#isonlyrequestedtypes) | Mengembalikan hanya tipe barcode yang secara eksplisit ditentukan untuk pengenalan. Ketika diaktifkan, barcode yang dikenali dari tipe lain yang kompatibel o |
| [setChecksumValidation(value)](#setchecksumvalidation) | Aktifkan validasi checksum selama pengenalan untuk barcode 1D dan Postal. Nilai default dianggap Ya untuk simbol yang |
| [setDetectEncoding()](#setdetectencoding) | Bendera yang memaksa mesin mendeteksi pengkodean codetext untuk set kode Unicode. Nilai default adalah true. |
| [setOnlyRequestedTypes()](#setonlyrequestedtypes) | Mengembalikan hanya tipe barcode yang secara eksplisit ditentukan untuk pengenalan. Ketika diaktifkan, barcode yang dikenali dari tipe lain yang kompatibel o |
| [setStripFNC(value)](#setstripfnc) | Hapus karakter FNC1, FNC2, FNC3 dari codetext. Nilai default adalah false. |

### getAustraliaPost() {#getaustraliapost}

Mendapatkan parameter decoding AustraliaPost

**Returns:** The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology

### getChecksumValidation() {#getchecksumvalidation}

Aktifkan validasi checksum selama pengenalan untuk barcode 1D dan Postal. Nilai default dianggap Ya untuk simbol yang harus mengandung checksum, dan No untuk yang checksum hanya mungkin. Checksum tidak pernah digunakan: Codabar, PatchCode, Pharmacode, DataLogic2of5. Checksum memungkinkan: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Checksum selalu digunakan: Simbol lainnya.

**Returns:** Enable checksum validation during recognition for 1D and Postal barcodes.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### getDetectEncoding() {#getdetectencoding}

Bendera yang memaksa mesin mendeteksi pengkodean codetext untuk set kode Unicode. Nilai default adalah true.

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### getStripFNC() {#getstripfnc}

Hapus karakter FNC1, FNC2, FNC3 dari codetext. Nilai default adalah false.

**Returns:** Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### isOnlyRequestedTypes() {#isonlyrequestedtypes}

Mengembalikan hanya tipe barcode yang secara eksplisit ditentukan untuk pengenalan. Ketika diaktifkan, barcode yang dikenali dari tipe lain yang kompatibel atau setara akan disaring. Nilai default adalah false. Contoh: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setChecksumValidation(value) {#setchecksumvalidation}

Aktifkan validasi checksum selama pengenalan untuk barcode 1D dan Postal. Nilai default dianggap Ya untuk simbol yang harus mengandung checksum, dan No untuk yang checksum hanya mungkin. Checksum tidak pernah digunakan: Codabar, PatchCode, Pharmacode, DataLogic2of5. Checksum memungkinkan: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Checksum selalu digunakan: Simbol lainnya.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Aktifkan validasi checksum selama pengenalan untuk barcode 1D dan Postal. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### setDetectEncoding() {#setdetectencoding}

Bendera yang memaksa mesin mendeteksi pengkodean codetext untuk set kode Unicode. Nilai default adalah true.

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### setOnlyRequestedTypes() {#setonlyrequestedtypes}

Mengembalikan hanya tipe barcode yang secara eksplisit ditentukan untuk pengenalan. Ketika diaktifkan, barcode yang dikenali dari tipe lain yang kompatibel atau setara akan disaring. Nilai default adalah false. Contoh: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setStripFNC(value) {#setstripfnc}

Hapus karakter FNC1, FNC2, FNC3 dari codetext. Nilai default adalah false.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Hapus karakter FNC1, FNC2, FNC3 dari codetext. Nilai default adalah false. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```
