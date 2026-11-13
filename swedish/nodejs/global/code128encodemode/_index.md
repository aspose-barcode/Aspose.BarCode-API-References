---
title: "Code128EncodeMode"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Kodningsläge för Code128‑streckkoder."
type: docs
weight: 130
url: /sv/nodejs/global/code128encodemode/
---

## Code128EncodeMode

Kodningsläge för Code128‑streckkoder. `Code 128`‑specifikation. Den här koden demonstrerar hur man genererar Code 128 med olika kodningar //Generera Code 128 med ISO 15417‑kodning let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO); generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG); //Generera Code 128 endast med Codeset A‑kodning let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A); generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);

## Värden

| Namn | Beskrivning |
| --- | --- |
| CODE_SET_A | ASCII-tecken 00 till 95 (0–9, A–Z och kontrollkoder), specialtecken och FNC 1–4 /// |
| CODE_SET_B | ASCII-tecken 32 till 127 (0–9, A–Z, a–z), specialtecken och FNC 1–4 /// |
| CODE_SET_C | 00–99 (kodar två siffror med en enda kodpunkt) och FNC1 /// |
