---
title: "ComplexBarcodeGenerator"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "ComplexBarcodeGenerator för backend-komplex streckkod (t.ex."
type: docs
weight: 280
url: /sv/nodejs/aspose.barcode/complexbarcodegenerator/
---

## ComplexBarcodeGenerator class

ComplexBarcodeGenerator för generering av backend‑komplexa streckkodsbilder (t.ex. SwissQR).

```js
new ComplexBarcodeGenerator(complexCodetext)
```

Skapar en instans av ComplexBarcodeGenerator.

| Parameter | Beskrivning |
| --- | --- |
| complexCodetext | Komplex kodtext |

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [generateBarCodeImage()](#generatebarcodeimage) | Genererar komplex streckkodbild enligt aktuella inställningar. |
| [getParameters()](#getparameters) | Genereringsparametrar. |
| [save(filePath, format)](#save) | Genererar och sparar komplex streckkodbild enligt aktuella inställningar. |

### generateBarCodeImage() {#generatebarcodeimage}

Genererar komplex streckkodbild enligt aktuella inställningar.

**Returns:** Base64 presentation of image.

### getParameters() {#getparameters}

Genereringsparametrar.

### save(filePath, format) {#save}

Genererar och sparar komplex streckkodbild enligt aktuella inställningar.

| Parameter | Beskrivning |
| --- | --- |
| filePath | Sökväg att spara till. |
| format | BarCodeImageFormat(PNG, BMP, JPEG, GIF) |
