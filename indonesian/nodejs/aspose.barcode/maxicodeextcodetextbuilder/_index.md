---
title: "MaxiCodeExtCodetextBuilder"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Generator teks kode ekstended untuk barcode MaxiCode untuk Mode ExtendedCodetext dari MaxiCodeEncodeMode. Gunakan properti TwoDDisplayText dari BarcodeGenerator untuk mengatur visibl"
type: docs
weight: 630
url: /id/nodejs/aspose.barcode/maxicodeextcodetextbuilder/
---

## MaxiCodeExtCodetextBuilder class

Generator codetext yang diperluas untuk barcode MaxiCode untuk Mode ExtendedCodetext dari MaxiCodeEncodeMode. Gunakan properti TwoDDisplayText dari BarcodeGenerator untuk mengatur teks yang terlihat dengan menghapus karakter pengelolaan. Contoh ini menunjukkan cara menggunakan MaxiCodeExtCodetextBuilder dalam Mode Extended.

```js
new MaxiCodeExtCodetextBuilder()
```

**Example:**

```js
//create codetext
let textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");

//generate codetext
let codetext = textBuilder.getExtendedCodetext();

//generate
let generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
generator.save("test.bmp", BarcodeImageFormat.BMP);
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Menghasilkan kode teks ekstended dari daftar kode teks ekstended. |

### getExtendedCodetext() {#getextendedcodetext}

Menghasilkan kode teks ekstended dari daftar kode teks ekstended.

**Returns:** Extended codetext as string
