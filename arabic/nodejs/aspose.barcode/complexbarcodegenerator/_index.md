---
title: "ComplexBarcodeGenerator"
linktitle: "ComplexBarcodeGenerator"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "ComplexBarcodeGenerator للباركود المعقد في الخلفية (مثال"
type: docs
weight: 280
url: /ar/nodejs/aspose.barcode/complexbarcodegenerator/
---

## ComplexBarcodeGenerator class

ComplexBarcodeGenerator لتوليد صور الباركود المعقد في الخلفية (مثل SwissQR).

```js
new ComplexBarcodeGenerator(complexCodetext)
```

إنشاء مثال من ComplexBarcodeGenerator.

| معامل | الوصف |
| --- | --- |
| complexCodetext | نص الكود المعقد |

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

## طرق

| اسم | الوصف |
| --- | --- |
| [generateBarCodeImage()](#generatebarcodeimage) | يولد صورة باركود معقدة وفق الإعدادات الحالية. |
| [getParameters()](#getparameters) | معلمات الإنشاء. |
| [save(filePath, format)](#save) | يولد ويحفظ صورة باركود معقدة وفق الإعدادات الحالية. |

### generateBarCodeImage() {#generatebarcodeimage}

يولد صورة باركود معقدة وفق الإعدادات الحالية.

**Returns:** Base64 presentation of image.

### getParameters() {#getparameters}

معلمات الإنشاء.

### save(filePath, format) {#save}

يولد ويحفظ صورة باركود معقدة وفق الإعدادات الحالية.

| معامل | الوصف |
| --- | --- |
| filePath | المسار للحفظ إليه. |
| التنسيق | BarCodeImageFormat(PNG, BMP, JPEG, GIF) |
