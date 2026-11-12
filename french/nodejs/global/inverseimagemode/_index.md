---
title: "InverseImageMode"
linktitle: "InverseImageMode"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres sur des images aux couleurs inversées (luminance)."
type: docs
weight: 370
url: /fr/nodejs/global/inverseimagemode/
---

## InverseImageMode

Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres sur des images aux couleurs inversées (luminance). Cet exemple montre comment utiliser le mode InverseImage let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Valeurs

| Nom | Description |
| --- | --- |
| NONE | Pas de bordure entourant le code-barres |
| CADRE | CADRE entourant le code-barres |
| BARRE | Deux barres horizontales entourant le code-barres |
| FRAME_OUT | CADRE entourant le code-barres |
| BAR_OUT | Deux barres horizontales entourant le code-barres |
