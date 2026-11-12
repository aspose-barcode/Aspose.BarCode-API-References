---
title: "ComplexBarcodeGenerator"
linktitle: "ComplexBarcodeGenerator"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "ComplexBarcodeGenerator para códigos de barras complejos de backend (p.ej."
type: docs
weight: 280
url: /es/nodejs/aspose.barcode/complexbarcodegenerator/
---

## ComplexBarcodeGenerator class

ComplexBarcodeGenerator para la generación de imágenes de códigos de barras complejos en el backend (p. ej., SwissQR).

```js
new ComplexBarcodeGenerator(complexCodetext)
```

Crea una instancia de ComplexBarcodeGenerator.

| Parámetro | Descripción |
| --- | --- |
| complexCodetext | Texto de código complejo |

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

## Métodos

| Nombre | Descripción |
| --- | --- |
| [generateBarCodeImage()](#generatebarcodeimage) | Genera una imagen de código de barras complejo con la configuración actual. |
| [getParameters()](#getparameters) | Parámetros de generación. |
| [save(filePath, format)](#save) | Genera y guarda una imagen de código de barras complejo con la configuración actual. |

### generateBarCodeImage() {#generatebarcodeimage}

Genera una imagen de código de barras complejo con la configuración actual.

**Returns:** Base64 presentation of image.

### getParameters() {#getparameters}

Parámetros de generación.

### save(filePath, format) {#save}

Genera y guarda una imagen de código de barras complejo con la configuración actual.

| Parámetro | Descripción |
| --- | --- |
| filePath | Ruta para guardar. |
| formato | BarCodeImageFormat(PNG, BMP, JPEG, GIF) |
