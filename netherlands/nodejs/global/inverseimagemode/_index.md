---
title: "InverseImageMode"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt."
type: docs
weight: 370
url: /nl/nodejs/global/inverseimagemode/
---

## InverseImageMode

Modus die extra herkenning van streepjescodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt. Deze voorbeeld toont hoe de InverseImage-modus te gebruiken let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Waarden

| Naam | Beschrijving |
| --- | --- |
| NONE | GEEN rand die de barcode omsluit |
| FRAME | FRAME die de barcode omsluit |
| BAR | Twee horizontale balken die de barcode omsluiten |
| FRAME_OUT | FRAME die de barcode omsluit |
| BAR_OUT | Twee horizontale balken die de barcode omsluiten |
