---
title: "ComplexBarcodeGenerator"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "ComplexBarcodeGenerator voor backend complexe barcode (bijv."
type: docs
weight: 280
url: /nl/nodejs/aspose.barcode/complexbarcodegenerator/
---

## ComplexBarcodeGenerator class

ComplexBarcodeGenerator voor backend‑complexe barcode‑ (bijv. SwissQR) afbeeldingsgeneratie.

```js
new ComplexBarcodeGenerator(complexCodetext)
```

Maakt een instantie van ComplexBarcodeGenerator aan.

| Parameter | Beschrijving |
| --- | --- |
| complexCodetext | Complexe codetekst |

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

| Naam | Beschrijving |
| --- | --- |
| [generateBarCodeImage()](#generatebarcodeimage) | Genereert een complexe barcode‑afbeelding met de huidige instellingen. |
| [getParameters()](#getparameters) | Generatie‑parameters. |
| [save(filePath, format)](#save) | Genereert en slaat een complexe barcode‑afbeelding op met de huidige instellingen. |

### generateBarCodeImage() {#generatebarcodeimage}

Genereert een complexe barcode‑afbeelding met de huidige instellingen.

**Returns:** Base64 presentation of image.

### getParameters() {#getparameters}

Generatie‑parameters.

### save(filePath, format) {#save}

Genereert en slaat een complexe barcode‑afbeelding op met de huidige instellingen.

| Parameter | Beschrijving |
| --- | --- |
| filePath | Pad om op te slaan. |
| formaat | BarCodeImageFormat(PNG, BMP, JPEG, GIF) |
