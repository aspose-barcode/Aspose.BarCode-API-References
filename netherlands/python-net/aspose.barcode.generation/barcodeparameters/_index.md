---
title: "BarcodeParameters"
second_title: "Aspose.BarCode voor Python via .NET API-referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.generation/barcodeparameters/
---

## BarcodeParameters class

Barcode-generatieparameters.

Het type BarcodeParameters exposeert de volgende leden:
## Properties
| Name | Beschrijving |
| :- | :- |
| x_dimension | x-dimension is de kleinste breedte van de eenheid van BarCode-staven of -spaties.<br/>            Het verhogen hiervan vergroot de totale breedte van de barcode-afbeelding.<br/>            Wordt genegeerd als de eigenschap [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |
| bar_height | Hoogte van de staven van 1D-barcodes in [Unit](/barcode/python-net/aspose.barcode.generation/unit/) waarde.<br/>            Wordt genegeerd als de eigenschap [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation. |
| bar_color | Kleur van de staven.<br/>            Standaardwaarde: Color.Black. |
| padding | Barcode-opvulling.<br/>            Standaardwaarde: 5pt 5pt 5pt 5pt. |
| checksum_always_show | Toon altijd het controlecijfer in de menselijk leesbare tekst voor Code128- en GS1Code128-barcodes. |
| is_checksum_enabled |  |
| throw_exception_when_code_text_incorrect | Alleen voor 1D-barcodes.<br/>            Als de codetext onjuist is en de waarde is ingesteld op true - wordt er een uitzondering gegooid. Anders wordt de codetext gecorrigeerd om te voldoen aan de specificatie van de barcode.<br/>            Een uitzondering wordt altijd gegooid voor: Databar-symbool als de codetext onjuist is.<br/>            Een uitzondering wordt nooit gegooid voor: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128-symbool als de codetext onjuist is. |
| wide_narrow_ratio | Verhouding van brede naar smalle staven.<br/>            Standaardwaarde: 3, dat wil zeggen, brede staven zijn 3 keer zo breed als smalle staven.<br/>            Gebruikt voor ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| code_text_parameters | Codetekstparameters. |
| filled_bars | Haalt of stelt een waarde in die aangeeft of de staven gevuld zijn.<br/>            Alleen voor 1D-barcodes.<br/>            Standaardwaarde: true. |
| bar_width_reduction | Haalt of stelt de reductiewaarde van de staven in die wordt gebruikt om de inktverspreiding tijdens het afdrukken te compenseren.<br/>            Standaardwaarde: 0 |
| postal | Postale parameters. Gebruikt voor Postnet, Planet. |
| patch_code | PatchCode-parameters. |
| australian_post | AustralianPost barcode-parameters. |
| data_bar | Databar-parameters. |
| gs1_composite_bar | GS1 Composite Bar parameters. |
| codablock | Codablock-parameters. |
| data_matrix | DataMatrix-parameters. |
| code_16k | Code16K-parameters. |
| dot_code | DotCode-parameters. |
| itf | ITF-parameters. |
| pdf417 | PDF417 parameters. |
| qr | QR, MicroQR and RectMicroQR parameters. |
| supplement | Supplementaire parameters. Gebruikt voor Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| maxi_code | MaxiCode-parameters. |
| aztec | Aztec-parameters. |
| code128 | Code128-parameters. |
| codabar | Codabar-parameters. |
| coupon | Coupon-parameters. Gebruikt voor UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| han_xin | HanXin parameters. |
| gs1 | GS1-parameters. |

### Zie ook

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

