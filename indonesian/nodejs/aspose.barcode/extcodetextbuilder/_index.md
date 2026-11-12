---
title: "ExtCodetextBuilder"
linktitle: "ExtCodetextBuilder"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Kelas pembantu untuk pembuatan codetext otomatis pada Mode Codetext Terluas"
type: docs
weight: 400
url: /id/nodejs/aspose.barcode/extcodetextbuilder/
---

## ExtCodetextBuilder class

Kelas pembantu untuk pembuatan codetext otomatis pada Mode Codetext Terluas

```js
new ExtCodetextBuilder()
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addECICodetext(ECIEncoding, codetext)](#addecicodetext) | Menambahkan kode teks dengan Identifier Saluran Ekstensi |
| [addPlainCodetext(codetext)](#addplaincodetext) | Menambahkan kode teks biasa ke item kode teks yang diperluas |
| [clear()](#clear) | Menghapus item kode teks yang diperluas |
| [getExtendedCodetext()](#getextendedcodetext) | Menghasilkan kode teks yang diperluas dari daftar item generasi |

### addECICodetext(ECIEncoding, codetext) {#addecicodetext}

Menambahkan kode teks dengan Identifier Saluran Ekstensi

| Parameter | Deskripsi |
| --- | --- |
| ECIEncoding | Identifier Saluran Ekstended |
| codetext | Kode teks dalam Unicode untuk ditambahkan sebagai item kode teks yang diperluas dengan Identifier Saluran Ekstensi |

### addPlainCodetext(codetext) {#addplaincodetext}

Menambahkan kode teks biasa ke item kode teks yang diperluas

| Parameter | Deskripsi |
| --- | --- |
| codetext | Codetext dalam unicode untuk ditambahkan sebagai item codetext ekstended |

### clear() {#clear}

Menghapus item kode teks yang diperluas

### getExtendedCodetext() {#getextendedcodetext}

Menghasilkan kode teks yang diperluas dari daftar item generasi

**Returns:** Return string of extended codetext
