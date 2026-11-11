---
title: "Klasse BaseGenerationParameters"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.BaseGenerationParameters klasse. Barcode-afbeeldingsgeneratieparameters"
type: docs
weight: 1030
url: /nl/net/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class

Barcode‑afbeeldings‑generatie‑parameters.

```csharp
public class BaseGenerationParameters
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.generation/basegenerationparameters/autosizemode/) { get; set; } | Specificeert de verschillende typen automatische formaatmodi. Standaardwaarde: AutoSizeMode.None. |
| [BackColor](../../aspose.barcode.generation/basegenerationparameters/backcolor/) { get; set; } | Achtergrondkleur van de barcode-afbeelding. Standaardwaarde: Color.White. Zie Color. |
| [Barcode](../../aspose.barcode.generation/basegenerationparameters/barcode/) { get; } | Haalt de [`BarcodeParameters`](../barcodeparameters/) op die alle barcode-eigenschappen bevat. |
| [Border](../../aspose.barcode.generation/basegenerationparameters/border/) { get; } | Haalt de [`BorderParameters`](../borderparameters/) op die alle configuratie-eigenschappen voor de barcode-rand bevat. |
| [CaptionAbove](../../aspose.barcode.generation/basegenerationparameters/captionabove/) { get; } | Bijschrift boven de BarCode-afbeelding. Zie [`CaptionParameters`](../captionparameters/). |
| [CaptionBelow](../../aspose.barcode.generation/basegenerationparameters/captionbelow/) { get; } | Bijschrift onder de BarCode-afbeelding. Zie [`CaptionParameters`](../captionparameters/). |
| [Image](../../aspose.barcode.generation/basegenerationparameters/image/) { get; } | Afbeeldingsparameters. Zie [`ImageParameters`](../imageparameters/). |
| [ImageHeight](../../aspose.barcode.generation/basegenerationparameters/imageheight/) { get; set; } | BarCode-beeldhoogte wanneer de eigenschap [`AutoSizeMode`](./autosizemode/) is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |
| [ImageWidth](../../aspose.barcode.generation/basegenerationparameters/imagewidth/) { get; set; } | BarCode-beeldbreedte wanneer de eigenschap [`AutoSizeMode`](./autosizemode/) is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |
| [Resolution](../../aspose.barcode.generation/basegenerationparameters/resolution/) { get; set; } | Haalt of stelt de resolutie van het BarCode‑beeld in. Eén waarde voor beide dimensies. Standaardwaarde: 96 dpi. |
| [RotationAngle](../../aspose.barcode.generation/basegenerationparameters/rotationangle/) { get; set; } | BarCode-beeldrotatiehoek, gemeten in graden, bv. RotationAngle = 0 of RotationAngle = 360 betekent geen rotatie. Als RotationAngle NIET gelijk is aan 90, 180, 270 of 0, kan dit de moeilijkheid voor de scanner om het beeld te lezen verhogen. Standaardwaarde: 0. |
| [UseAntiAlias](../../aspose.barcode.generation/basegenerationparameters/useantialias/) { get; set; } | Haalt of stelt een waarde in die aangeeft of anti-aliasing-modus wordt gebruikt om het beeld te renderen. |

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


