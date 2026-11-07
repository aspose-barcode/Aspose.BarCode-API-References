---
title: "Aspose::BarCode::Generation::BaseGenerationParameters class"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Generation::BaseGenerationParameters 클래스. C++에서 바코드 이미지 생성 매개변수입니다."
type: docs
weight: 700
url: /ko/cpp/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class


바코드 이미지 생성 매개변수.

```cpp
class BaseGenerationParameters : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_AutoSizeMode](./get_autosizemode/)() const | 자동 크기 조정 모드의 다양한 유형을 지정합니다. 기본값: [AutoSizeMode.None](../autosizemode/). |
| [get_BackColor](./get_backcolor/)() const | 바코드 이미지의 배경 색상입니다. 기본값: Color.White. 자세한 내용은 [Color](../)를 참조하십시오. |
| [get_Barcode](./get_barcode/)() const | 모든 바코드 속성을 포함하는 [BarcodeParameters](../barcodeparameters/)를 가져옵니다. |
| [get_Border](./get_border/)() const | 바코드 테두리의 모든 구성 속성을 포함하는 [BorderParameters](../borderparameters/)를 가져옵니다. |
| [get_CaptionAbove](./get_captionabove/)() const | 이미지 위에 있는 캡션 [BarCode](../../aspose.barcode/) 이미지. [CaptionParameters](../captionparameters/)를 참조하십시오. |
| [get_CaptionBelow](./get_captionbelow/)() const | 이미지 아래에 있는 캡션 [BarCode](../../aspose.barcode/) 이미지. [CaptionParameters](../captionparameters/)를 참조하십시오. |
| [get_Image](./get_image/)() const | 이미지 매개변수. [ImageParameters](../imageparameters/)를 참조하십시오. |
| [get_ImageHeight](./get_imageheight/)() const | [BarCode](../../aspose.barcode/) 이미지 높이, [AutoSizeMode](../autosizemode/) 속성이 [AutoSizeMode.Nearest](../autosizemode/) 또는 [AutoSizeMode.Interpolation](../autosizemode/)으로 설정된 경우. |
| [get_ImageWidth](./get_imagewidth/)() const | [BarCode](../../aspose.barcode/) 이미지 너비, [AutoSizeMode](../autosizemode/) 속성이 [AutoSizeMode.Nearest](../autosizemode/) 또는 [AutoSizeMode.Interpolation](../autosizemode/)으로 설정된 경우. |
| [get_Resolution](./get_resolution/)() const | [BarCode](../../aspose.barcode/) 이미지의 해상도를 가져옵니다. 두 차원 모두에 대한 하나의 값입니다. 기본값: 96 dpi. |
| [get_RotationAngle](./get_rotationangle/)() const | [BarCode](../../aspose.barcode/) 이미지 회전 각도(도 단위). 예: RotationAngle = 0 또는 RotationAngle = 360은 회전 없음. RotationAngle가 90, 180, 270 또는 0이 아니면 스캐너가 이미지를 읽기 어려워질 수 있습니다. 기본값: 0. |
| [get_UseAntiAlias](./get_useantialias/)() const | 이미지를 렌더링할 때 안티앨리어싱 모드가 사용되는지 여부를 나타내는 값을 가져옵니다. |
| [set_AutoSizeMode](./set_autosizemode/)(Aspose::BarCode::Generation::AutoSizeMode) | 자동 크기 조정 모드의 다양한 유형을 지정합니다. 기본값: [AutoSizeMode.None](../autosizemode/). |
| [set_BackColor](./set_backcolor/)(System::Drawing::Color) | 바코드 이미지의 배경 색상입니다. 기본값: Color.White. 자세한 내용은 [Color](../)를 참조하십시오. |
| [set_ImageHeight](./set_imageheight/)(System::SharedPtr\<Unit\>) | [BarCode](../../aspose.barcode/) 이미지 높이, [AutoSizeMode](../autosizemode/) 속성이 [AutoSizeMode.Nearest](../autosizemode/) 또는 [AutoSizeMode.Interpolation](../autosizemode/)으로 설정된 경우. |
| [set_ImageWidth](./set_imagewidth/)(System::SharedPtr\<Unit\>) | [BarCode](../../aspose.barcode/) 이미지 너비, [AutoSizeMode](../autosizemode/) 속성이 [AutoSizeMode.Nearest](../autosizemode/) 또는 [AutoSizeMode.Interpolation](../autosizemode/)으로 설정된 경우. |
| [set_Resolution](./set_resolution/)(float) | [BarCode](../../aspose.barcode/) 이미지의 해상도를 설정합니다. 두 차원 모두에 대한 하나의 값입니다. 기본값: 96 dpi. |
| [set_RotationAngle](./set_rotationangle/)(float) | [BarCode](../../aspose.barcode/) 이미지 회전 각도(도 단위). 예: RotationAngle = 0 또는 RotationAngle = 360은 회전 없음. RotationAngle가 90, 180, 270 또는 0이 아니면 스캐너가 이미지를 읽기 어려워질 수 있습니다. 기본값: 0. |
| [set_UseAntiAlias](./set_useantialias/)(bool) | 이미지를 렌더링할 때 안티앨리어싱 모드가 사용되는지 여부를 나타내는 값을 설정합니다. |
## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
