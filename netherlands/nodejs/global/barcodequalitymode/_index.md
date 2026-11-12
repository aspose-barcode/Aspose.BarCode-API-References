---
title: "BarcodeQualityMode"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Modus die methoden inschakelt om barcode‑elementen met de geselecteerde kwaliteit te herkennen."
type: docs
weight: 80
url: /nl/nodejs/global/barcodequalitymode/
---

## BarcodeQualityMode

Modus die methoden in staat stelt barcode‑elementen te herkennen met de geselecteerde kwaliteit. Een barcode‑element met lagere kwaliteit vereist meer intensieve methoden, wat de herkenning vertraagt. Deze voorbeeld laat zien hoe de BarcodeQuality‑modus te gebruiken is let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Waarden

| Naam | Beschrijving |
| --- | --- |
| SOLID | Specificeert een solide lijn. |
| DASH | Specificeert een lijn bestaande uit streepjes. |
| DOT | Specificeert een lijn bestaande uit punten. |
| DASH_DOT | Specificeert een lijn bestaande uit een herhalend patroon van streep-punt. |
| DASH_DOT_DOT | Specificeert een lijn bestaande uit een herhalend patroon van streep-punt-punt. |
