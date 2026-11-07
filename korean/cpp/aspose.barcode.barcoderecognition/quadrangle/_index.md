---
title: "Aspose::BarCode::BarCodeRecognition::Quadrangle 클래스"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::Quadrangle 클래스. C++에서 Quadrangle 영역을 나타내는 네 개의 Point 집합을 저장합니다."
type: docs
weight: 3000
url: /ko/cpp/aspose.barcode.barcoderecognition/quadrangle/
---
## Quadrangle class


네 개의 [Point](../)s 집합을 저장하여 [Quadrangle](./) 영역을 나타냅니다.

```cpp
class Quadrangle : public System::IEquatable<System::SharedPtr<Quadrangle>>
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Contains](./contains/)(System::Drawing::Point) | 지정된 [Point](../)이 이 [Quadrangle](./) 클래스에 포함되는지 판단합니다. |
| [Contains](./contains/)(int32_t, int32_t) | 지정된 점이 이 [Quadrangle](./) 클래스에 포함되는지 확인합니다. |
| [Contains](./contains/)(System::SharedPtr\<Quadrangle\>) | 지정된 [Quadrangle](./)이 이 [Quadrangle](./) 클래스에 포함되거나 교차하는지 확인합니다. |
| [Contains](./contains/)(System::Drawing::Rectangle) | 지정된 [Rectangle](../)이 이 [Quadrangle](./) 클래스에 포함되거나 교차하는지 확인합니다. |
| [Equals](./equals/)(System::SharedPtr\<Quadrangle\>) override | 이 인스턴스가 지정된 [Quadrangle](./) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [get_BoundingRectangle](./get_boundingrectangle/)() | [Quadrangle](./)을 둘러싸는 [Rectangle](../)을 가져옵니다. |
| [get_IsEmpty](./get_isempty/)() | **Tests** 이 [Quadrangle](./)의 모든 [Point](../)가 값이 0인지 확인합니다. |
| [get_LeftBottom](./get_leftbottom/)() const | [Quadrangle](./) 영역의 왼쪽 하단 모서리 [Point](../)를 가져옵니다. |
| [get_LeftTop](./get_lefttop/)() const | [Quadrangle](./) 영역의 왼쪽 상단 모서리 [Point](../)를 가져옵니다. |
| [get_RightBottom](./get_rightbottom/)() const | [Quadrangle](./) 영역의 오른쪽 하단 모서리 [Point](../)를 가져옵니다. |
| [get_RightTop](./get_righttop/)() const | [Quadrangle](./) 영역의 오른쪽 상단 모서리 [Point](../)를 가져옵니다. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [Quadrangle](./quadrangle/)() | [Quadrangle](./) 클래스의 새로운 빈 인스턴스를 초기화합니다. |
| [Quadrangle](./quadrangle/)(System::Drawing::Point, System::Drawing::Point, System::Drawing::Point, System::Drawing::Point) | 설명 포인트를 사용하여 [Quadrangle](./) 클래스의 새로운 인스턴스를 초기화합니다. |
| [set_LeftBottom](./set_leftbottom/)(System::Drawing::Point) | [Quadrangle](./) 영역의 왼쪽 하단 모서리 [Point](../)를 가져옵니다. |
| [set_LeftTop](./set_lefttop/)(System::Drawing::Point) | [Quadrangle](./) 영역의 왼쪽 상단 모서리 [Point](../)를 가져옵니다. |
| [set_RightBottom](./set_rightbottom/)(System::Drawing::Point) | [Quadrangle](./) 영역의 오른쪽 하단 모서리 [Point](../)를 가져옵니다. |
| [set_RightTop](./set_righttop/)(System::Drawing::Point) | [Quadrangle](./) 영역의 오른쪽 상단 모서리 [Point](../)를 가져옵니다. |
| [ToString](./tostring/)() const override | 이 [Quadrangle](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| static [Empty](./empty/) | 속성이 초기화되지 않은 상태인 [Quadrangle](./) 클래스를 나타냅니다. |
## 또 보기

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
