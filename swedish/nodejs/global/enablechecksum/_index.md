---
title: "EnableChecksum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Aktivera kontrollsumma under generering för 1D-streckkoder."
type: docs
weight: 250
url: /sv/nodejs/global/enablechecksum/
---

## EnableChecksum

Aktivera kontrollsumma under generering för 1D-streckkoder. Standard behandlas som Ja för symbologier som måste innehålla kontrollsumma, som Nej där kontrollsumma bara är möjlig. Kontrollsumma används aldrig: Codabar. Kontrollsumma är möjlig: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Kontrollsumma används alltid: Övriga symbologier.

## Värden

| Namn | Beskrivning |
| --- | --- |
| DEFAULT | Om kontrollsumma krävs av specifikationen - kommer den att bifogas. |
| YES | Använd alltid kontrollsumma om möjligt. |
| NEJ | Använd inte kontrollsumman. |
