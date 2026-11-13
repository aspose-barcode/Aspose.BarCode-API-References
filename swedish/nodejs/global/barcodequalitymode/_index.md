---
title: "BarcodeQualityMode"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Läge som möjliggör metoder för att känna igen streckkodelement med den valda kvaliteten."
type: docs
weight: 80
url: /sv/nodejs/global/barcodequalitymode/
---

## BarcodeQualityMode

Läge som möjliggör metoder att känna igen streckkodselement med den valda kvaliteten. Streckkodselement med lägre kvalitet kräver hårdare metoder vilket saktar ner igenkänningen. Detta exempel visar hur man använder BarcodeQuality-läget let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Värden

| Namn | Beskrivning |
| --- | --- |
| SOLID | Anger en solid linje. |
| DASH | Anger en linje bestående av streck. |
| DOT | Anger en linje bestående av punkter. |
| DASH_DOT | Anger en linje bestående av ett upprepande mönster av streck-punkt. |
| DASH_DOT_DOT | Anger en linje bestående av ett upprepande mönster av streck-punkt-punkt. |
