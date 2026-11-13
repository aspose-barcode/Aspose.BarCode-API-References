---
title: "CodetextParameters"
second_title: "Aspose.BarCode für Python über .NET API-Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.generation/codetextparameters/
---

## CodetextParameters class

Codetext‑Parameter.

Der Typ CodetextParameters stellt die folgenden Mitglieder bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| two_d_display_text | Text, der anstelle von Codetext in 2D-Strichcodes angezeigt wird.<br/>            Verwendet für: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| font_mode | Geben Sie FontMode an. Wenn FontMode auf Auto gesetzt ist, wird die Schriftgröße automatisch basierend auf dem xDimension-Wert berechnet.<br/>            Es wird empfohlen, FontMode.Auto zu verwenden, insbesondere in AutoSizeMode.Nearest oder AutoSizeMode.Interpolation.<br/>            Standardwert: FontMode.Auto. |
| font | Geben Sie die Schrift des angezeigten CodeText an.<br/>            Standardwert: Arial 5pt regular.<br/>            Wird ignoriert, wenn FontMode auf FontMode.Auto gesetzt ist. |
| space | Abstand zwischen CodeText und BarCode im [Unit](/barcode/python-net/aspose.barcode.generation/unit/) Wert.<br/>            Standardwert: 2pt.<br/>            Wird ignoriert für EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| Ausrichtung | Liest oder setzt die Ausrichtung des Code-Textes.<br/>            Standardwert: StringAlignment.Center. |
| Farbe | Gibt die anzuzeigende Farbe des CodeText an.<br/>            Standardwert: Color.Black. |
| Position | Gibt die Position des angezeigten CodeText an, setzen Sie auf CodeLocation.None, um den CodeText zu verbergen.<br/>            Standardwert: CodeLocation.Below für 1D-Barcodes und CodeLocation.None für 2D-Barcodes. |
| no_wrap | Gibt Wortumbrüche (Zeilenumbrüche) im Text an.<br/>            Standardwert: false. |

### Siehe auch

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

