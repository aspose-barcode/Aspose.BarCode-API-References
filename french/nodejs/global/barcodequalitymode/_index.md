---
title: "BarcodeQualityMode"
linktitle: "BarcodeQualityMode"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Mode qui active les méthodes permettant de reconnaître les éléments du code-barres avec la qualité sélectionnée."
type: docs
weight: 80
url: /fr/nodejs/global/barcodequalitymode/
---

## BarcodeQualityMode

Mode qui permet aux méthodes de reconnaître les éléments du code-barres avec la qualité sélectionnée. Un élément de code-barres de qualité inférieure nécessite des méthodes plus lourdes, ce qui ralentit la reconnaissance. Cet exemple montre comment utiliser le mode BarcodeQuality let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Valeurs

| Nom | Description |
| --- | --- |
| SOLIDE | Spécifie une ligne solide. |
| TIRET | Spécifie une ligne composée de tirets. |
| POINT | Spécifie une ligne composée de points. |
| DASH_DOT | Spécifie une ligne composée d'un motif répété tiret-point. |
| DASH_DOT_DOT | Spécifie une ligne composée d'un motif répété tiret-point-point. |
