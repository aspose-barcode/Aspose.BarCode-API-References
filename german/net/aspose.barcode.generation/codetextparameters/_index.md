---
title: "Klasse CodetextParameters"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.CodetextParameters Klasse. Codetext-Parameter"
type: docs
weight: 1160
url: /de/net/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class

Codetext‑Parameter.

```csharp
public class CodetextParameters
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Alignment](../../aspose.barcode.generation/codetextparameters/alignment/) { get; set; } | Liest oder setzt die Ausrichtung des Code-Texts. Standardwert: StringAlignment.Center. |
| [Color](../../aspose.barcode.generation/codetextparameters/color/) { get; set; } | Geben Sie die Farbe des angezeigten CodeText an. Standardwert: Color.Black. |
| [Font](../../aspose.barcode.generation/codetextparameters/font/) { get; } | Geben Sie die Schriftart des angezeigten CodeText an. Standardwert: Arial 5pt regular. Wird ignoriert, wenn FontMode auf FontMode.Auto gesetzt ist. |
| [FontMode](../../aspose.barcode.generation/codetextparameters/fontmode/) { get; set; } | Geben Sie FontMode an. Wenn FontMode auf Auto gesetzt ist, wird die Schriftgröße automatisch basierend auf dem xDimension-Wert berechnet. Es wird empfohlen, FontMode.Auto zu verwenden, insbesondere in AutoSizeMode.Nearest oder AutoSizeMode.Interpolation. Standardwert: FontMode.Auto. |
| [Location](../../aspose.barcode.generation/codetextparameters/location/) { get; set; } | Geben Sie den Anzeigestandort des CodeText an, setzen Sie ihn auf CodeLocation.None, um CodeText auszublenden. Standardwert: CodeLocation.Below für 1D-Barcodes und CodeLocation.None für 2D-Barcodes. |
| [NoWrap](../../aspose.barcode.generation/codetextparameters/nowrap/) { get; set; } | Geben Sie Zeilenumbrüche (Zeilenwechsel) im Text an. Standardwert: false. |
| [Space](../../aspose.barcode.generation/codetextparameters/space/) { get; set; } | Abstand zwischen CodeText und BarCode im [`Unit`](../unit/)-Wert. Standardwert: 2pt. Ignoriert für EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [TwoDDisplayText](../../aspose.barcode.generation/codetextparameters/twoddisplaytext/) { get; set; } | Text, der anstelle von codetext in 2D-Barcodes angezeigt wird. Verwendet für: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/codetextparameters/tostring/)() | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `CodetextParameters` zurück. |

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


