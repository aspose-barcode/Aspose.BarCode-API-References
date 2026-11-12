---
title: "Code128EncodeMode"
linktitle: "Code128EncodeMode"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Modo de codificación para códigos de barras Code128."
type: docs
weight: 130
url: /es/nodejs/global/code128encodemode/
---

## Code128EncodeMode

Modo de codificación para códigos de barras Code128. Especificación `Code 128`. Este código muestra cómo generar code 128 con diferentes codificaciones //Generate code 128 with ISO 15417 encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO); generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG); //Generate code 128 only with Codeset A encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A); generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);

## Valores

| Nombre | Descripción |
| --- | --- |
| CODE_SET_A | Caracteres ASCII 00 a 95 (0–9, A–Z y códigos de control), caracteres especiales y FNC 1–4 /// |
| CODE_SET_B | Caracteres ASCII 32 a 127 (0–9, A–Z, a–z), caracteres especiales y FNC 1–4 /// |
| CODE_SET_C | 00–99 (codifica dos dígitos con un solo punto de código) y FNC1 /// |
