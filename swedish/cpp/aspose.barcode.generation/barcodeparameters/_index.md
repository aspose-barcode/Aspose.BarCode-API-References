---
title: "Aspose::BarCode::Generation::BarcodeParameters klass"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::BarcodeParameters-klass. Parametrar för streckkodsgenerering i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class


Parametrar för streckkodsgenerering.

```cpp
class BarcodeParameters : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AustralianPost](./get_australianpost/)() const | AustralianPost streckkodparametrar. |
| [get_Aztec](./get_aztec/)() const | Aztec-parametrar. |
| [get_BarColor](./get_barcolor/)() const | Streckens färg. Standardvärde: Color.Black. |
| [get_BarHeight](./get_barheight/)() const | Höjd på 1D-streckkods staplar i [Enhet](../unit/) värde. Ignoreras om egenskapen [BaseGenerationParameters::AutoSizeMode](../) är satt till [AutoSizeMode.Nearest](../autosizemode/) eller [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_BarWidthReduction](./get_barwidthreduction/)() const | Hämtar eller anger värdet för stapelreduktion som används för att kompensera bläckspridning vid utskrift. Standardvärde: 0 |
| [get_ChecksumAlwaysShow](./get_checksumalwaysshow/)() const | Visa alltid kontrollsiffran i den mänskligt läsbara texten för Code128- och GS1Code128-streckkoder. |
| [get_Codabar](./get_codabar/)() const | Parametrar för Codabar. |
| [get_Codablock](./get_codablock/)() const | Parametrar för Codablock. |
| [get_Code128](./get_code128/)() const | Parametrar för Code128. |
| [get_Code16K](./get_code16k/)() const | Parametrar för Code16K. |
| [get_CodeTextParameters](./get_codetextparameters/)() const | Parametrar för kodtext. |
| [get_Coupon](./get_coupon/)() const | Kupongparametrar. Används för UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [get_DataBar](./get_databar/)() const | Parametrar för Databar. |
| [get_DataMatrix](./get_datamatrix/)() const | Parametrar för DataMatrix. |
| [get_DotCode](./get_dotcode/)() const | Parametrar för DotCode. |
| [get_FilledBars](./get_filledbars/)() const | Hämtar ett värde som indikerar om staplar är fyllda. Endast för 1D-streckkoder. Standardvärde: true. |
| [get_GS1](./get_gs1/)() const | Parametrar för GS1. |
| [get_GS1CompositeBar](./get_gs1compositebar/)() const | GS1 Composite Bar-parametrar. |
| [get_HanXin](./get_hanxin/)() const | HanXin-parametrar. |
| [get_IsChecksumEnabled](./get_ischecksumenabled/)() const |  |
| [get_ITF](./get_itf/)() const | Parametrar för ITF. |
| [get_MaxiCode](./get_maxicode/)() const | Parametrar för MaxiCode. |
| [get_Padding](./get_padding/)() const | Streckkodspaddningar. Standardvärde: 5pt 5pt 5pt 5pt. |
| [get_PatchCode](./get_patchcode/)() const | Parametrar för PatchCode. |
| [get_Pdf417](./get_pdf417/)() const | PDF417-parametrar. |
| [get_Postal](./get_postal/)() const | Postparametrar. Används för Postnet, Planet. |
| [get_QR](./get_qr/)() const | QR-, MicroQR- och RectMicroQR-parametrar. |
| [get_Supplement](./get_supplement/)() const | Komplementära parametrar. Används för Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [get_ThrowExceptionWhenCodeTextIncorrect](./get_throwexceptionwhencodetextincorrect/)() const | Endast för 1D-streckkoder. Om codetext är felaktig och värdet är satt till true – ett undantag kommer att kastas. Annars kommer codetext att korrigeras för att matcha streckkodens specifikation. Undantag kommer alltid att kastas för: Databar-symbologi om codetext är felaktig. Undantag kommer aldrig att kastas för: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128-symbologi om codetext är felaktig. |
| [get_WideNarrowRatio](./get_widenarrowratio/)() const | Förhållandet mellan breda staplar och smala staplar. Standardvärde: 3, det vill säga att breda staplar är 3 gånger så breda som smala staplar. Används för ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [get_XDimension](./get_xdimension/)() const | x-dimension är den minsta bredden på enheten av [BarCode](../../aspose.barcode/) staplar eller mellanslag. Att öka detta kommer att öka hela streckkodens bildbredd. Ignoreras om egenskapen [BaseGenerationParameters::AutoSizeMode](../) är satt till [AutoSizeMode.Nearest](../autosizemode/) eller [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarColor](./set_barcolor/)(System::Drawing::Color) | Streckens färg. Standardvärde: Color.Black. |
| [set_BarHeight](./set_barheight/)(System::SharedPtr\<Unit\>) | Höjd på 1D-streckkods staplar i [Enhet](../unit/) värde. Ignoreras om egenskapen [BaseGenerationParameters::AutoSizeMode](../) är satt till [AutoSizeMode.Nearest](../autosizemode/) eller [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarWidthReduction](./set_barwidthreduction/)(System::SharedPtr\<Unit\>) | Hämtar eller anger värdet för stapelreduktion som används för att kompensera bläckspridning vid utskrift. Standardvärde: 0 |
| [set_ChecksumAlwaysShow](./set_checksumalwaysshow/)(bool) | Visa alltid kontrollsiffran i den mänskligt läsbara texten för Code128- och GS1Code128-streckkoder. |
| [set_FilledBars](./set_filledbars/)(bool) | Anger ett värde som indikerar om staplar är fyllda. Endast för 1D-streckkoder. Standardvärde: true. |
| [set_GS1CompositeBar](./set_gs1compositebar/)(System::SharedPtr\<GS1CompositeBarParameters\>) | GS1 Composite Bar-parametrar. |
| [set_IsChecksumEnabled](./set_ischecksumenabled/)(EnableChecksum) |  |
| [set_ThrowExceptionWhenCodeTextIncorrect](./set_throwexceptionwhencodetextincorrect/)(bool) | Endast för 1D-streckkoder. Om codetext är felaktig och värdet är satt till true – ett undantag kommer att kastas. Annars kommer codetext att korrigeras för att matcha streckkodens specifikation. Undantag kommer alltid att kastas för: Databar-symbologi om codetext är felaktig. Undantag kommer aldrig att kastas för: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128-symbologi om codetext är felaktig. |
| [set_WideNarrowRatio](./set_widenarrowratio/)(float) | Förhållandet mellan breda staplar och smala staplar. Standardvärde: 3, det vill säga att breda staplar är 3 gånger så breda som smala staplar. Används för ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [set_XDimension](./set_xdimension/)(System::SharedPtr\<Unit\>) | x-dimension är den minsta bredden på enheten av [BarCode](../../aspose.barcode/) staplar eller mellanslag. Att öka detta kommer att öka hela streckkodens bildbredd. Ignoreras om egenskapen [BaseGenerationParameters::AutoSizeMode](../) är satt till [AutoSizeMode.Nearest](../autosizemode/) eller [AutoSizeMode.Interpolation](../autosizemode/). |
## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
