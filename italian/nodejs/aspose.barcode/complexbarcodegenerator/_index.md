---
title: "ComplexBarcodeGenerator"
linktitle: "ComplexBarcodeGenerator"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "ComplexBarcodeGenerator per barcode complesso di backend (ad es."
type: docs
weight: 280
url: /it/nodejs/aspose.barcode/complexbarcodegenerator/
---

## ComplexBarcodeGenerator class

ComplexBarcodeGenerator per la generazione di immagini di barcode complessi backend (ad es. SwissQR).

```js
new ComplexBarcodeGenerator(complexCodetext)
```

Crea un'istanza di ComplexBarcodeGenerator.

| Parametro | Descrizione |
| --- | --- |
| complexCodetext | Codetext complesso |

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [generateBarCodeImage()](#generatebarcodeimage) | Genera l'immagine del barcode complesso con le impostazioni correnti. |
| [getParameters()](#getparameters) | Parametri di generazione. |
| [save(filePath, format)](#save) | Genera e salva l'immagine del barcode complesso con le impostazioni correnti. |

### generateBarCodeImage() {#generatebarcodeimage}

Genera l'immagine del barcode complesso con le impostazioni correnti.

**Returns:** Base64 presentation of image.

### getParameters() {#getparameters}

Parametri di generazione.

### save(filePath, format) {#save}

Genera e salva l'immagine del barcode complesso con le impostazioni correnti.

| Parametro | Descrizione |
| --- | --- |
| filePath | Percorso in cui salvare. |
| formato | BarCodeImageFormat(PNG, BMP, JPEG, GIF) |
