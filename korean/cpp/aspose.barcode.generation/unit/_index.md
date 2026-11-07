---
title: "Aspose::BarCode::Generation::Unit 클래스"
linktitle: "Unit"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Generation::Unit 클래스. C++에서 다양한 단위(Pixel, Inches 등)로 크기 값을 지정합니다."
type: docs
weight: 5000
url: /ko/cpp/aspose.barcode.generation/unit/
---
## Unit class


다양한 단위(픽셀, 인치 등)로 크기 값을 지정합니다.

```cpp
class Unit : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 이 인스턴스와 지정된 객체(또한 [Unit](./) 객체여야 함)가 동일한 값을 갖는지 여부를 결정합니다. |
| [get_Document](./get_document/)() | 문서 단위로 크기 값을 가져옵니다. |
| [get_Inches](./get_inches/)() | 인치 단위로 크기 값을 가져옵니다. |
| [get_Millimeters](./get_millimeters/)() | 밀리미터 단위로 크기 값을 가져옵니다. |
| [get_Pixels](./get_pixels/)() | 픽셀 단위로 크기 값을 가져옵니다. |
| [get_Point](./get_point/)() | 포인트 단위로 크기 값을 가져옵니다. |
| [get_Resolution](./get_resolution/)() const | Resolution |
| [GetHashCode](./gethashcode/)() const override | 이 객체에 대한 해시 코드를 반환합니다. |
| [set_Document](./set_document/)(float) | 문서 단위로 크기 값을 설정합니다. |
| [set_Inches](./set_inches/)(float) | 인치 단위로 크기 값을 설정합니다. |
| [set_Millimeters](./set_millimeters/)(float) | 밀리미터 단위로 크기 값을 설정합니다. |
| [set_Pixels](./set_pixels/)(float) | 픽셀 단위로 크기 값을 설정합니다. |
| [set_Point](./set_point/)(float) | 포인트 단위로 크기 값을 설정합니다. |
| [ToString](./tostring/)() const override | 이 [Unit](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 비고


이 샘플은 [BarCode](../../aspose.barcode/) 이미지를 생성하고 저장하는 방법을 보여줍니다.
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
