---
title: "Unit"
linktitle: "Unit"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Menentukan nilai ukuran dalam berbagai satuan (Pixel, Inci, dll)."
type: docs
weight: 960
url: /id/nodejs/aspose.barcode/unit/
---

## Unit class

Menentukan nilai ukuran dalam berbagai satuan (Pixel, Inci, dll).

```js
new Unit()
```

**Example:**

```js
//This sample shows how to create and save a BarCode image.
   let generator = new BarcodeGenerator(EncodeTypes.CODE_128);
   generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
   generator.save("test.png", BarcodeImageFormat.PNG);
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [equals(obj)](#equals) | Menentukan apakah instance ini dan objek yang ditentukan, yang juga harus berupa objek Unit, memiliki nilai yang sama. |
| [getDocument()](#getdocument) | Mendapatkan nilai ukuran dalam satuan dokumen. |
| [getInches()](#getinches) | Mendapatkan nilai ukuran dalam inci. |
| [getMillimeters()](#getmillimeters) | Mendapatkan nilai ukuran dalam milimeter. |
| [getPixels()](#getpixels) | Mendapatkan nilai ukuran dalam piksel. |
| [getPoint()](#getpoint) | Mendapatkan nilai ukuran dalam poin. |
| [setDocument()](#setdocument) | Mengatur nilai ukuran dalam satuan dokumen. |
| [setInches()](#setinches) | Mengatur nilai ukuran dalam inci. |
| [setMillimeters()](#setmillimeters) | Mengatur nilai ukuran dalam milimeter. |
| [setPixels()](#setpixels) | Mengatur nilai ukuran dalam piksel. |
| [setPoint()](#setpoint) | Mengatur nilai ukuran dalam poin. |
| [toString()](#tostring) | Mengembalikan representasi string yang dapat dibaca manusia dari Unit ini. |

### equals(obj) {#equals}

Menentukan apakah instance ini dan objek yang ditentukan, yang juga harus berupa objek Unit, memiliki nilai yang sama.

| Parameter | Deskripsi |
| --- | --- |
| obj | Unit yang dibandingkan dengan instance ini. |

**Returns:** true if obj is a Unit and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.

### getDocument() {#getdocument}

Mendapatkan nilai ukuran dalam satuan dokumen.

### getInches() {#getinches}

Mendapatkan nilai ukuran dalam inci.

### getMillimeters() {#getmillimeters}

Mendapatkan nilai ukuran dalam milimeter.

### getPixels() {#getpixels}

Mendapatkan nilai ukuran dalam piksel.

### getPoint() {#getpoint}

Mendapatkan nilai ukuran dalam poin.

### setDocument() {#setdocument}

Mengatur nilai ukuran dalam satuan dokumen.

### setInches() {#setinches}

Mengatur nilai ukuran dalam inci.

### setMillimeters() {#setmillimeters}

Mengatur nilai ukuran dalam milimeter.

### setPixels() {#setpixels}

Mengatur nilai ukuran dalam piksel.

### setPoint() {#setpoint}

Mengatur nilai ukuran dalam poin.

### toString() {#tostring}

Mengembalikan representasi string yang dapat dibaca manusia dari Unit ini.

**Returns:** A string that represents this Unit.
