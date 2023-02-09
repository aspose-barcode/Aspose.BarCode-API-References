---
title: CodetextParameters
second_title: Aspose.BarCode voor .NET API-referentie
description: Codetekstparameters.
type: docs
weight: 840
url: /nl/net/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class

Codetekstparameters.

```csharp
public class CodetextParameters
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Alignment](../../aspose.barcode.generation/codetextparameters/alignment/) { get; set; } | Haalt of stelt de uitlijning van de codetekst in. Standaardwaarde: StringAlignment.Center. |
| [Color](../../aspose.barcode.generation/codetextparameters/color/) { get; set; } | Specificeer de weergegeven CodeText's Color. Standaardwaarde: Color.Black. |
| [Font](../../aspose.barcode.generation/codetextparameters/font/) { get; } | Geef het weergegeven CodeText-lettertype op. Standaardwaarde: Arial 5pt regular. Genegeerd als FontMode is ingesteld op FontMode.Auto. |
| [FontMode](../../aspose.barcode.generation/codetextparameters/fontmode/) { get; set; } | Geef FontMode op. Als FontMode is ingesteld op Auto, wordt de lettergrootte automatisch berekend op basis van xDimension-waarde. Het wordt aanbevolen om FontMode.Auto te gebruiken, vooral in AutoSizeMode.Nearest of AutoSizeMode.Interpolation. Standaardwaarde: FontMode.Auto. |
| [Location](../../aspose.barcode.generation/codetextparameters/location/) { get; set; } | Geef de weergegeven CodeText-locatie op, stel in op CodeLocation.None om CodeText. te verbergen Standaardwaarde: CodeLocation.Below voor 1D-barcodes en CodeLocation.None voor 2D-barcodes. |
| [NoWrap](../../aspose.barcode.generation/codetextparameters/nowrap/) { get; set; } | Specificeer woordterugloop (regeleinden) binnen tekst. Standaardwaarde: false. |
| [Space](../../aspose.barcode.generation/codetextparameters/space/) { get; set; } | Ruimte tussen de CodeText en de BarCode in[`Unit`](../unit/)value. Standaardwaarde: 2pt. Genegeerd voor EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [TwoDDisplayText](../../aspose.barcode.generation/codetextparameters/twoddisplaytext/) { get; set; } | Tekst die wordt weergegeven in plaats van codetekst in 2D-barcodes. Gebruikt voor: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/codetextparameters/tostring/)() | Retourneert hiervan een door mensen leesbare tekenreeksrepresentatie`CodetextParameters` . |

### Zie ook

* naamruimte [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->