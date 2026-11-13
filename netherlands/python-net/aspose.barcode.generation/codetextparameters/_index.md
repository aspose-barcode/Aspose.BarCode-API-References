---
title: "CodetextParameters"
second_title: "Aspose.BarCode voor Python via .NET API-referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.generation/codetextparameters/
---

## CodetextParameters class

Codetekstparameters.

Het type CodetextParameters maakt de volgende leden beschikbaar:
## Properties
| Name | Beschrijving |
| :- | :- |
| two_d_display_text | Tekst die wordt weergegeven in plaats van codetext in 2D-streepjescodes.<br/>            Gebruikt voor: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| font_mode | Specificeer FontMode. Als FontMode is ingesteld op Auto, wordt de lettergrootte automatisch berekend op basis van de xDimension-waarde.<br/>            Het wordt aanbevolen FontMode.Auto te gebruiken, vooral in AutoSizeMode.Nearest of AutoSizeMode.Interpolation.<br/>            Standaardwaarde: FontMode.Auto. |
| font | Specificeer het lettertype van de weergegeven CodeText.<br/>            Standaardwaarde: Arial 5pt regular.<br/>            Genegeerd als FontMode is ingesteld op FontMode.Auto. |
| space | Ruimte tussen de CodeText en de BarCode in [Unit](/barcode/python-net/aspose.barcode.generation/unit/) waarde.<br/>            Standaardwaarde: 2pt.<br/>            Genegeerd voor EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| uitlijning | Haalt de uitlijning van de code-tekst op of stelt deze in.<br/>            Standaardwaarde: StringAlignment.Center. |
| kleur | Geef de kleur van de weergegeven CodeText op.<br/>            Standaardwaarde: Color.Black. |
| locatie | Geef de locatie van de weergegeven CodeText op, stel in op CodeLocation.None om CodeText te verbergen.<br/>            Standaardwaarde: CodeLocation.Below voor 1D-barcodes en CodeLocation.None voor 2D-barcodes. |
| no_wrap | Geef woordomslagen (regeleinden) binnen de tekst op.<br/>            Standaardwaarde: false. |

### Zie ook

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

