---
title: "OneDExtendedParameters"
linktitle: "OneDExtendedParameters"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Menyimpan data khusus dari barcode 1D yang dikenali seperti teks kode terpisah dan checksum."
type: docs
weight: 720
url: /id/nodejs/aspose.barcode/onedextendedparameters/
---

## OneDExtendedParameters class

Menyimpan data khusus dari barcode 1D yang dikenali seperti teks kode terpisah dan checksum.

```js
new OneDExtendedParameters()
```

**Example:**

```js
//This sample shows how to get 1D barcode value and checksum
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.EAN_13);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Value: " + result.getExtended().getOneD().getValue());
   console.log("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [equals(obj)](#equals) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai OneDExtendedParameters yang ditentukan. |
| [getCheckSum()](#getchecksum) | Mendapatkan checksum untuk barcode 1D. Nilai: Checksum untuk barcode 1D. |
| [getValue()](#getvalue) | Mendapatkan codetext barcode 1D tanpa checksum. Nilai: Codetext barcode 1D tanpa checksum. |
| [hashCode()](#hashcode) | Mengembalikan kode hash untuk instance ini. |
| [isEmpty()](#isempty) | Menguji apakah semua parameter hanya memiliki nilai default Nilai: Mengembalikan `true ` jika semua parameter hanya memiliki nilai default; o |
| [toString()](#tostring) | Mengembalikan representasi string yang dapat dibaca manusia dari OneDExtendedParameters ini. |

### equals(obj) {#equals}

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai OneDExtendedParameters yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| obj | Sebuah nilai System.Object untuk dibandingkan dengan instance ini. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCheckSum() {#getchecksum}

Mendapatkan checksum untuk barcode 1D. Nilai: Checksum untuk barcode 1D.

### getValue() {#getvalue}

Mendapatkan codetext barcode 1D tanpa checksum. Nilai: Codetext barcode 1D tanpa checksum.

### hashCode() {#hashcode}

Mengembalikan kode hash untuk instance ini.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Menguji apakah semua parameter hanya memiliki nilai default. Nilai: Mengembalikan `true ` jika semua parameter hanya memiliki nilai default; jika tidak, `false `.

### toString() {#tostring}

Mengembalikan representasi string yang dapat dibaca manusia dari OneDExtendedParameters ini.

**Returns:** A string that represents this OneDExtendedParameters.
