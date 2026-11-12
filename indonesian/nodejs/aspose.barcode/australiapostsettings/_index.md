---
title: "AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Parameter decoding AustraliaPost."
type: docs
weight: 30
url: /id/nodejs/aspose.barcode/australiapostsettings/
---

## AustraliaPostSettings class

Parameter decoding AustraliaPost. Berisi parameter yang memengaruhi data yang dikenali dari simbol AustraliaPost.

```js
new AustraliaPostSettings()
```

Konstruktor AustraliaPostSettings

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getCustomerInformationInterpretingType()](#getcustomerinformationinterpretingtype) | Mendapatkan Tipe Interpretasi untuk Informasi Pelanggan dari AustralianPost BarCode.DEFAULT adalah CustomerInformationInterpre |
| [getIgnoreEndingFillingPatternsForCTable()](#getignoreendingfillingpatternsforctable) | Bendera yang memaksa decoder AustraliaPost mengabaikan pola pengisian terakhir di bidang Informasi Pelanggan selama proses decoding |
| [setCustomerInformationInterpretingType(value)](#setcustomerinformationinterpretingtype) | Mengatur Tipe Interpretasi untuk Informasi Pelanggan dari AustralianPost BarCode.DEFAULT adalah CustomerInformationInterpre |
| [setIgnoreEndingFillingPatternsForCTable()](#setignoreendingfillingpatternsforctable) | Bendera yang memaksa decoder AustraliaPost mengabaikan pola pengisian terakhir di bidang Informasi Pelanggan selama proses decoding |

### getCustomerInformationInterpretingType() {#getcustomerinformationinterpretingtype}

Mendapatkan Tipe Interpretasi untuk Informasi Pelanggan dari AustralianPost BarCode.DEFAULT adalah CustomerInformationInterpretingType.OTHER.

**Returns:** The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode

### getIgnoreEndingFillingPatternsForCTable() {#getignoreendingfillingpatternsforctable}

Bendera yang memaksa decoder AustraliaPost mengabaikan pola pengisian terakhir di bidang Informasi Pelanggan selama proses decoding sebagai metode CTable. Metode enkoding CTable tidak memiliki celah dalam tabel enkoding dan urutan "333" dari pola pengisian didekode sebagai huruf "z".

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeType());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setCustomerInformationInterpretingType(value) {#setcustomerinformationinterpretingtype}

Mengatur Tipe Interpretasi untuk Informasi Pelanggan dari AustralianPost BarCode.DEFAULT adalah CustomerInformationInterpretingType.OTHER.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Tipe interpretasi (CTable, NTable, atau Lainnya) dari informasi pelanggan untuk AustralianPost BarCode |

### setIgnoreEndingFillingPatternsForCTable() {#setignoreendingfillingpatternsforctable}

Bendera yang memaksa decoder AustraliaPost mengabaikan pola pengisian terakhir di bidang Informasi Pelanggan selama proses decoding sebagai metode CTable. Metode enkoding CTable tidak memiliki celah dalam tabel enkoding dan urutan "333" dari pola pengisian didekode sebagai huruf "z".

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeType());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```
