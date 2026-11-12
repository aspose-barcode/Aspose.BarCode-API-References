---
title: "Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Menyimpan data khusus dari barcode Code128 yang dikenali Mewakili wilayah barcode yang dikenali dan sudut barcode"
type: docs
weight: 240
url: /id/nodejs/aspose.barcode/code128extendedparameters/
---

## Code128ExtendedParameters class

Menyimpan data khusus dari barcode Code128 yang dikenali Mewakili wilayah barcode yang dikenali dan sudut barcode

```js
new Code128ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get code128 raw values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.CODE_128);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("Code128 Data Portions: " + result.getExtended().getCode128());
}
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [equals(obj)](#equals) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai Code128ExtendedParameters yang ditentukan. |
| [getCode128DataPortions()](#getcode128dataportions) | Mendapatkan array Code128DataPortion dari barcode Code128 yang dikenali. Nilai dari Code128DataPortion. |
| [hashCode()](#hashcode) | Mengembalikan kode hash untuk instance ini. |
| [toString()](#tostring) | Mengembalikan representasi string yang dapat dibaca manusia dari Code128ExtendedParameters ini. |

### equals(obj) {#equals}

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai Code128ExtendedParameters yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| obj | Sebuah nilai System.Object untuk dibandingkan dengan instance ini. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCode128DataPortions() {#getcode128dataportions}

Mendapatkan array Code128DataPortion dari barcode Code128 yang dikenali. Nilai dari Code128DataPortion.

### hashCode() {#hashcode}

Mengembalikan kode hash untuk instance ini.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Mengembalikan representasi string yang dapat dibaca manusia dari Code128ExtendedParameters ini.

**Returns:** A string that represents this Code128ExtendedParameters.
