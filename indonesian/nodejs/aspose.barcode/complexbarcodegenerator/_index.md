---
title: "ComplexBarcodeGenerator"
linktitle: "ComplexBarcodeGenerator"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "ComplexBarcodeGenerator untuk barcode kompleks backend (misalnya"
type: docs
weight: 280
url: /id/nodejs/aspose.barcode/complexbarcodegenerator/
---

## ComplexBarcodeGenerator class

ComplexBarcodeGenerator untuk generasi gambar barcode kompleks backend (mis. SwissQR).

```js
new ComplexBarcodeGenerator(complexCodetext)
```

Membuat sebuah instance dari ComplexBarcodeGenerator.

| Parameter | Deskripsi |
| --- | --- |
| complexCodetext | Kode teks kompleks |

**Example:**

```js
This sample shows how to create and save a SwissQR image.
   let swissQRCodetext = new SwissQRCodetext(null);
   swissQRCodetext.getBill().setAccount("Account");
   swissQRCodetext.getBill().setBillInformation("BillInformation");
   swissQRCodetext.getBill().setBillInformation("BillInformation");
   swissQRCodetext.getBill().setAmount(1024);
   swissQRCodetext.getBill().getCreditor().setName("Creditor.Name");
   swissQRCodetext.getBill().getCreditor().setAddressLine1("Creditor.AddressLine1");
   swissQRCodetext.getBill().getCreditor().setAddressLine2("Creditor.AddressLine2");
   swissQRCodetext.getBill().getCreditor().setCountryCode("Nl");
   swissQRCodetext.getBill().setUnstructuredMessage("UnstructuredMessage");
   swissQRCodetext.getBill().setReference("Reference");
   swissQRCodetext.getBill().setAlternativeSchemes([new AlternativeScheme("AlternativeSchemeInstruction1"),new AlternativeScheme("AlternativeSchemeInstruction2")]);
   swissQRCodetext.getBill().setDebtor(new Address(null));
   swissQRCodetext.getBill().getDebtor().setName("Debtor.Name");
   swissQRCodetext.getBill().getDebtor().setAddressLine1("Debtor.AddressLine1");
   swissQRCodetext.getBill().getDebtor().setAddressLine2("Debtor.AddressLine2");
   swissQRCodetext.getBill().getDebtor().setCountryCode("Lux");
   let cg = new ComplexBarcodeGenerator(swissQRCodetext);
   let res = cg.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [generateBarCodeImage()](#generatebarcodeimage) | Menghasilkan gambar barcode kompleks dengan pengaturan saat ini. |
| [getParameters()](#getparameters) | Parameter generasi. |
| [save(filePath, format)](#save) | Menghasilkan dan menyimpan gambar barcode kompleks dengan pengaturan saat ini. |

### generateBarCodeImage() {#generatebarcodeimage}

Menghasilkan gambar barcode kompleks dengan pengaturan saat ini.

**Returns:** Base64 presentation of image.

### getParameters() {#getparameters}

Parameter generasi.

### save(filePath, format) {#save}

Menghasilkan dan menyimpan gambar barcode kompleks dengan pengaturan saat ini.

| Parameter | Deskripsi |
| --- | --- |
| filePath | Jalur untuk disimpan. |
| format | BarCodeImageFormat(PNG, BMP, JPEG, GIF) |
