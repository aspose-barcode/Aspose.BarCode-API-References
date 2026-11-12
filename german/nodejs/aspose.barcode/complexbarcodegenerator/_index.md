---
title: "ComplexBarcodeGenerator"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "ComplexBarcodeGenerator für komplexen Backend‑Barcode (z. B."
type: docs
weight: 280
url: /de/nodejs/aspose.barcode/complexbarcodegenerator/
---

## ComplexBarcodeGenerator class

ComplexBarcodeGenerator zur Erzeugung von Backend-Komplexbarcode (z. B. SwissQR)-Bildern.

```js
new ComplexBarcodeGenerator(complexCodetext)
```

Erstellt eine Instanz von ComplexBarcodeGenerator.

| Parameter | Beschreibung |
| --- | --- |
| complexCodetext | Komplexer Codetext |

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

## Methoden

| Name | Beschreibung |
| --- | --- |
| [generateBarCodeImage()](#generatebarcodeimage) | Erzeugt ein komplexes Barcode-Bild mit den aktuellen Einstellungen. |
| [getParameters()](#getparameters) | Erzeugungsparameter. |
| [save(filePath, format)](#save) | Erzeugt und speichert ein komplexes Barcode-Bild mit den aktuellen Einstellungen. |

### generateBarCodeImage() {#generatebarcodeimage}

Erzeugt ein komplexes Barcode-Bild mit den aktuellen Einstellungen.

**Returns:** Base64 presentation of image.

### getParameters() {#getparameters}

Erzeugungsparameter.

### save(filePath, format) {#save}

Erzeugt und speichert ein komplexes Barcode-Bild mit den aktuellen Einstellungen.

| Parameter | Beschreibung |
| --- | --- |
| filePath | Pfad zum Speichern. |
| format | BarCodeImageFormat(PNG, BMP, JPEG, GIF) |
