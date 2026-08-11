---
title: "Code128EncodeMode"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Encoding mode for Code128 barcodes."
type: docs
weight: 130
url: /nodejs/global/code128encodemode/
---

## Code128EncodeMode

Encoding mode for Code128 barcodes. `Code 128` specification. Thos code demonstrates how to generate code 128 with different encodings //Generate code 128 with ISO 15417 encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO); generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG); //Generate code 128 only with Codeset A encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A); generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);

## Values

| Name | Description |
| --- | --- |
| CODE_SET_A | ASCII characters 00 to 95 (0–9, A–Z and control codes), special characters, and FNC 1–4 /// |
| CODE_SET_B | ASCII characters 32 to 127 (0–9, A–Z, a–z), special characters, and FNC 1–4 /// |
| CODE_SET_C | 00–99 (encodes two digits with a single code point) and FNC1 /// |
