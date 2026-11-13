---
title: "ComplexBackgroundMode"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Läge som aktiverar eller inaktiverar ytterligare igenkänning av färgstreckkoder på färgbilder."
type: docs
weight: 160
url: /sv/nodejs/global/complexbackgroundmode/
---

## ComplexBackgroundMode

Läge som aktiverar eller inaktiverar ytterligare igenkänning av färgade streckkoder på färgbilder. Detta exempel visar hur man använder ComplexBackground mode let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Värden

| Namn | Beskrivning |
| --- | --- |
| C_TABLE | Använd C_TABLE för att tolka kundinformationen. Tillåter A..Z, a..z, 1..9, mellanslag och #-symbol. |
| N_TABLE | Använd N_TABLE för att tolka kundinformationen. Tillåter siffror. |
| OTHER | Tolkar inte kundinformationen. Tillåter endast 0, 1, 2 eller 3 symboler. |
