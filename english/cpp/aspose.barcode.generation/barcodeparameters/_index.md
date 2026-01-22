---
title: Aspose::BarCode::Generation::BarcodeParameters class
linktitle: BarcodeParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::BarcodeParameters class. Barcode generation parameters in C++.'
type: docs
weight: 500
url: /cpp/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class


Barcode generation parameters.

```cpp
class BarcodeParameters : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_AustralianPost](./get_australianpost/)() const | AustralianPost barcode parameters. |
| [get_Aztec](./get_aztec/)() const | Aztec parameters. |
| [get_BarColor](./get_barcolor/)() const | Bars color. Default value: Color.Black. |
| [get_BarHeight](./get_barheight/)() const | Height of 1D barcodes' bars in [Unit](../unit/) value. Ignored if [BaseGenerationParameters::AutoSizeMode](../) property is set to [AutoSizeMode.Nearest](../autosizemode/) or [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_BarWidthReduction](./get_barwidthreduction/)() const | Get or sets bars reduction value that is used to compensate ink spread while printing. Default value: 0 |
| [get_ChecksumAlwaysShow](./get_checksumalwaysshow/)() const | Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes. |
| [get_Codabar](./get_codabar/)() const | Codabar parameters. |
| [get_Codablock](./get_codablock/)() const | Codablock parameters. |
| [get_Code128](./get_code128/)() const | Code128 parameters. |
| [get_Code16K](./get_code16k/)() const | Code16K parameters. |
| [get_CodeTextParameters](./get_codetextparameters/)() const | Codetext parameters. |
| [get_Coupon](./get_coupon/)() const | Coupon parameters. Used for UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [get_DataBar](./get_databar/)() const | Databar parameters. |
| [get_DataMatrix](./get_datamatrix/)() const | DataMatrix parameters. |
| [get_DotCode](./get_dotcode/)() const | DotCode parameters. |
| [get_EnableEscape](./get_enableescape/)() const | Indicates whether explains the character "\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is true, "\" will be explained as a special escape character. Otherwise, "\" acts as normal characters. |
| [get_FilledBars](./get_filledbars/)() const | Gets a value indicating whether bars filled. Only for 1D barcodes. Default value: true. |
| [get_GS1CompositeBar](./get_gs1compositebar/)() const | GS1 Composite Bar parameters. |
| [get_HanXin](./get_hanxin/)() const | HanXin parameters. |
| [get_IsChecksumEnabled](./get_ischecksumenabled/)() const |  |
| [get_ITF](./get_itf/)() const | ITF parameters. |
| [get_MaxiCode](./get_maxicode/)() const | MaxiCode parameters. |
| [get_Padding](./get_padding/)() const | Barcode paddings. Default value: 5pt 5pt 5pt 5pt. |
| [get_PatchCode](./get_patchcode/)() const | PatchCode parameters. |
| [get_Pdf417](./get_pdf417/)() const | PDF417 parameters. |
| [get_Postal](./get_postal/)() const | Postal parameters. Used for Postnet, Planet. |
| [get_QR](./get_qr/)() const | QR, MicroQR and RectMicroQR parameters. |
| [get_Supplement](./get_supplement/)() const | Supplement parameters. Used for Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [get_ThrowExceptionWhenCodeTextIncorrect](./get_throwexceptionwhencodetextincorrect/)() const | Only for 1D barcodes. If codetext is incorrect and value set to true - exception will be thrown. Otherwise codetext will be corrected to match barcode's specification. Exception always will be thrown for: Databar symbology if codetext is incorrect. Exception always will not be thrown for: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 symbology if codetext is incorrect. |
| [get_WideNarrowRatio](./get_widenarrowratio/)() | Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| [get_XDimension](./get_xdimension/)() const | x-dimension is the smallest width of the unit of [BarCode](../../aspose.barcode/) bars or spaces. Increase this will increase the whole barcode image width. Ignored if [BaseGenerationParameters::AutoSizeMode](../) property is set to [AutoSizeMode.Nearest](../autosizemode/) or [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarColor](./set_barcolor/)(System::Drawing::Color) | Bars color. Default value: Color.Black. |
| [set_BarHeight](./set_barheight/)(System::SharedPtr\<Unit\>) | Height of 1D barcodes' bars in [Unit](../unit/) value. Ignored if [BaseGenerationParameters::AutoSizeMode](../) property is set to [AutoSizeMode.Nearest](../autosizemode/) or [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarWidthReduction](./set_barwidthreduction/)(System::SharedPtr\<Unit\>) | Get or sets bars reduction value that is used to compensate ink spread while printing. Default value: 0 |
| [set_ChecksumAlwaysShow](./set_checksumalwaysshow/)(bool) | Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes. |
| [set_EnableEscape](./set_enableescape/)(bool) | Indicates whether explains the character "\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is true, "\" will be explained as a special escape character. Otherwise, "\" acts as normal characters. |
| [set_FilledBars](./set_filledbars/)(bool) | Sets a value indicating whether bars filled. Only for 1D barcodes. Default value: true. |
| [set_GS1CompositeBar](./set_gs1compositebar/)(System::SharedPtr\<GS1CompositeBarParameters\>) | GS1 Composite Bar parameters. |
| [set_IsChecksumEnabled](./set_ischecksumenabled/)(EnableChecksum) |  |
| [set_ThrowExceptionWhenCodeTextIncorrect](./set_throwexceptionwhencodetextincorrect/)(bool) | Only for 1D barcodes. If codetext is incorrect and value set to true - exception will be thrown. Otherwise codetext will be corrected to match barcode's specification. Exception always will be thrown for: Databar symbology if codetext is incorrect. Exception always will not be thrown for: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 symbology if codetext is incorrect. |
| [set_WideNarrowRatio](./set_widenarrowratio/)(float) | Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| [set_XDimension](./set_xdimension/)(System::SharedPtr\<Unit\>) | x-dimension is the smallest width of the unit of [BarCode](../../aspose.barcode/) bars or spaces. Increase this will increase the whole barcode image width. Ignored if [BaseGenerationParameters::AutoSizeMode](../) property is set to [AutoSizeMode.Nearest](../autosizemode/) or [AutoSizeMode.Interpolation](../autosizemode/). |
## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
