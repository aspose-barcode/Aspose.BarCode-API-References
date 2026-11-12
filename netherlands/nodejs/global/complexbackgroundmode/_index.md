---
title: "ComplexBackgroundMode"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Modus die extra herkenning van gekleurde barcodes op kleurafbeeldingen in- of uitschakelt."
type: docs
weight: 160
url: /nl/nodejs/global/complexbackgroundmode/
---

## ComplexBackgroundMode

Modus die extra herkenning van gekleurde barcodes op gekleurde afbeeldingen in- of uitschakelt. Deze voorbeeld toont hoe je ComplexBackground mode gebruikt let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Waarden

| Naam | Beschrijving |
| --- | --- |
| C_TABLE | Gebruik C_TABLE om de klantinformatie te interpreteren. Staat A..Z, a..z, 1..9, spatie en # toe. |
| N_TABLE | Gebruik N_TABLE om de klantinformatie te interpreteren. Staat cijfers toe. |
| OTHER | Interpreteer de klantinformatie niet. Staat alleen het symbool 0, 1, 2 of 3 toe. |
