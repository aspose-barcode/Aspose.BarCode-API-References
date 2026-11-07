---
title: "Aspose::BarCode::Generation::BarcodeParameters class"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::Generation::BarcodeParameters class. Barcode-generatieparameters in C++."
type: docs
weight: 500
url: /nl/cpp/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class


Barcode‑generatieparameters.

```cpp
class BarcodeParameters : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_AustralianPost](./get_australianpost/)() const | AustralianPost-barcodeparameters. |
| [get_Aztec](./get_aztec/)() const | Aztec-parameters. |
| [get_BarColor](./get_barcolor/)() const | Kleur van de balken. Standaardwaarde: Color.Black. |
| [get_BarHeight](./get_barheight/)() const | Hoogte van de balken van 1D-streepjescodes in [Unit](../unit/) waarde. Genegeerd als de eigenschap [BaseGenerationParameters::AutoSizeMode](../) is ingesteld op [AutoSizeMode.Nearest](../autosizemode/) of [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_BarWidthReduction](./get_barwidthreduction/)() const | Haalt op of stelt de balkreductiewaarde in die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren. Standaardwaarde: 0 |
| [get_ChecksumAlwaysShow](./get_checksumalwaysshow/)() const | Toon altijd het controlecijfer in de menselijk leesbare tekst voor Code128- en GS1Code128-barcodes. |
| [get_Codabar](./get_codabar/)() const | Codabar-parameters. |
| [get_Codablock](./get_codablock/)() const | Codablock-parameters. |
| [get_Code128](./get_code128/)() const | Code128-parameters. |
| [get_Code16K](./get_code16k/)() const | Code16K-parameters. |
| [get_CodeTextParameters](./get_codetextparameters/)() const | Codetext-parameters. |
| [get_Coupon](./get_coupon/)() const | Coupon-parameters. Gebruikt voor UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [get_DataBar](./get_databar/)() const | Databar-parameters. |
| [get_DataMatrix](./get_datamatrix/)() const | DataMatrix-parameters. |
| [get_DotCode](./get_dotcode/)() const | DotCode-parameters. |
| [get_FilledBars](./get_filledbars/)() const | Geeft een waarde die aangeeft of de staven gevuld zijn. Alleen voor 1D-barcodes. Standaardwaarde: true. |
| [get_GS1](./get_gs1/)() const | GS1-parameters. |
| [get_GS1CompositeBar](./get_gs1compositebar/)() const | GS1 Composite Bar-parameters. |
| [get_HanXin](./get_hanxin/)() const | HanXin-parameters. |
| [get_IsChecksumEnabled](./get_ischecksumenabled/)() const |  |
| [get_ITF](./get_itf/)() const | ITF-parameters. |
| [get_MaxiCode](./get_maxicode/)() const | MaxiCode-parameters. |
| [get_Padding](./get_padding/)() const | Barcode-opvulling. Standaardwaarde: 5pt 5pt 5pt 5pt. |
| [get_PatchCode](./get_patchcode/)() const | PatchCode-parameters. |
| [get_Pdf417](./get_pdf417/)() const | PDF417-parameters. |
| [get_Postal](./get_postal/)() const | Postparameters. Gebruikt voor Postnet, Planet. |
| [get_QR](./get_qr/)() const | QR-, MicroQR- en RectMicroQR-parameters. |
| [get_Supplement](./get_supplement/)() const | Supplementaire parameters. Gebruikt voor Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [get_ThrowExceptionWhenCodeTextIncorrect](./get_throwexceptionwhencodetextincorrect/)() const | Alleen voor 1D-barcodes. Als de codetekst onjuist is en de waarde is ingesteld op true, wordt er een uitzondering gegooid. Anders wordt de codetekst gecorrigeerd om te voldoen aan de specificatie van de barcode. Een uitzondering wordt altijd gegooid voor: Databar-symbool als de codetekst onjuist is. Een uitzondering wordt nooit gegooid voor: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128-symbool als de codetekst onjuist is. |
| [get_WideNarrowRatio](./get_widenarrowratio/)() const | Verhouding brede staven tot smalle staven. Standaardwaarde: 3, dat wil zeggen, brede staven zijn 3 keer zo breed als smalle staven. Gebruikt voor ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [get_XDimension](./get_xdimension/)() const | x-dimension is de kleinste breedte van de eenheid van [BarCode](../../aspose.barcode/) staven of spaties. Het vergroten hiervan zal de totale breedte van de barcode-afbeelding vergroten. Genegeerd als de eigenschap [BaseGenerationParameters::AutoSizeMode](../) is ingesteld op [AutoSizeMode.Nearest](../autosizemode/) of [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarColor](./set_barcolor/)(System::Drawing::Color) | Kleur van de balken. Standaardwaarde: Color.Black. |
| [set_BarHeight](./set_barheight/)(System::SharedPtr\<Unit\>) | Hoogte van de balken van 1D-streepjescodes in [Unit](../unit/) waarde. Genegeerd als de eigenschap [BaseGenerationParameters::AutoSizeMode](../) is ingesteld op [AutoSizeMode.Nearest](../autosizemode/) of [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarWidthReduction](./set_barwidthreduction/)(System::SharedPtr\<Unit\>) | Haalt op of stelt de balkreductiewaarde in die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren. Standaardwaarde: 0 |
| [set_ChecksumAlwaysShow](./set_checksumalwaysshow/)(bool) | Toon altijd het controlecijfer in de menselijk leesbare tekst voor Code128- en GS1Code128-barcodes. |
| [set_FilledBars](./set_filledbars/)(bool) | Stelt een waarde in die aangeeft of de staven gevuld zijn. Alleen voor 1D-barcodes. Standaardwaarde: true. |
| [set_GS1CompositeBar](./set_gs1compositebar/)(System::SharedPtr\<GS1CompositeBarParameters\>) | GS1 Composite Bar-parameters. |
| [set_IsChecksumEnabled](./set_ischecksumenabled/)(EnableChecksum) |  |
| [set_ThrowExceptionWhenCodeTextIncorrect](./set_throwexceptionwhencodetextincorrect/)(bool) | Alleen voor 1D-barcodes. Als de codetekst onjuist is en de waarde is ingesteld op true, wordt er een uitzondering gegooid. Anders wordt de codetekst gecorrigeerd om te voldoen aan de specificatie van de barcode. Een uitzondering wordt altijd gegooid voor: Databar-symbool als de codetekst onjuist is. Een uitzondering wordt nooit gegooid voor: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128-symbool als de codetekst onjuist is. |
| [set_WideNarrowRatio](./set_widenarrowratio/)(float) | Verhouding brede staven tot smalle staven. Standaardwaarde: 3, dat wil zeggen, brede staven zijn 3 keer zo breed als smalle staven. Gebruikt voor ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [set_XDimension](./set_xdimension/)(System::SharedPtr\<Unit\>) | x-dimension is de kleinste breedte van de eenheid van [BarCode](../../aspose.barcode/) staven of spaties. Het vergroten hiervan zal de totale breedte van de barcode-afbeelding vergroten. Genegeerd als de eigenschap [BaseGenerationParameters::AutoSizeMode](../) is ingesteld op [AutoSizeMode.Nearest](../autosizemode/) of [AutoSizeMode.Interpolation](../autosizemode/). |
## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
