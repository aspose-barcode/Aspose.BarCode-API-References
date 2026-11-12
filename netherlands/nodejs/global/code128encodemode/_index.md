---
title: "Code128EncodeMode"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Coderingsmodus voor Code128 barcodes."
type: docs
weight: 130
url: /nl/nodejs/global/code128encodemode/
---

## Code128EncodeMode

Coderingsmodus voor Code128 barcodes. `Code 128` specificatie. Deze code laat zien hoe code 128 te genereren met verschillende coderingen //Generate code 128 with ISO 15417 encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO); generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG); //Generate code 128 only with Codeset A encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A); generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);

## Waarden

| Naam | Beschrijving |
| --- | --- |
| CODE_SET_A | ASCII‑tekens 00 tot 95 (0–9, A–Z en controlecodes), speciale tekens, en FNC 1–4 /// |
| CODE_SET_B | ASCII‑tekens 32 tot 127 (0–9, A–Z, a–z), speciale tekens, en FNC 1–4 /// |
| CODE_SET_C | 00–99 (codeert twee cijfers met één codepunt) en FNC1 /// |
