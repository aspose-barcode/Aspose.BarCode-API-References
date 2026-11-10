---
title: "Klasse CodetextParametersUI"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Windows.Forms.CodetextParametersUI Klasse. Codetext-Parameter"
type: docs
weight: 1820
url: /de/net/aspose.barcode.windows.forms/codetextparametersui/
---
## CodetextParametersUI class

Codetext‑Parameter.

```csharp
public class CodetextParametersUI
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Alignment](../../aspose.barcode.windows.forms/codetextparametersui/alignment/) { get; set; } | Liest oder setzt die Ausrichtung des Code-Texts. Standardwert: StringAlignment.Center. |
| [Color](../../aspose.barcode.windows.forms/codetextparametersui/color/) { get; set; } | Geben Sie die Farbe des angezeigten CodeText an. Standardwert: Color.Black. |
| [Font](../../aspose.barcode.windows.forms/codetextparametersui/font/) { get; set; } | Geben Sie die Schriftart des angezeigten CodeText an. Standardwert: Arial 5pt regular. Wird ignoriert, wenn FontMode auf FontMode.Auto gesetzt ist. |
| [FontMode](../../aspose.barcode.windows.forms/codetextparametersui/fontmode/) { get; set; } | Geben Sie FontMode an. Wenn FontMode auf Auto gesetzt ist, wird die Schriftgröße automatisch basierend auf dem xDimension-Wert berechnet. Es wird empfohlen, FontMode.Auto zu verwenden, insbesondere in AutoSizeMode.Nearest oder AutoSizeMode.Interpolation. Standardwert: FontMode.Auto. |
| [Location](../../aspose.barcode.windows.forms/codetextparametersui/location/) { get; set; } | Geben Sie den Anzeigestandort des CodeText an, setzen Sie ihn auf CodeLocation.None, um CodeText auszublenden. Standardwert: CodeLocation.Below für 1D-Barcodes und CodeLocation.None für 2D-Barcodes. |
| [Space](../../aspose.barcode.windows.forms/codetextparametersui/space/) { get; } | Abstand zwischen CodeText und BarCode im [`Unit`](../../aspose.barcode.generation/unit/)-Wert. Standardwert: 2pt. Ignoriert für EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [TwoDDisplayText](../../aspose.barcode.windows.forms/codetextparametersui/twoddisplaytext/) { get; set; } | Text, der anstelle von codetext in 2D-Barcodes angezeigt wird. Verwendet für: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/codetextparametersui/tostring/)() | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [`CodetextParameters`](../../aspose.barcode.generation/codetextparameters/) zurück. |

### Siehe auch

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


