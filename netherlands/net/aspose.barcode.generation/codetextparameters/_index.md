---
title: "Klasse CodetextParameters"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.CodetextParameters klasse. Codetextparameters"
type: docs
weight: 1160
url: /nl/net/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class

Codetekst‑parameters.

```csharp
public class CodetextParameters
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Alignment](../../aspose.barcode.generation/codetextparameters/alignment/) { get; set; } | Haalt de uitlijning van de code-tekst op of stelt deze in. Standaardwaarde: StringAlignment.Center. |
| [Color](../../aspose.barcode.generation/codetextparameters/color/) { get; set; } | Specificeer de kleur van de weergegeven CodeText. Standaardwaarde: Color.Black. |
| [Font](../../aspose.barcode.generation/codetextparameters/font/) { get; } | Specificeer het lettertype van de weergegeven CodeText. Standaardwaarde: Arial 5pt regular. Genegeerd als FontMode is ingesteld op FontMode.Auto. |
| [FontMode](../../aspose.barcode.generation/codetextparameters/fontmode/) { get; set; } | Specificeer FontMode. Als FontMode is ingesteld op Auto, wordt de lettergrootte automatisch berekend op basis van de xDimension-waarde. Het wordt aanbevolen om FontMode.Auto te gebruiken, vooral in AutoSizeMode.Nearest of AutoSizeMode.Interpolation. Standaardwaarde: FontMode.Auto. |
| [Location](../../aspose.barcode.generation/codetextparameters/location/) { get; set; } | Specificeer de weergave van de CodeText-locatie, stel in op CodeLocation.None om CodeText te verbergen. Standaardwaarde: CodeLocation.Below voor 1D-barcode en CodeLocation.None voor 2D-barcode. |
| [NoWrap](../../aspose.barcode.generation/codetextparameters/nowrap/) { get; set; } | Geef woordomslagen (regeleinden) binnen de tekst op. Standaardwaarde: false. |
| [Space](../../aspose.barcode.generation/codetextparameters/space/) { get; set; } | Ruimte tussen de CodeText en de BarCode in [`Unit`](../unit/) waarde. Standaardwaarde: 2pt. Genegeerd voor EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [TwoDDisplayText](../../aspose.barcode.generation/codetextparameters/twoddisplaytext/) { get; set; } | Tekst die wordt weergegeven in plaats van codetext in 2D-barcode. Gebruikt voor: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/codetextparameters/tostring/)() | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze `CodetextParameters`. |

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


