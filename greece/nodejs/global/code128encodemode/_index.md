---
title: "Code128EncodeMode"
linktitle: "Code128EncodeMode"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Λειτουργία κωδικοποίησης για barcode Code128."
type: docs
weight: 130
url: /el/nodejs/global/code128encodemode/
---

## Code128EncodeMode

Λειτουργία κωδικοποίησης για barcode Code128. `Code 128` προδιαγραφή. Αυτός ο κώδικας δείχνει πώς να δημιουργήσετε code 128 με διαφορετικές κωδικοποιήσεις //Generate code 128 with ISO 15417 encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO); generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG); //Generate code 128 only with Codeset A encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A); generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);

## Τιμές

| Όνομα | Περιγραφή |
| --- | --- |
| CODE_SET_A | Χαρακτήρες ASCII 00 έως 95 (0–9, A–Z και κώδικες ελέγχου), ειδικοί χαρακτήρες, και FNC 1–4 /// |
| CODE_SET_B | Χαρακτήρες ASCII 32 έως 127 (0–9, A–Z, a–z), ειδικοί χαρακτήρες, και FNC 1–4 /// |
| CODE_SET_C | 00–99 (κωδικοποιεί δύο ψηφία με ένα ενιαίο σημείο κώδικα) και FNC1 /// |
