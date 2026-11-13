---
title: "BarcodeParameters"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.generation/barcodeparameters/
---

## BarcodeParameters class

Parametrar för streckkodsgenerering.

Typen BarcodeParameters visar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| x_dimension | x-dimension är den minsta bredden på enheten för BarCode-staplar eller -mellanrum.<br/>            Att öka detta kommer att öka hela streckkodens bildbredd.<br/>            Ignoreras om egenskapen [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) är inställd på AutoSizeMode.Nearest eller AutoSizeMode.Interpolation. |
| bar_height | Höjden på 1D-streckkodernas staplar i [Unit](/barcode/python-net/aspose.barcode.generation/unit/) värde.<br/>            Ignoreras om egenskapen [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) är inställd på AutoSizeMode.Nearest eller AutoSizeMode.Interpolation. |
| bar_color | Stapelfärg.<br/>            Standardvärde: Color.Black. |
| padding | Streckkodens marginaler.<br/>            Standardvärde: 5pt 5pt 5pt 5pt. |
| checksum_always_show | Visa alltid kontrollsiffran i den mänskligt läsbara texten för Code128- och GS1Code128-streckkoder. |
| is_checksum_enabled |  |
| throw_exception_when_code_text_incorrect | Endast för 1D-streckkoder.<br/>            Om kodtexten är felaktig och värdet är satt till true - kommer ett undantag att kastas. Annars kommer kodtexten att korrigeras för att matcha streckkodens specifikation.<br/>            Undantag kommer alltid att kastas för: Databar-symbol om kodtexten är felaktig.<br/>            Undantag kommer aldrig att kastas för: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128-symbol om kodtexten är felaktig. |
| wide_narrow_ratio | Förhållandet mellan breda staplar och smala staplar.<br/>            Standardvärde: 3, det vill säga att breda staplar är 3 gånger så breda som smala staplar.<br/>            Används för ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| code_text_parameters | Codetext-parametrar. |
| filled_bars | Hämtar eller anger ett värde som indikerar om staplarna är fyllda.<br/>            Endast för 1D-streckkoder.<br/>            Standardvärde: true. |
| bar_width_reduction | Hämtar eller anger stapelns reduceringsvärde som används för att kompensera bläckspridning vid utskrift.<br/>            Standardvärde: 0 |
| postal | Postparametrar. Används för Postnet, Planet. |
| patch_code | PatchCode-parametrar. |
| australian_post | AustralianPost‑streckkodparametrar. |
| data_bar | Databar-parametrar. |
| gs1_composite_bar | GS1 Composite Bar-parametrar. |
| codablock | Codablock-parametrar. |
| data_matrix | DataMatrix-parametrar. |
| code_16k | Code16K-parametrar. |
| dot_code | DotCode-parametrar. |
| itf | ITF-parametrar. |
| pdf417 | PDF417-parametrar. |
| qr | QR-, MicroQR- och RectMicroQR-parametrar. |
| supplement | Tilläggsparametrar. Används för Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| maxi_code | MaxiCode-parametrar. |
| aztec | Aztec-parametrar. |
| code128 | Code128-parametrar. |
| codabar | Codabar-parametrar. |
| coupon | Kupongparametrar. Används för UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| han_xin | HanXin-parametrar. |
| gs1 | GS1-parametrar. |

### Se även

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

