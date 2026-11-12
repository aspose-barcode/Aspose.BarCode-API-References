---
title: "HIBCLICCombinedCodetext"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC LIC yang menyimpan data utama dan sekunder."
type: docs
weight: 440
url: /id/nodejs/aspose.barcode/hibcliccombinedcodetext/
---

## HIBCLICCombinedCodetext class

Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC LIC yang menyimpan data utama dan sekunder. Contoh ini menunjukkan cara mengkodekan dan mendekode HIBC LIC menggunakan HIBCLICCombinedCodetext.

```js
new HIBCLICCombinedCodetext()
```

**Example:**

```js
let combinedCodetext = new HIBCLICCombinedCodetext();
combinedCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
combinedCodetext.setPrimaryData(new PrimaryData());
combinedCodetext.getPrimaryData().setProductOrCatalogNumber("12345");
combinedCodetext.getPrimaryData().setLabelerIdentificationCode("A999");
combinedCodetext.getPrimaryData().setUnitOfMeasureID(1);
combinedCodetext.setSecondaryAndAdditionalData(new SecondaryAndAdditionalData());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDate(new Date());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDateFormat(HIBCLICDateFormat.MMDDYY);
combinedCodetext.getSecondaryAndAdditionalData().setQuantity(30);
combinedCodetext.getSecondaryAndAdditionalData().setLotNumber("LOT123");
combinedCodetext.getSecondaryAndAdditionalData().setSerialNumber("SERIAL123");
combinedCodetext.getSecondaryAndAdditionalData().setDateOfManufacture(new Date());
ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getPrimaryData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getPrimaryData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getPrimaryData().getUnitOfMeasureID());
print("Expiry date: " + result.getSecondaryAndAdditionalData().getExpiryDate());
print("Quantity: " + result.getSecondaryAndAdditionalData().getQuantity());
print("Lot number: " + result.getSecondaryAndAdditionalData().getLotNumber());
print("Serial number: " + result.getSecondaryAndAdditionalData().getSerialNumber());
print("Date of manufacture: " + result.getSecondaryAndAdditionalData().getDateOfManufacture());
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [equals(obj)](#equals) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai `HIBCLICCombinedCodetext` yang ditentukan. |
| [getConstructedCodetext()](#getconstructedcodetext) | Membuat codetext |
| [getPrimaryData()](#getprimarydata) | Mengidentifikasi data utama. |
| [getSecondaryAndAdditionalData()](#getsecondaryandadditionaldata) | Mengidentifikasi data sekunder dan data tambahan suplemental. |
| [hashCode()](#hashcode) | Mengembalikan kode hash untuk instance ini. |
| [initFromString(constructedCodetext)](#initfromstring) | Menginisialisasi instance dari codetext yang dibangun. |
| [setPrimaryData()](#setprimarydata) | Mengidentifikasi data utama. |
| [setSecondaryAndAdditionalData()](#setsecondaryandadditionaldata) | Mengidentifikasi data sekunder dan data tambahan suplemental. |

### equals(obj) {#equals}

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai `HIBCLICCombinedCodetext` yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| obj | Nilai `HIBCLICCombinedCodetext` untuk dibandingkan dengan instance ini. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Membuat codetext

**Returns:** Constructed codetext

### getPrimaryData() {#getprimarydata}

Mengidentifikasi data utama.

### getSecondaryAndAdditionalData() {#getsecondaryandadditionaldata}

Mengidentifikasi data sekunder dan data tambahan suplemental.

### hashCode() {#hashcode}

Mengembalikan kode hash untuk instance ini.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Menginisialisasi instance dari codetext yang dibangun.

| Parameter | Deskripsi |
| --- | --- |
| constructedCodetext | Codetext yang dibangun. |

### setPrimaryData() {#setprimarydata}

Mengidentifikasi data utama.

### setSecondaryAndAdditionalData() {#setsecondaryandadditionaldata}

Mengidentifikasi data sekunder dan data tambahan suplemental.
