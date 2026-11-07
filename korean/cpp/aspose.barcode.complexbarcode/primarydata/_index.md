---
title: "Aspose::BarCode::ComplexBarcode::PrimaryData 클래스"
linktitle: "PrimaryData"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::PrimaryData 클래스. C++에서 HIBC LIC 기본 데이터를 저장하기 위한 클래스."
type: docs
weight: 2500
url: /ko/cpp/aspose.barcode.complexbarcode/primarydata/
---
## PrimaryData class


HIBC LIC 기본 데이터를 저장하기 위한 클래스.

```cpp
class PrimaryData : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 이 인스턴스가 지정된 [PrimaryData](./) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [get_LabelerIdentificationCode](./get_labeleridentificationcode/)() const | 라벨러 식별 코드의 날짜를 식별합니다. 라벨러 식별 코드는 첫 번째 문자가 항상 알파벳인 4자리 영숫자 문자열이어야 합니다. |
| [get_ProductOrCatalogNumber](./get_productorcatalognumber/)() const | 제품 또는 카탈로그 번호를 식별합니다. 제품 또는 카탈로그 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다. |
| [get_UnitOfMeasureID](./get_unitofmeasureid/)() const | 측정 단위 ID를 식별합니다. 측정 단위 ID는 0에서 9 사이의 정수 값이어야 합니다. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [ParseFromString](./parsefromstring/)(System::String) | HIBC LIC 사양에 따라 문자열 형식에서 기본 데이터를 인스턴스화합니다. |
| [PrimaryData](./primarydata/)() |  |
| [set_LabelerIdentificationCode](./set_labeleridentificationcode/)(System::String) | 라벨러 식별 코드의 날짜를 식별합니다. 라벨러 식별 코드는 첫 번째 문자가 항상 알파벳인 4자리 영숫자 문자열이어야 합니다. |
| [set_ProductOrCatalogNumber](./set_productorcatalognumber/)(System::String) | 제품 또는 카탈로그 번호를 식별합니다. 제품 또는 카탈로그 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다. |
| [set_UnitOfMeasureID](./set_unitofmeasureid/)(int32_t) | 측정 단위 ID를 식별합니다. 측정 단위 ID는 0에서 9 사이의 정수 값이어야 합니다. |
| [ToString](./tostring/)() const override | HIBC LIC 사양에 따라 데이터를 문자열 형식으로 변환합니다. |
## 또 보기

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
