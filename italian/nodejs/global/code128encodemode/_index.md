---
title: "Code128EncodeMode"
linktitle: "Code128EncodeMode"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Modalità di codifica per i codici a barre Code128."
type: docs
weight: 130
url: /it/nodejs/global/code128encodemode/
---

## Code128EncodeMode

Modalità di codifica per i codici a barre Code128. Specifica `Code 128`. Questo codice dimostra come generare il code 128 con diverse codifiche //Genera code 128 con codifica ISO 15417 let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO); generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG); //Genera code 128 solo con codifica Codeset A let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A); generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);

## Valori

| Nome | Descrizione |
| --- | --- |
| CODE_SET_A | Caratteri ASCII da 00 a 95 (0–9, A–Z e codici di controllo), caratteri speciali e FNC 1–4 /// |
| CODE_SET_B | Caratteri ASCII da 32 a 127 (0–9, A–Z, a–z), caratteri speciali e FNC 1–4 /// |
| CODE_SET_C | 00–99 (codifica due cifre con un singolo punto di codice) e FNC1 /// |
