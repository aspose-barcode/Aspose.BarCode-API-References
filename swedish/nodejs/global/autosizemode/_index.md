---
title: "AutoSizeMode"
linktitle: "AutoSizeMode"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Anger de olika typerna av automatiska storleksinställningslägen."
type: docs
weight: 20
url: /sv/nodejs/global/autosizemode/
---

## AutoSizeMode

Anger de olika typerna av automatiska storlekslägen. Standardvärdet är AutoSizeMode.NONE.

## Värden

| Namn | Beskrivning |
| --- | --- |
| INGEN | Automatisk storleksändring är inaktiverad. Standardvärde. |
| NEAREST | Streckkoden ändras till närmaste lägsta möjliga storlek som specificeras av egenskaperna BarCodeWidth och BarCodeHeight. |
| INTERPOLATION | Ändrar streckkoden till angiven storlek med liten skalning men den kan bli något skadad i vissa fall på grund av användning av interpolation för skalning. Storleken kan specificeras av egenskaperna BarcodeGenerator.BarCodeWidth och BarcodeGenerator.BarCodeHeight. |
