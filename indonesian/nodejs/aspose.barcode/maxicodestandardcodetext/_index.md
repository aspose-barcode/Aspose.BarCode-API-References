---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Kelas untuk mengenkode dan mendekode teks kode MaxiCode untuk mode 4, 5, dan 6."
type: docs
weight: 670
url: /id/nodejs/aspose.barcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

Kelas untuk mengenkode dan mendekode teks kode MaxiCode untuk mode 4, 5, dan 6.

```js
new MaxiCodeStandardCodetext()
```

**Example:**

```js
//Mode 4
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [equals(obj)](#equals) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai yang ditentukan. |
| [getConstructedCodetext()](#getconstructedcodetext) | Membuat codetext |
| [getHashCode()](#gethashcode) | Mengembalikan kode hash untuk instance ini. |
| [getMessage()](#getmessage) | Mendapatkan pesan. |
| [getMode()](#getmode) | Mendapatkan mode MaxiCode. |
| [initFromString(constructedCodetext)](#initfromstring) | Menginisialisasi instance dari codetext yang dibangun. |
| [setMessage()](#setmessage) | Mengatur pesan. |
| [setMode()](#setmode) | Mengatur mode MaxiCode. Codetext standar hanya dapat digunakan dengan mode 4, 5, dan 6. |

### equals(obj) {#equals}

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| obj | Nilai untuk dibandingkan dengan instance ini. |

**Returns:** if obj has the same value as this instance; otherwise, false .

### getConstructedCodetext() {#getconstructedcodetext}

Membuat codetext

**Returns:** Constructed codetext

### getHashCode() {#gethashcode}

Mengembalikan kode hash untuk instance ini.

**Returns:** A 32-bit signed integer hash code

### getMessage() {#getmessage}

Mendapatkan pesan.

### getMode() {#getmode}

Mendapatkan mode MaxiCode.

**Returns:** MaxiCode mode

### initFromString(constructedCodetext) {#initfromstring}

Menginisialisasi instance dari codetext yang dibangun.

| Parameter | Deskripsi |
| --- | --- |
| constructedCodetext | Codetext yang dibangun. |

### setMessage() {#setmessage}

Mengatur pesan.

### setMode() {#setmode}

Mengatur mode MaxiCode. Codetext standar hanya dapat digunakan dengan mode 4, 5, dan 6.
