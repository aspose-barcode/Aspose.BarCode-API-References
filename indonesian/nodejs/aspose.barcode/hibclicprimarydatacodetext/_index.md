---
title: "HIBCLICPrimaryDataCodetext"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Kelas untuk mengenkode dan mendekode teks yang disematkan dalam kode HIBC LIC yang menyimpan data utama."
type: docs
weight: 460
url: /id/nodejs/aspose.barcode/hibclicprimarydatacodetext/
---

## HIBCLICPrimaryDataCodetext class

Kelas untuk mengenkode dan mendekode teks yang disematkan dalam kode HIBC LIC yang menyimpan data utama. Contoh ini menunjukkan cara mengenkode dan mendekode HIBC LIC menggunakan HIBCLICPrimaryCodetext.

```js
new HIBCLICPrimaryDataCodetext()
```

**Example:**

```js
let complexCodetext  = new HIBCLICPrimaryCodetext();
complexCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
complexCodetext.setData(new PrimaryData());
complexCodetext.getData().setProductOrCatalogNumber("12345");
complexCodetext.getData().setLabelerIdentificationCode("A999");
complexCodetext.getData().setUnitOfMeasureID(1);
let generator = new ComplexBarcodeGenerator(complexCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getData().getUnitOfMeasureID());
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [equals(obj)](#equals) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai `HIBCLICPrimaryDataCodetext` yang ditentukan. |
| [getConstructedCodetext()](#getconstructedcodetext) | Membuat codetext |
| [getData()](#getdata) | Mengidentifikasi data utama. |
| [hashCode()](#hashcode) | Mengembalikan kode hash untuk instance ini. |
| [initFromString(constructedCodetext)](#initfromstring) | Menginisialisasi instance dari codetext yang dibangun. |
| [setData()](#setdata) | Mengidentifikasi data utama. |

### equals(obj) {#equals}

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai `HIBCLICPrimaryDataCodetext` yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| obj | Nilai `HIBCLICPrimaryDataCodetext` untuk dibandingkan dengan instance ini. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Membuat codetext

**Returns:** Constructed codetext

### getData() {#getdata}

Mengidentifikasi data utama.

### hashCode() {#hashcode}

Mengembalikan kode hash untuk instance ini.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Menginisialisasi instance dari codetext yang dibangun.

| Parameter | Deskripsi |
| --- | --- |
| constructedCodetext | Codetext yang dibangun. |

### setData() {#setdata}

Mengidentifikasi data utama.
