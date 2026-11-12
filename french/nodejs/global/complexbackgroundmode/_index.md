---
title: "ComplexBackgroundMode"
linktitle: "ComplexBackgroundMode"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres couleur sur les images couleur."
type: docs
weight: 160
url: /fr/nodejs/global/complexbackgroundmode/
---

## ComplexBackgroundMode

Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres couleur sur des images couleur. Cet exemple montre comment utiliser le mode ComplexBackground let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Valeurs

| Nom | Description |
| --- | --- |
| C_TABLE | Utilisez C_TABLE pour interpréter les informations client. Autorise A..Z, a..z, 1..9, espace et le caractère #. |
| N_TABLE | Utilisez N_TABLE pour interpréter les informations client. Autorise les chiffres. |
| OTHER | N'interprétez pas les informations client. Autorise uniquement le symbole 0, 1, 2 ou 3. |
