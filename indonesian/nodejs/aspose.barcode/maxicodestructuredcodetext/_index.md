---
title: "MaxiCodeStructuredCodetext"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Kelas dasar untuk mengenkode dan mendekode teks yang tertanam dalam kode MaxiCode untuk mode 2 dan 3."
type: docs
weight: 700
url: /id/nodejs/aspose.barcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

Kelas dasar untuk mengenkode dan mendekode teks yang tertanam dalam kode MaxiCode untuk mode 2 dan 3.

```js
new MaxiCodeStructuredCodetext()
```

**Example:**

```js
This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance.

 let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
 let results = reader.readBarCodes();
 for(let i = 0; i < results.length; i++)
 {
    let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
     {
         let maxiCodeStructuredCodetext = resultMaxiCodeCodetext;
         console.log("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
         console.log("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
         console.log("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
     }
 }
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [equals(obj)](#equals) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai yang ditentukan. |
| [getConstructedCodetext()](#getconstructedcodetext) | Membuat codetext |
| [getCountryCode()](#getcountrycode) | Mengidentifikasi kode negara 3 digit. |
| [getHashCode()](#gethashcode) | Mengembalikan kode hash untuk instance ini. |
| [getPostalCode()](#getpostalcode) | Mengidentifikasi kode pos. Harus 9 digit dalam mode 2 atau 6 simbol alfanumerik dalam mode 3. |
| [getSecondMessage()](#getsecondmessage) | Mengidentifikasi pesan kedua dari barcode. |
| [getServiceCategory()](#getservicecategory) | Mengidentifikasi kategori layanan 3 digit. |
| [initFromString(constructedCodetext)](#initfromstring) | Menginisialisasi instance dari codetext yang dibangun. |
| [setCountryCode()](#setcountrycode) | Mengidentifikasi kode negara 3 digit. |
| [setPostalCode()](#setpostalcode) | Mengidentifikasi kode pos. Harus 9 digit dalam mode 2 atau 6 simbol alfanumerik dalam mode 3. |
| [setSecondMessage()](#setsecondmessage) | Mengidentifikasi pesan kedua dari barcode. |
| [setServiceCategory()](#setservicecategory) | Mengidentifikasi kategori layanan 3 digit. |

### equals(obj) {#equals}

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| obj | Sebuah nilai untuk dibandingkan dengan instance ini |

**Returns:** true if obj has the same value as this instance; otherwise, false

### getConstructedCodetext() {#getconstructedcodetext}

Membuat codetext

**Returns:** Constructed codetext

### getCountryCode() {#getcountrycode}

Mengidentifikasi kode negara 3 digit.

### getHashCode() {#gethashcode}

Mengembalikan kode hash untuk instance ini.

**Returns:** A 32-bit signed integer hash code.

### getPostalCode() {#getpostalcode}

Mengidentifikasi kode pos. Harus 9 digit dalam mode 2 atau 6 simbol alfanumerik dalam mode 3.

### getSecondMessage() {#getsecondmessage}

Mengidentifikasi pesan kedua dari barcode.

### getServiceCategory() {#getservicecategory}

Mengidentifikasi kategori layanan 3 digit.

### initFromString(constructedCodetext) {#initfromstring}

Menginisialisasi instance dari codetext yang dibangun.

| Parameter | Deskripsi |
| --- | --- |
| constructedCodetext | Codetext yang dibangun. |

### setCountryCode() {#setcountrycode}

Mengidentifikasi kode negara 3 digit.

### setPostalCode() {#setpostalcode}

Mengidentifikasi kode pos. Harus 9 digit dalam mode 2 atau 6 simbol alfanumerik dalam mode 3.

### setSecondMessage() {#setsecondmessage}

Mengidentifikasi pesan kedua dari barcode.

### setServiceCategory() {#setservicecategory}

Mengidentifikasi kategori layanan 3 digit.
