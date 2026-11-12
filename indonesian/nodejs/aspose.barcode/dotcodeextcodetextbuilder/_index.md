---
title: "DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Generator codetext diperluas untuk barcode DotCode 2D untuk Mode ExtendedCodetext dari DotCodeEncodeMode"
type: docs
weight: 370
url: /id/nodejs/aspose.barcode/dotcodeextcodetextbuilder/
---

## DotCodeExtCodetextBuilder class

Generator codetext diperluas untuk barcode DotCode 2D untuk Mode ExtendedCodetext dari DotCodeEncodeMode

```js
new DotCodeExtCodetextBuilder()
```

**Example:**

```js
//Extended codetext mode
//create codetext
let textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");
textBuilder.addFNC3SymbolSeparator();
textBuilder.addFNC3ReaderInitialization();
textBuilder.addPlainCodetext("Reader initialization info");
//generate codetext
let codetext = textBuilder.getExtendedCodetext();
//generate
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
generator.save("test.bmp", BarCodeImageFormat.BMP);
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addFNC1FormatIdentifier()](#addfnc1formatidentifier) | Menambahkan pengidentifikasi format FNC1 ke item codetext yang diperluas. |
| [addFNC3ReaderInitialization()](#addfnc3readerinitialization) | Menambahkan inisialisasi pembaca FNC3 ke item codetext yang diperluas. |
| [addFNC3SymbolSeparator()](#addfnc3symbolseparator) | Menambahkan pemisah simbol FNC3 ke item codetext yang diperluas. |
| [addStructuredAppendMode(barcodeId, barcodesCount)](#addstructuredappendmode) | Menambahkan mode penambahan terstruktur ke item codetext yang diperluas. |
| [getExtendedCodetext()](#getextendedcodetext) | Menghasilkan kode teks ekstended dari daftar kode teks ekstended. |

### addFNC1FormatIdentifier() {#addfnc1formatidentifier}

Menambahkan pengidentifikasi format FNC1 ke item codetext yang diperluas.

### addFNC3ReaderInitialization() {#addfnc3readerinitialization}

Menambahkan inisialisasi pembaca FNC3 ke item codetext yang diperluas.

### addFNC3SymbolSeparator() {#addfnc3symbolseparator}

Menambahkan pemisah simbol FNC3 ke item codetext yang diperluas.

### addStructuredAppendMode(barcodeId, barcodesCount) {#addstructuredappendmode}

Menambahkan mode penambahan terstruktur ke item codetext yang diperluas.

| Parameter | Deskripsi |
| --- | --- |
| barcodeId | ID barcode |
| barcodesCount | Jumlah barcode |

### getExtendedCodetext() {#getextendedcodetext}

Menghasilkan kode teks ekstended dari daftar kode teks ekstended.

**Returns:** Extended codetext as string
