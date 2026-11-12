---
title: "AztecExtCodetextBuilder"
linktitle: "AztecExtCodetextBuilder"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Generator kode teks ekstended untuk barcode Aztec dalam Mode ExtendedCodetext dari AztecEncodeMode. Gunakan properti TwoDDisplayText dari BarcodeGenerator untuk mengatur teks yang terlihat."
type: docs
weight: 50
url: /id/nodejs/aspose.barcode/aztecextcodetextbuilder/
---

## AztecExtCodetextBuilder class

Generator kode teks ekstended untuk barcode Aztec dalam Mode ExtendedCodetext dari AztecEncodeMode. Gunakan properti TwoDDisplayText dari BarcodeGenerator untuk mengatur teks yang terlihat dengan menghapus karakter pengelolaan. Contoh ini menunjukkan cara menggunakan AztecExtCodetextBuilder dalam Mode Extended.

```js
new AztecExtCodetextBuilder()
```

**Example:**

```js
//create codetext
     let textBuilder = new AztecExtCodetextBuilder();
     textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
     textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
     textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
     textBuilder.addPlainCodetext("Plain text");
     //generate codetext
     let codetext = textBuilder.getExtendedCodetext();
     //generate
     let generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
     generator.getParameters().getBarcode().getCodeTextParameters().setwoDDisplayText("My Text");
     generator.save("test.bmp", BarcodeImageFormat.BMP);
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Menghasilkan kode teks ekstended dari daftar kode teks ekstended. |

### getExtendedCodetext() {#getextendedcodetext}

Menghasilkan kode teks ekstended dari daftar kode teks ekstended.

**Returns:** Extended codetext as string
