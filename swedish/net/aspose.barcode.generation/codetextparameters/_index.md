---
title: CodetextParameters
second_title: Aspose.BarCode för .NET API-referens
description: Kodtextparametrar.
type: docs
weight: 630
url: /sv/net/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class

Kodtextparametrar.

```csharp
public class CodetextParameters
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Alignment](../../aspose.barcode.generation/codetextparameters/alignment) { get; set; } | Hämtar eller ställer in justeringen av kodtexten. Standardvärde: StringAlignment.Center. |
| [Color](../../aspose.barcode.generation/codetextparameters/color) { get; set; } | Ange kodtextens färg. Standardvärde: Color.Black. |
| [Font](../../aspose.barcode.generation/codetextparameters/font) { get; } | Ange kodtextens teckensnitt som visas. Standardvärde: Arial 5pt regular. Ignoreras om FontMode är inställt på FontMode.Auto. |
| [FontMode](../../aspose.barcode.generation/codetextparameters/fontmode) { get; set; } | Ange FontMode. Om FontMode är inställt på Auto, kommer teckenstorleken att beräknas automatiskt baserat på xDimension value. Det rekommenderas att använda FontMode.Auto, särskilt i AutoSizeMode.Nearest eller AutoSizeMode.Interpolation. Standardvärde: FontMode.Auto. |
| [Location](../../aspose.barcode.generation/codetextparameters/location) { get; set; } | Ange kodtextplatsen som visas, inställd på CodeLocation.None för att dölja CodeText. Standardvärde: CodeLocation.Below. |
| [NoWrap](../../aspose.barcode.generation/codetextparameters/nowrap) { get; set; } | Ange radbrytningar (radbrytningar) i text. Standardvärde: false. |
| [Space](../../aspose.barcode.generation/codetextparameters/space) { get; set; } | Mellanrum mellan CodeText och streckkoden i[`Unit`](../unit)value. Standardvärde: 2pt. Ignoreras för EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [TwoDDisplayText](../../aspose.barcode.generation/codetextparameters/twoddisplaytext) { get; set; } | Text som kommer att visas istället för kodtext i 2D streckkoder. Används för: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/codetextparameters/tostring)() | Returnerar en mänsklig läsbar strängrepresentation av detta[`CodetextParameters`](../codetextparameters) . |

### Se även

* namnutrymme [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* hopsättning [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->