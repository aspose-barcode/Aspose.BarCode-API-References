---
title: "Aspose::BarCode::Generation::BarcodeParameters 클래스"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Generation::BarcodeParameters 클래스. C++에서 바코드 생성 매개변수."
type: docs
weight: 500
url: /ko/cpp/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class


바코드 생성 매개변수.

```cpp
class BarcodeParameters : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_AustralianPost](./get_australianpost/)() const | AustralianPost 바코드 매개변수. |
| [get_Aztec](./get_aztec/)() const | Aztec 매개변수. |
| [get_BarColor](./get_barcolor/)() const | 바 색상. 기본값: Color.Black. |
| [get_BarHeight](./get_barheight/)() const | 1D 바코드 바의 높이를 [Unit](../unit/) 값으로 지정합니다. [BaseGenerationParameters::AutoSizeMode](../) 속성이 [AutoSizeMode.Nearest](../autosizemode/) 또는 [AutoSizeMode.Interpolation](../autosizemode/) 로 설정된 경우 무시됩니다. |
| [get_BarWidthReduction](./get_barwidthreduction/)() const | 인쇄 시 잉크 번짐을 보정하기 위해 사용되는 바 감소 값을 가져오거나 설정합니다. 기본값: 0 |
| [get_ChecksumAlwaysShow](./get_checksumalwaysshow/)() const | Code128 및 GS1Code128 바코드에 대해 사람이 읽을 수 있는 텍스트에 항상 체크섬 숫자를 표시합니다. |
| [get_Codabar](./get_codabar/)() const | Codabar 매개변수. |
| [get_Codablock](./get_codablock/)() const | Codablock 매개변수. |
| [get_Code128](./get_code128/)() const | Code128 매개변수. |
| [get_Code16K](./get_code16k/)() const | Code16K 매개변수. |
| [get_CodeTextParameters](./get_codetextparameters/)() const | Codetext 매개변수. |
| [get_Coupon](./get_coupon/)() const | 쿠폰 매개변수. UpcaGs1DatabarCoupon 및 UpcaGs1Code128Coupon에 사용됩니다. |
| [get_DataBar](./get_databar/)() const | Databar 매개변수. |
| [get_DataMatrix](./get_datamatrix/)() const | DataMatrix 매개변수. |
| [get_DotCode](./get_dotcode/)() const | DotCode 매개변수. |
| [get_FilledBars](./get_filledbars/)() const | 바가 채워졌는지 여부를 나타내는 값을 가져옵니다. 1D 바코드에만 적용됩니다. 기본값: true. |
| [get_GS1](./get_gs1/)() const | GS1 매개변수. |
| [get_GS1CompositeBar](./get_gs1compositebar/)() const | GS1 복합 바 매개변수. |
| [get_HanXin](./get_hanxin/)() const | HanXin 매개변수. |
| [get_IsChecksumEnabled](./get_ischecksumenabled/)() const |  |
| [get_ITF](./get_itf/)() const | ITF 매개변수. |
| [get_MaxiCode](./get_maxicode/)() const | MaxiCode 매개변수. |
| [get_Padding](./get_padding/)() const | 바코드 패딩. 기본값: 5pt 5pt 5pt 5pt. |
| [get_PatchCode](./get_patchcode/)() const | PatchCode 매개변수. |
| [get_Pdf417](./get_pdf417/)() const | PDF417 매개변수. |
| [get_Postal](./get_postal/)() const | 우편 매개변수. Postnet 및 Planet에 사용됩니다. |
| [get_QR](./get_qr/)() const | QR, MicroQR 및 RectMicroQR 매개변수. |
| [get_Supplement](./get_supplement/)() const | 보조 매개변수. Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN에 사용됩니다. |
| [get_ThrowExceptionWhenCodeTextIncorrect](./get_throwexceptionwhencodetextincorrect/)() const | 1D 바코드에만 적용됩니다. codetext가 올바르지 않고 값이 true로 설정된 경우 예외가 발생합니다. 그렇지 않으면 codetext가 바코드 사양에 맞게 수정됩니다. 예외는 항상 발생합니다: Databar 심볼로지가 codetext가 올바르지 않은 경우. 예외는 절대 발생하지 않습니다: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 심볼로지가 codetext가 올바르지 않은 경우. |
| [get_WideNarrowRatio](./get_widenarrowratio/)() const | 넓은 바와 좁은 바의 비율. 기본값: 3, 즉 넓은 바는 좁은 바보다 3배 넓습니다. ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII에 사용됩니다. |
| [get_XDimension](./get_xdimension/)() const | x-dimension은 [BarCode](../../aspose.barcode/) 바 또는 공백 단위의 가장 작은 너비입니다. 이를 증가시키면 전체 바코드 이미지 너비가 증가합니다. [BaseGenerationParameters::AutoSizeMode](../) 속성이 [AutoSizeMode.Nearest](../autosizemode/) 또는 [AutoSizeMode.Interpolation](../autosizemode/)으로 설정된 경우 무시됩니다. |
| [set_BarColor](./set_barcolor/)(System::Drawing::Color) | 바 색상. 기본값: Color.Black. |
| [set_BarHeight](./set_barheight/)(System::SharedPtr\<Unit\>) | 1D 바코드 바의 높이를 [Unit](../unit/) 값으로 지정합니다. [BaseGenerationParameters::AutoSizeMode](../) 속성이 [AutoSizeMode.Nearest](../autosizemode/) 또는 [AutoSizeMode.Interpolation](../autosizemode/) 로 설정된 경우 무시됩니다. |
| [set_BarWidthReduction](./set_barwidthreduction/)(System::SharedPtr\<Unit\>) | 인쇄 시 잉크 번짐을 보정하기 위해 사용되는 바 감소 값을 가져오거나 설정합니다. 기본값: 0 |
| [set_ChecksumAlwaysShow](./set_checksumalwaysshow/)(bool) | Code128 및 GS1Code128 바코드에 대해 사람이 읽을 수 있는 텍스트에 항상 체크섬 숫자를 표시합니다. |
| [set_FilledBars](./set_filledbars/)(bool) | 바가 채워졌는지 여부를 나타내는 값을 설정합니다. 1D 바코드에만 적용됩니다. 기본값: true. |
| [set_GS1CompositeBar](./set_gs1compositebar/)(System::SharedPtr\<GS1CompositeBarParameters\>) | GS1 복합 바 매개변수. |
| [set_IsChecksumEnabled](./set_ischecksumenabled/)(EnableChecksum) |  |
| [set_ThrowExceptionWhenCodeTextIncorrect](./set_throwexceptionwhencodetextincorrect/)(bool) | 1D 바코드에만 적용됩니다. codetext가 올바르지 않고 값이 true로 설정된 경우 예외가 발생합니다. 그렇지 않으면 codetext가 바코드 사양에 맞게 수정됩니다. 예외는 항상 발생합니다: Databar 심볼로지가 codetext가 올바르지 않은 경우. 예외는 절대 발생하지 않습니다: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 심볼로지가 codetext가 올바르지 않은 경우. |
| [set_WideNarrowRatio](./set_widenarrowratio/)(float) | 넓은 바와 좁은 바의 비율. 기본값: 3, 즉 넓은 바는 좁은 바보다 3배 넓습니다. ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII에 사용됩니다. |
| [set_XDimension](./set_xdimension/)(System::SharedPtr\<Unit\>) | x-dimension은 [BarCode](../../aspose.barcode/) 바 또는 공백 단위의 가장 작은 너비입니다. 이를 증가시키면 전체 바코드 이미지 너비가 증가합니다. [BaseGenerationParameters::AutoSizeMode](../) 속성이 [AutoSizeMode.Nearest](../autosizemode/) 또는 [AutoSizeMode.Interpolation](../autosizemode/)으로 설정된 경우 무시됩니다. |
## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
