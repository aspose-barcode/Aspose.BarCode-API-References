---
title: "FontUnit"
linktitle: "FontUnit"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Mendefinisikan format khusus untuk teks, termasuk jenis huruf, ukuran, dan atribut gaya di mana ukuran berada dalam properti nilai Unit."
type: docs
weight: 410
url: /id/nodejs/aspose.barcode/fontunit/
---

## FontUnit class

Mendefinisikan format khusus untuk teks, termasuk jenis huruf, ukuran, dan atribut gaya di mana ukuran berada dalam properti nilai Unit.

```js
new FontUnit()
```

**Example:**

```js
This sample shows how to create and save a BarCode image.

  let generator = new BarcodeGenerator(EncodeTypes.CODE_128);
  generator.getParameters().getCaptionAbove().setText("CAPTION ABOOVE");
  generator.getParameters().getCaptionAbove().setVisible(true);
  generator.getParameters().getCaptionAbove().getFont().setStyle(FontStyle.ITALIC);
  generator.getParameters().getCaptionAbove().getFont().getSize().setPoint(25);
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getFamilyName()](#getfamilyname) | Mendapatkan nama jenis huruf dari Font ini. |
| [getSize()](#getsize) | Mendapatkan ukuran FontUnit ini dalam nilai Unit. |
| [getStyle()](#getstyle) | Mendapatkan informasi gaya untuk FontUnit ini. |
| [setFamilyName()](#setfamilyname) | Mengatur nama jenis huruf dari Font ini. |
| [setStyle()](#setstyle) | Mengatur informasi gaya untuk FontUnit ini. |

### getFamilyName() {#getfamilyname}

Mendapatkan nama jenis huruf dari Font ini.

### getSize() {#getsize}

Mendapatkan ukuran FontUnit ini dalam nilai Unit.

**Throws:** IllegalArgumentExceptionThe Size parameter value is less than or equal to 0.

### getStyle() {#getstyle}

Mendapatkan informasi gaya untuk FontUnit ini.

### setFamilyName() {#setfamilyname}

Mengatur nama jenis huruf dari Font ini.

### setStyle() {#setstyle}

Mengatur informasi gaya untuk FontUnit ini.
