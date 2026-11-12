---
title: "DataBarExtendedParameters"
linktitle: "DataBarExtendedParameters"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Menyimpan informasi tambahan DataBar dari barcode yang dikenali"
type: docs
weight: 310
url: /id/nodejs/aspose.barcode/databarextendedparameters/
---

## DataBarExtendedParameters class

Menyimpan informasi tambahan DataBar dari barcode yang dikenali

```js
new DataBarExtendedParameters()
```

**Example:**

```js
let reader = new BarCodeReader("test.png", DecodeType.DATABAR_OMNI_DIRECTIONAL);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
}
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [equals(obj)](#equals) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai DataBarExtendedParameters yang ditentukan. |
| [hashCode()](#hashcode) | Mengembalikan kode hash untuk instance ini. |
| [is2DCompositeComponent()](#is2dcompositecomponent) | Mendapatkan flag komponen komposit DataBar 2D. Nilai default adalah false. |
| [toString()](#tostring) | Mengembalikan representasi string yang dapat dibaca manusia dari objek ini. |

### equals(obj) {#equals}

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai DataBarExtendedParameters yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| obj | Nilai DataBarExtendedParameters untuk dibandingkan dengan instance ini. |

**Returns:** true if obj has the same value as this instance; otherwise, false .

### hashCode() {#hashcode}

Mengembalikan kode hash untuk instance ini.

**Returns:** A 32-bit signed integer hash code.

### is2DCompositeComponent() {#is2dcompositecomponent}

Mendapatkan flag komponen komposit DataBar 2D. Nilai default adalah false.

**Returns:** The DataBar 2D composite component flag.

### toString() {#tostring}

Mengembalikan representasi string yang dapat dibaca manusia dari objek ini.

**Returns:** A string that represents this .
