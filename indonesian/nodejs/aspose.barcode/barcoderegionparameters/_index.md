---
title: "BarCodeRegionParameters"
linktitle: "BarCodeRegionParameters"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Mewakili wilayah barcode yang dikenali dan sudut barcode"
type: docs
weight: 100
url: /id/nodejs/aspose.barcode/barcoderegionparameters/
---

## BarCodeRegionParameters class

Mewakili wilayah barcode yang dikenali dan sudut barcode

```js
new BarCodeRegionParameters()
```

**Example:**

```js
//This sample shows how to get barcode Angle and bounding quadrangle values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Angle: " + result.getRegion().getAngle());
   console.log("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
}
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [equals(obj)](#equals) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai BarCodeRegionParameters yang ditentukan. |
| [getAngle()](#getangle) | Mendapatkan sudut barcode (0-360). Nilai: Sudut untuk barcode (0-360). |
| [getPoints()](#getpoints) | Mendapatkan array Points yang membatasi wilayah kode batang Nilai: Mengembalikan array Points yang membatasi wilayah kode batang |
| [getQuadrangle()](#getquadrangle) | Mendapatkan Quadrangle yang membatasi wilayah kode batang Nilai: Mengembalikan Quadrangle yang membatasi wilayah kode batang |
| [getRectangle()](#getrectangle) | Mendapatkan Rectangle yang membatasi wilayah kode batang Nilai: Mengembalikan Rectangle yang membatasi wilayah kode batang |
| [hashCode()](#hashcode) | Mengembalikan kode hash untuk instance ini. |
| [toString()](#tostring) | Mengembalikan representasi string yang dapat dibaca manusia dari BarCodeRegionParameters ini. |

### equals(obj) {#equals}

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai BarCodeRegionParameters yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| obj | Sebuah nilai System.Object untuk dibandingkan dengan instance ini. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getAngle() {#getangle}

Mendapatkan sudut barcode (0-360). Nilai: Sudut untuk barcode (0-360).

### getPoints() {#getpoints}

Mendapatkan array Points yang membatasi wilayah kode batang Nilai: Mengembalikan array Points yang membatasi wilayah kode batang

### getQuadrangle() {#getquadrangle}

Mendapatkan Quadrangle yang membatasi wilayah kode batang Nilai: Mengembalikan Quadrangle yang membatasi wilayah kode batang

### getRectangle() {#getrectangle}

Mendapatkan Rectangle yang membatasi wilayah kode batang Nilai: Mengembalikan Rectangle yang membatasi wilayah kode batang

### hashCode() {#hashcode}

Mengembalikan kode hash untuk instance ini.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Mengembalikan representasi string yang dapat dibaca manusia dari BarCodeRegionParameters ini.

**Returns:** A string that represents this BarCodeRegionParameters.
