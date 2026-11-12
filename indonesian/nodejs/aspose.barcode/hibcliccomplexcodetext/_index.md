---
title: "HIBCLICComplexCodetext"
linktitle: "HIBCLICComplexCodetext"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Kelas dasar untuk enkoding dan dekoding teks yang tertanam dalam kode HIBC LIC."
type: docs
weight: 450
url: /id/nodejs/aspose.barcode/hibcliccomplexcodetext/
---

## HIBCLICComplexCodetext class

Kelas dasar untuk enkoding dan dekoding teks yang tertanam dalam kode HIBC LIC. Contoh ini menunjukkan cara mendekode codetext HIBC LIC mentah menjadi instance HIBCLICComplexCodetext.

```js
new HIBCLICComplexCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.HIBC_AZTEC_LIC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
   let resultHIBCLICComplexCodetext = ComplexCodetextReader.tryDecodeHIBCLIC(result.getCodeText());
   print("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
   print("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Mendapatkan atau mengatur tipe barcode. Codetext HIBC LIC dapat dienkode menggunakan HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM |
| [getConstructedCodetext()](#getconstructedcodetext) | Membuat codetext |
| [initFromString(constructedCodetext)](#initfromstring) | Menginisialisasi instance dari codetext yang dibangun. |
| [setBarcodeType()](#setbarcodetype) | Mendapatkan atau mengatur tipe barcode. Codetext HIBC LIC dapat dienkode menggunakan HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM |

### getBarcodeType() {#getbarcodetype}

Mendapatkan atau mengatur tipe barcode. Codetext HIBC LIC dapat dienkode menggunakan tipe enkode HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC, dan HIBCQRLIC. Nilai default: HIBCCode39LIC.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Membuat codetext

**Returns:** Constructed codetext

### initFromString(constructedCodetext) {#initfromstring}

Menginisialisasi instance dari codetext yang dibangun.

| Parameter | Deskripsi |
| --- | --- |
| constructedCodetext | Codetext yang dibangun. |

### setBarcodeType() {#setbarcodetype}

Mendapatkan atau mengatur tipe barcode. Codetext HIBC LIC dapat dienkode menggunakan tipe enkode HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC, dan HIBCQRLIC. Nilai default: HIBCCode39LIC.

**Returns:** Barcode type.
