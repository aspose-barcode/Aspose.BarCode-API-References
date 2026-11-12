---
title: "Code128EncodeMode"
linktitle: "Code128EncodeMode"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Mode d'encodage pour les codes-barres Code128."
type: docs
weight: 130
url: /fr/nodejs/global/code128encodemode/
---

## Code128EncodeMode

Mode d'encodage pour les codes-barres Code128. Spécification `Code 128`. Ce code montre comment générer le code 128 avec différents encodages //Generate code 128 with ISO 15417 encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO); generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG); //Generate code 128 only with Codeset A encoding let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A); generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);

## Valeurs

| Nom | Description |
| --- | --- |
| CODE_SET_A | Caractères ASCII 00 à 95 (0–9, A–Z et codes de contrôle), caractères spéciaux, et FNC 1–4 /// |
| CODE_SET_B | Caractères ASCII 32 à 127 (0–9, A–Z, a–z), caractères spéciaux, et FNC 1–4 /// |
| CODE_SET_C | 00–99 (encode deux chiffres avec un seul point de code) et FNC1 /// |
