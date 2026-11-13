---
title: "CodetextParameters"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.generation/codetextparameters/
---

## CodetextParameters class

Codetext-parametrar.

Typen CodetextParameters visar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| two_d_display_text | Text som kommer att visas istället för kodtext i 2D-streckkoder.<br/>            Används för: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| font_mode | Ange FontMode. Om FontMode är inställt på Auto beräknas teckenstorleken automatiskt baserat på xDimension‑värdet.<br/>            Det rekommenderas att använda FontMode.Auto särskilt i AutoSizeMode.Nearest eller AutoSizeMode.Interpolation.<br/>            Standardvärde: FontMode.Auto. |
| font | Ange teckensnittet för den visade CodeText‑en.<br/>            Standardvärde: Arial 5pt regular.<br/>            Ignoreras om FontMode är inställt på FontMode.Auto. |
| space | Avstånd mellan CodeText och BarCode i [Unit](/barcode/python-net/aspose.barcode.generation/unit/) värde.<br/>            Standardvärde: 2pt.<br/>            Ignoreras för EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| justering | Hämtar eller anger justeringen av kodtexten.<br/>            Standardvärde: StringAlignment.Center. |
| färg | Ange färgen som CodeText visas i.<br/>            Standardvärde: Color.Black. |
| position | Ange var CodeText visas, sätt till CodeLocation.None för att dölja CodeText.<br/>            Standardvärde: CodeLocation.Below för 1D-streckkoder och CodeLocation.None för 2D-streckkoder. |
| no_wrap | Ange radbrytningar (linjebrott) i texten.<br/>            Standardvärde: false. |

### Se även

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

