---
title: "QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Generator kode teks ekstended untuk barcode QR 2D untuk Mode ExtendedCodetext dari QREncodeMode Gunakan properti Display2DText dari BarCodeBuilder untuk mengatur teks yang terlihat menjadi rem"
type: docs
weight: 820
url: /id/nodejs/aspose.barcode/qrextcodetextbuilder/
---

## QrExtCodetextBuilder class

Generator kode teks ekstended untuk barcode QR 2D untuk Mode ExtendedCodetext dari QREncodeMode Gunakan properti Display2DText dari BarCodeBuilder untuk mengatur teks yang terlihat menjadi menghapus karakter pengelolaan.

```js
new QrExtCodetextBuilder()
```

**Example:**

```js
//Example how to generate FNC1 first position for Extended Mode
 //create codetext
 const lTextBuilder = new QrExtCodetextBuilder();
 lTextBuilder.addFNC1FirstPosition();
 lTextBuilder.addPlainCodetext("000%89%%0");
 lTextBuilder.addFNC1GroupSeparator();
 lTextBuilder.addPlainCodetext("12345&lt;FNC1&gt;");
 //generate codetext
 const lCodetext = lTextBuilder.getExtendedCodetext();
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addCodetextWithCompactionMode(mode, codetext)](#addcodetextwithcompactionmode) | Menambahkan kode teks dengan mode kompaksi QR yang ditentukan ke item kode teks ekstended. |
| [addFNC1FirstPosition()](#addfnc1firstposition) | Menambahkan FNC1 pada posisi pertama ke item kode teks ekstended |
| [addFNC1GroupSeparator()](#addfnc1groupseparator) | Menambahkan Group Separator (GS - '\\u001D') ke item kode teks ekstended |
| [addFNC1SecondPosition(codetext)](#addfnc1secondposition) | Menambahkan FNC1 pada posisi kedua ke item kode teks ekstended |
| [clear()](#clear) | Menghapus item kode teks yang diperluas |
| [getExtendedCodetext()](#getextendedcodetext) | Menghasilkan kode teks ekstended dari daftar kode teks ekstended. |

### addCodetextWithCompactionMode(mode, codetext) {#addcodetextwithcompactionmode}

Menambahkan kode teks dengan mode kompaksi QR yang ditentukan ke item kode teks ekstended.

| Parameter | Deskripsi |
| --- | --- |
| mode | Mode kompaksi QR untuk kode teks. |
| codetext | Kode teks dalam Unicode untuk ditambahkan sebagai item kode teks ekstended. |

**Throws:** IllegalArgumentException The specified codetext cannot be encoded in the selected QR compaction mode.

### addFNC1FirstPosition() {#addfnc1firstposition}

Menambahkan FNC1 pada posisi pertama ke item kode teks ekstended

### addFNC1GroupSeparator() {#addfnc1groupseparator}

Menambahkan Group Separator (GS - '\\u001D') ke item kode teks ekstended

### addFNC1SecondPosition(codetext) {#addfnc1secondposition}

Menambahkan FNC1 pada posisi kedua ke item kode teks ekstended

| Parameter | Deskripsi |
| --- | --- |
| codetext | Nilai FNC1 pada posisi kedua |

### clear() {#clear}

Menghapus item kode teks yang diperluas

### getExtendedCodetext() {#getextendedcodetext}

Menghasilkan kode teks ekstended dari daftar kode teks ekstended.

**Returns:** Extended codetext as string
