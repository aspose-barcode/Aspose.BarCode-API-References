---
title: "Aspose::BarCode::Generation::ITFParameters class"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Generation::ITFParameters 클래스. C++에서 ITF 매개변수."
type: docs
weight: 3300
url: /ko/cpp/aspose.barcode.generation/itfparameters/
---
## ITFParameters class


ITF 매개변수.

```cpp
class ITFParameters : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_BorderThickness](./get_borderthickness/)() const | [Unit](../unit/) 값으로 ITF 경계(베어러 바) 두께를 가져옵니다. 기본값: 12pt. |
| [get_BorderType](./get_bordertype/)() const | ITF 바코드의 경계 유형. 기본값: [ITF14BorderType.Bar](../itf14bordertype/). |
| [get_QuietZoneCoef](./get_quietzonecoef/)() const | xDimension에서 정숙 구역의 크기. 기본값: 10, 즉 xDimension = 2px이면 정숙 구역은 20px이 됩니다. |
| [set_BorderThickness](./set_borderthickness/)(System::SharedPtr\<Unit\>) | ITF 경계(베어러 바)의 두께를 [Unit](../unit/) 값으로 설정합니다. 기본값: 12pt. |
| [set_BorderType](./set_bordertype/)(ITF14BorderType) | ITF 바코드의 경계 유형. 기본값: [ITF14BorderType.Bar](../itf14bordertype/). |
| [set_QuietZoneCoef](./set_quietzonecoef/)(int32_t) | xDimension에서 정숙 구역의 크기. 기본값: 10, 즉 xDimension = 2px이면 정숙 구역은 20px이 됩니다. |
| [ToString](./tostring/)() const override | 이 [ITFParameters](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
