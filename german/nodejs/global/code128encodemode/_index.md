---
title: "Code128EncodeMode"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Kodierungsmodus für Code128‑Barcodes."
type: docs
weight: 130
url: /de/nodejs/global/code128encodemode/
---

## Code128EncodeMode

Kodierungsmodus für Code128-Barcodes. `Code 128` Spezifikation. Dieser Code demonstriert, wie man Code 128 mit verschiedenen Kodierungen erzeugt //Generiere Code 128 mit ISO 15417 Kodierung let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO); generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG); //Generiere Code 128 ausschließlich mit Codeset A Kodierung let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A); generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);

## Werte

| Name | Beschreibung |
| --- | --- |
| CODE_SET_A | ASCII-Zeichen 00 bis 95 (0–9, A–Z und Steuerzeichen), Sonderzeichen und FNC 1–4 /// |
| CODE_SET_B | ASCII-Zeichen 32 bis 127 (0–9, A–Z, a–z), Sonderzeichen und FNC 1–4 /// |
| CODE_SET_C | 00–99 (kodiert zwei Ziffern mit einem einzigen Codepunkt) und FNC1 /// |
