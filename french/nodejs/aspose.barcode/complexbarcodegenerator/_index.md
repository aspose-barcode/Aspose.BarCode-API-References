---
title: "ComplexBarcodeGenerator"
linktitle: "ComplexBarcodeGenerator"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "ComplexBarcodeGenerator pour le code-barres complexe backend (p. ex."
type: docs
weight: 280
url: /fr/nodejs/aspose.barcode/complexbarcodegenerator/
---

## ComplexBarcodeGenerator class

ComplexBarcodeGenerator pour la génération d'images de code-barres complexes côté serveur (p. ex. SwissQR).

```js
new ComplexBarcodeGenerator(complexCodetext)
```

Crée une instance de ComplexBarcodeGenerator.

| Paramètre | Description |
| --- | --- |
| complexCodetext | Texte de code complexe |

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

## Méthodes

| Nom | Description |
| --- | --- |
| [generateBarCodeImage()](#generatebarcodeimage) | Génère l'image du code-barres complexe selon les paramètres actuels. |
| [getParameters()](#getparameters) | Paramètres de génération. |
| [save(filePath, format)](#save) | Génère et enregistre l'image du code-barres complexe selon les paramètres actuels. |

### generateBarCodeImage() {#generatebarcodeimage}

Génère l'image du code-barres complexe selon les paramètres actuels.

**Returns:** Base64 presentation of image.

### getParameters() {#getparameters}

Paramètres de génération.

### save(filePath, format) {#save}

Génère et enregistre l'image du code-barres complexe selon les paramètres actuels.

| Paramètre | Description |
| --- | --- |
| filePath | Chemin où enregistrer. |
| format | BarCodeImageFormat(PNG, BMP, JPEG, GIF) |
