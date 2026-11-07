---
title: "Aspose::BarCode::Generation::BarcodeParameters Klasse"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::BarcodeParameters Klasse. Barcode-Generierungsparameter in C++."
type: docs
weight: 500
url: /de/cpp/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class


Barcode-Generierungsparameter.

```cpp
class BarcodeParameters : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_AustralianPost](./get_australianpost/)() const | AustralianPost-Barcode-Parameter. |
| [get_Aztec](./get_aztec/)() const | Aztec-Parameter. |
| [get_BarColor](./get_barcolor/)() const | Farbe der Balken. Standardwert: Color.Black. |
| [get_BarHeight](./get_barheight/)() const | Höhe der Balken von 1D-Barcodes im [Unit](../unit/)-Wert. Ignoriert, wenn die Eigenschaft [BaseGenerationParameters::AutoSizeMode](../) auf [AutoSizeMode.Nearest](../autosizemode/) oder [AutoSizeMode.Interpolation](../autosizemode/) gesetzt ist. |
| [get_BarWidthReduction](./get_barwidthreduction/)() const | Liest oder setzt den Reduktionswert der Balken, der verwendet wird, um die Tintenverbreitung beim Drucken auszugleichen. Standardwert: 0 |
| [get_ChecksumAlwaysShow](./get_checksumalwaysshow/)() const | Checksumme immer im menschenlesbaren Text für Code128- und GS1Code128-Barcodes anzeigen. |
| [get_Codabar](./get_codabar/)() const | Codabar-Parameter. |
| [get_Codablock](./get_codablock/)() const | Codablock-Parameter. |
| [get_Code128](./get_code128/)() const | Code128-Parameter. |
| [get_Code16K](./get_code16k/)() const | Code16K-Parameter. |
| [get_CodeTextParameters](./get_codetextparameters/)() const | Codetext-Parameter. |
| [get_Coupon](./get_coupon/)() const | Coupon-Parameter. Verwendet für UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [get_DataBar](./get_databar/)() const | Databar-Parameter. |
| [get_DataMatrix](./get_datamatrix/)() const | DataMatrix-Parameter. |
| [get_DotCode](./get_dotcode/)() const | DotCode-Parameter. |
| [get_FilledBars](./get_filledbars/)() const | Gibt einen Wert zurück, der angibt, ob die Balken gefüllt sind. Nur für 1D-Barcodes. Standardwert: true. |
| [get_GS1](./get_gs1/)() const | GS1-Parameter. |
| [get_GS1CompositeBar](./get_gs1compositebar/)() const | GS1 Composite Bar-Parameter. |
| [get_HanXin](./get_hanxin/)() const | HanXin-Parameter. |
| [get_IsChecksumEnabled](./get_ischecksumenabled/)() const |  |
| [get_ITF](./get_itf/)() const | ITF-Parameter. |
| [get_MaxiCode](./get_maxicode/)() const | MaxiCode-Parameter. |
| [get_Padding](./get_padding/)() const | Barcode-Abstände. Standardwert: 5pt 5pt 5pt 5pt. |
| [get_PatchCode](./get_patchcode/)() const | PatchCode-Parameter. |
| [get_Pdf417](./get_pdf417/)() const | PDF417-Parameter. |
| [get_Postal](./get_postal/)() const | Postparameter. Verwendet für Postnet, Planet. |
| [get_QR](./get_qr/)() const | QR-, MicroQR- und RectMicroQR-Parameter. |
| [get_Supplement](./get_supplement/)() const | Ergänzungsparameter. Verwendet für Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [get_ThrowExceptionWhenCodeTextIncorrect](./get_throwexceptionwhencodetextincorrect/)() const | Nur für 1D-Barcodes. Wenn der Codetext inkorrekt ist und der Wert auf true gesetzt wird, wird eine Ausnahme ausgelöst. Andernfalls wird der Codetext korrigiert, um der Spezifikation des Barcodes zu entsprechen. Ausnahme wird immer ausgelöst für: Databar-Symbologie, wenn der Codetext inkorrekt ist. Ausnahme wird niemals ausgelöst für: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128-Symbologie, wenn der Codetext inkorrekt ist. |
| [get_WideNarrowRatio](./get_widenarrowratio/)() const | Verhältnis von breiten zu schmalen Balken. Standardwert: 3, das heißt, breite Balken sind dreimal so breit wie schmale Balken. Verwendet für ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [get_XDimension](./get_xdimension/)() const | Die x-Dimension ist die kleinste Breite der Einheit von [BarCode](../../aspose.barcode/) Balken oder Lücken. Eine Erhöhung davon vergrößert die gesamte Barcode-Bildbreite. Ignoriert, wenn die Eigenschaft [BaseGenerationParameters::AutoSizeMode](../) auf [AutoSizeMode.Nearest](../autosizemode/) oder [AutoSizeMode.Interpolation](../autosizemode/) gesetzt ist. |
| [set_BarColor](./set_barcolor/)(System::Drawing::Color) | Farbe der Balken. Standardwert: Color.Black. |
| [set_BarHeight](./set_barheight/)(System::SharedPtr\<Unit\>) | Höhe der Balken von 1D-Barcodes im [Unit](../unit/)-Wert. Ignoriert, wenn die Eigenschaft [BaseGenerationParameters::AutoSizeMode](../) auf [AutoSizeMode.Nearest](../autosizemode/) oder [AutoSizeMode.Interpolation](../autosizemode/) gesetzt ist. |
| [set_BarWidthReduction](./set_barwidthreduction/)(System::SharedPtr\<Unit\>) | Liest oder setzt den Reduktionswert der Balken, der verwendet wird, um die Tintenverbreitung beim Drucken auszugleichen. Standardwert: 0 |
| [set_ChecksumAlwaysShow](./set_checksumalwaysshow/)(bool) | Checksumme immer im menschenlesbaren Text für Code128- und GS1Code128-Barcodes anzeigen. |
| [set_FilledBars](./set_filledbars/)(bool) | Setzt einen Wert, der angibt, ob die Balken gefüllt sind. Nur für 1D-Barcodes. Standardwert: true. |
| [set_GS1CompositeBar](./set_gs1compositebar/)(System::SharedPtr\<GS1CompositeBarParameters\>) | GS1 Composite Bar-Parameter. |
| [set_IsChecksumEnabled](./set_ischecksumenabled/)(EnableChecksum) |  |
| [set_ThrowExceptionWhenCodeTextIncorrect](./set_throwexceptionwhencodetextincorrect/)(bool) | Nur für 1D-Barcodes. Wenn der Codetext inkorrekt ist und der Wert auf true gesetzt wird, wird eine Ausnahme ausgelöst. Andernfalls wird der Codetext korrigiert, um der Spezifikation des Barcodes zu entsprechen. Ausnahme wird immer ausgelöst für: Databar-Symbologie, wenn der Codetext inkorrekt ist. Ausnahme wird niemals ausgelöst für: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128-Symbologie, wenn der Codetext inkorrekt ist. |
| [set_WideNarrowRatio](./set_widenarrowratio/)(float) | Verhältnis von breiten zu schmalen Balken. Standardwert: 3, das heißt, breite Balken sind dreimal so breit wie schmale Balken. Verwendet für ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [set_XDimension](./set_xdimension/)(System::SharedPtr\<Unit\>) | Die x-Dimension ist die kleinste Breite der Einheit von [BarCode](../../aspose.barcode/) Balken oder Lücken. Eine Erhöhung davon vergrößert die gesamte Barcode-Bildbreite. Ignoriert, wenn die Eigenschaft [BaseGenerationParameters::AutoSizeMode](../) auf [AutoSizeMode.Nearest](../autosizemode/) oder [AutoSizeMode.Interpolation](../autosizemode/) gesetzt ist. |
## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
