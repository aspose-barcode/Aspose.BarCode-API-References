---
title: "InverseImageMode"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Läge som aktiverar eller inaktiverar ytterligare igenkänning av streckkoder på bilder med inverterade färger (luminans)."
type: docs
weight: 370
url: /sv/nodejs/global/inverseimagemode/
---

## InverseImageMode

Läge som aktiverar eller inaktiverar ytterligare igenkänning av streckkoder på bilder med inverterade färger (luminans). Detta exempel visar hur man använder InverseImage-läget let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Värden

| Namn | Beskrivning |
| --- | --- |
| INGEN | Ingen ram som omger streckkoden |
| FRAME | FRAME som omger streckkoden |
| BAR | Två horisontella staplar som omger streckkoden |
| FRAME_OUT | FRAME som omger streckkoden |
| BAR_OUT | Två horisontella staplar som omger streckkoden |
