---
title: "DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Generator codetext ekstended untuk barcode DataMatrix 2D untuk Mode ExtendedCodetext dari DataMatrixEncodeMode //mode codetext ekstended //buat codetext let textBuil"
type: docs
weight: 340
url: /id/nodejs/aspose.barcode/datamatrixextcodetextbuilder/
---

## DataMatrixExtCodetextBuilder class

Generator codetext ekstended untuk barcode DataMatrix 2D untuk Mode ExtendedCodetext dari DataMatrixEncodeMode //mode codetext ekstended //buat codetext let textBuilder = new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.BYTES, "World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF_8, "犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C_40, "ABCDE"); //hasilkan codetext let codetext = textBuilder.getExtendedCodetext(); //hasilkan let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null, codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.BMP);

```js
new DataMatrixExtCodetextBuilder()
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addCodetextWithEncodeMode(encodeMode, codetext)](#addcodetextwithencodemode) | Menambahkan codetext dengan mode enkode yang ditentukan ke item codetext ekstended |
| [addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext)](#addecicodetextwithencodemode) | Menambahkan codetext dengan Identifier Saluran Ekstended dengan mode enkode yang ditentukan |
| [getExtendedCodetext()](#getextendedcodetext) | Menghasilkan kode teks ekstended dari daftar kode teks ekstended. |

### addCodetextWithEncodeMode(encodeMode, codetext) {#addcodetextwithencodemode}

Menambahkan codetext dengan mode enkode yang ditentukan ke item codetext ekstended

| Parameter | Deskripsi |
| --- | --- |
| encodeMode | Nilai mode enkode |
| codetext | Codetext dalam unicode untuk ditambahkan sebagai item codetext ekstended |

### addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext) {#addecicodetextwithencodemode}

Menambahkan codetext dengan Identifier Saluran Ekstended dengan mode enkode yang ditentukan

| Parameter | Deskripsi |
| --- | --- |
| ECIEncoding | Identifier Saluran Ekstended |
| encodeMode | Nilai mode enkode |
| codetext | Codetext dalam unicode untuk ditambahkan sebagai item codetext ekstended dengan Identifier Saluran Ekstended dengan mode enkode yang ditentukan |

### getExtendedCodetext() {#getextendedcodetext}

Menghasilkan kode teks ekstended dari daftar kode teks ekstended.

**Returns:** Extended codetext as string
