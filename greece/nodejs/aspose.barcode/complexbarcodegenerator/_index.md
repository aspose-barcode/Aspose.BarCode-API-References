---
title: "ComplexBarcodeGenerator"
linktitle: "ComplexBarcodeGenerator"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "ComplexBarcodeGenerator για σύνθετο barcode στο backend (πχ."
type: docs
weight: 280
url: /el/nodejs/aspose.barcode/complexbarcodegenerator/
---

## ComplexBarcodeGenerator class

ComplexBarcodeGenerator για δημιουργία εικόνων backend σύνθετου barcode (π.χ. SwissQR).

```js
new ComplexBarcodeGenerator(complexCodetext)
```

Δημιουργεί μια παρουσία του ComplexBarcodeGenerator.

| Παράμετρος | Περιγραφή |
| --- | --- |
| complexCodetext | Σύνθετο codetext |

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

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [generateBarCodeImage()](#generatebarcodeimage) | Δημιουργεί εικόνα σύνθετου barcode με τις τρέχουσες ρυθμίσεις. |
| [getParameters()](#getparameters) | Παράμετροι δημιουργίας. |
| [save(filePath, format)](#save) | Δημιουργεί και αποθηκεύει εικόνα σύνθετου barcode με τις τρέχουσες ρυθμίσεις. |

### generateBarCodeImage() {#generatebarcodeimage}

Δημιουργεί εικόνα σύνθετου barcode με τις τρέχουσες ρυθμίσεις.

**Returns:** Base64 presentation of image.

### getParameters() {#getparameters}

Παράμετροι δημιουργίας.

### save(filePath, format) {#save}

Δημιουργεί και αποθηκεύει εικόνα σύνθετου barcode με τις τρέχουσες ρυθμίσεις.

| Παράμετρος | Περιγραφή |
| --- | --- |
| filePath | Διαδρομή αποθήκευσης. |
| μορφή | BarCodeImageFormat(PNG, BMP, JPEG, GIF) |
