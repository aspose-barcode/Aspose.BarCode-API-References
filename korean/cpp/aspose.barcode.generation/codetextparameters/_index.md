---
title: "Aspose::BarCode::Generation::CodetextParameters class"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Generation::CodetextParameters 클래스. C++에서 코드텍스트 매개변수."
type: docs
weight: 1500
url: /ko/cpp/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class


Codetext 매개변수.

```cpp
class CodetextParameters : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Alignment](./get_alignment/)() const | 코드 텍스트의 정렬을 가져옵니다. 기본값: [StringAlignment.Center](../textalignment/). |
| [get_Color](./get_color/)() const | 표시되는 CodeText의 색상을 지정합니다. 기본값: Color.Black. |
| [get_Font](./get_font/)() const | 표시되는 CodeText의 글꼴을 지정합니다. 기본값: Arial 5pt regular. FontMode가 [FontMode.Auto](../aztecencodemode/)로 설정된 경우 무시됩니다. |
| [get_FontMode](./get_fontmode/)() const | FontMode를 지정합니다. FontMode가 Auto로 설정되면 xDimension 값에 따라 글꼴 크기가 자동으로 계산됩니다. 특히 [AutoSizeMode.Nearest](../autosizemode/) 또는 [AutoSizeMode.Interpolation](../autosizemode/)에서 [FontMode.Auto](../aztecencodemode/)를 사용하는 것이 권장됩니다. 기본값: [FontMode.Auto](../aztecencodemode/). |
| [get_Location](./get_location/)() const | 표시되는 CodeText 위치를 지정합니다. CodeText를 숨기려면 [CodeLocation.None](../codelocation/)으로 설정합니다. 기본값: 1D 바코드의 경우 [CodeLocation.Below](../codelocation/), 2D 바코드의 경우 [CodeLocation.None](../codelocation/)입니다. |
| [get_NoWrap](./get_nowrap/)() const | 텍스트 내에서 단어 줄바꿈(줄 바꿈)을 지정합니다. 기본값: false. |
| [get_Space](./get_space/)() const | CodeText와 [BarCode](../../aspose.barcode/) 사이의 [Unit ](../unit/) 값에 대한 간격입니다. 기본값: 2pt. EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon에 대해서는 무시됩니다. |
| [get_TwoDDisplayText](./get_twoddisplaytext/)() const | 2D 바코드에서 코드 텍스트 대신 표시될 텍스트입니다. 사용 대상: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [set_Alignment](./set_alignment/)(TextAlignment) | 코드 텍스트의 정렬을 설정합니다. 기본값: [StringAlignment.Center](../textalignment/). |
| [set_Color](./set_color/)(System::Drawing::Color) | 표시되는 CodeText의 색상을 지정합니다. 기본값: Color.Black. |
| [set_FontMode](./set_fontmode/)(Aspose::BarCode::Generation::FontMode) | FontMode를 지정합니다. FontMode가 Auto로 설정되면 xDimension 값에 따라 글꼴 크기가 자동으로 계산됩니다. 특히 [AutoSizeMode.Nearest](../autosizemode/) 또는 [AutoSizeMode.Interpolation](../autosizemode/)에서 [FontMode.Auto](../aztecencodemode/)를 사용하는 것이 권장됩니다. 기본값: [FontMode.Auto](../aztecencodemode/). |
| [set_Location](./set_location/)(CodeLocation) | 표시되는 CodeText 위치를 지정합니다. CodeText를 숨기려면 [CodeLocation.None](../codelocation/)으로 설정합니다. 기본값: 1D 바코드의 경우 [CodeLocation.Below](../codelocation/), 2D 바코드의 경우 [CodeLocation.None](../codelocation/)입니다. |
| [set_NoWrap](./set_nowrap/)(bool) | 텍스트 내에서 단어 줄바꿈(줄 바꿈)을 지정합니다. 기본값: false. |
| [set_Space](./set_space/)(System::SharedPtr\<Unit\>) | CodeText와 [BarCode](../../aspose.barcode/) 사이의 [Unit ](../unit/) 값에 대한 간격입니다. 기본값: 2pt. EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon에 대해서는 무시됩니다. |
| [set_TwoDDisplayText](./set_twoddisplaytext/)(System::String) | 2D 바코드에서 코드 텍스트 대신 표시될 텍스트입니다. 사용 대상: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [ToString](./tostring/)() const override | 이 [CodetextParameters](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
