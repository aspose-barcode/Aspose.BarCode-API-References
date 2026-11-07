---
title: "Aspose::BarCode::ComplexBarcode::Address 클래스"
linktitle: "주소"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::Address 클래스. C++에서 채권자 또는 채무자의 주소."
type: docs
weight: 100
url: /ko/cpp/aspose.barcode.complexbarcode/address/
---
## Address class


[Address](./) of creditor or debtor.

```cpp
class Address : public System::IEquatable<System::SharedPtr<Address>>
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Address](./address/)() | [Address](./) 인스턴스를 생성합니다. |
| [Clear](./clear/)() | 모든 필드를 지우고 유형을 [AddressType::Undetermined](../addresstype/) 로 설정합니다. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 지정된 객체가 현재 객체와 같은지 여부를 결정합니다. |
| [Equals](./equals/)(System::SharedPtr\<Address\>) override | 지정된 주소가 현재 주소와 같은지 여부를 결정합니다. |
| [get_AddressLine1](./get_addressline1/)() const | 주소 라인 1을 가져옵니다. |
| [get_AddressLine2](./get_addressline2/)() const | 주소 라인 2를 가져옵니다. |
| [get_CountryCode](./get_countrycode/)() const | 두 글자 ISO 국가 코드를 가져옵니다. |
| [get_HouseNo](./get_houseno/)() const | 건물 번호를 가져옵니다. |
| [get_Name](./get_name/)() const | 자연인의 경우 성과 이름, 법인의 경우 회사명을 가져옵니다. |
| [get_PostalCode](./get_postalcode/)() const | 우편 번호를 가져옵니다. |
| [get_Street](./get_street/)() const | 거리명을 가져옵니다. |
| [get_Town](./get_town/)() const | 도시 또는 마을을 가져옵니다. |
| [get_Type](./get_type/)() const | 주소 유형을 가져옵니다. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 가져옵니다. |
| [set_AddressLine1](./set_addressline1/)(System::String) | 주소 라인 1을 설정합니다. |
| [set_AddressLine2](./set_addressline2/)(System::String) | 주소 라인 2를 설정합니다. |
| [set_CountryCode](./set_countrycode/)(System::String) | 두 글자 ISO 국가 코드를 설정합니다. |
| [set_HouseNo](./set_houseno/)(System::String) | 건물 번호를 설정합니다. |
| [set_Name](./set_name/)(System::String) | 자연인의 경우 성과 이름, 법인의 경우 회사명을 설정합니다. |
| [set_PostalCode](./set_postalcode/)(System::String) | 우편 번호를 설정합니다. |
| [set_Street](./set_street/)(System::String) | 거리를 설정합니다. |
| [set_Town](./set_town/)(System::String) | 도시 또는 마을을 설정합니다. |
## 비고


거리, 건물 번호, 우편 번호 및 도시를 (유형 *structured address*) 로 설정하거나 주소 라인 1과 2를 (유형 *combined address elements*) 로 설정할 수 있습니다. 필드 중 하나가 설정되면 유형이 자동으로 지정됩니다. 필드를 설정하기 전에 주소 유형은 *undetermined* 입니다. 두 유형의 필드를 모두 설정하면 주소 유형이 *conflicting* 으로 변합니다. 모든 필드가 비어 있지 않은 경우 이름과 국가 코드는 항상 설정되어야 합니다.
## 또 보기

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
