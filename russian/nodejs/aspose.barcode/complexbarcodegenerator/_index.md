---
title: "ComplexBarcodeGenerator"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "ComplexBarcodeGenerator для бэкенд‑генерации сложных штрих‑кодов (например,"
type: docs
weight: 280
url: /ru/nodejs/aspose.barcode/complexbarcodegenerator/
---

## ComplexBarcodeGenerator class

ComplexBarcodeGenerator для генерации изображений сложных штрих‑кодов бекэнда (например, SwissQR).

```js
new ComplexBarcodeGenerator(complexCodetext)
```

Создаёт экземпляр ComplexBarcodeGenerator.

| Параметр | Описание |
| --- | --- |
| complexCodetext | Сложный кодовый текст |

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

## Методы

| Имя | Описание |
| --- | --- |
| [generateBarCodeImage()](#generatebarcodeimage) | Создаёт изображение сложного штрих‑кода с текущими настройками. |
| [getParameters()](#getparameters) | Параметры генерации. |
| [save(filePath, format)](#save) | Создаёт и сохраняет изображение сложного штрих‑кода с текущими настройками. |

### generateBarCodeImage() {#generatebarcodeimage}

Создаёт изображение сложного штрих‑кода с текущими настройками.

**Returns:** Base64 presentation of image.

### getParameters() {#getparameters}

Параметры генерации.

### save(filePath, format) {#save}

Создаёт и сохраняет изображение сложного штрих‑кода с текущими настройками.

| Параметр | Описание |
| --- | --- |
| filePath | Путь для сохранения. |
| формат | BarCodeImageFormat(PNG, BMP, JPEG, GIF) |
