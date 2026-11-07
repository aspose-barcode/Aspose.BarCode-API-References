---
title: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class. C++에서 HIBC LIC 보조 및 추가 데이터를 저장하기 위한 클래스."
type: docs
weight: 2600
url: /ko/cpp/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class


HIBC LIC 보조 및 추가 데이터를 저장하기 위한 클래스.

```cpp
class SecondaryAndAdditionalData : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 이 인스턴스가 지정된 [SecondaryAndAdditionalData](./) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [get_DateOfManufacture](./get_dateofmanufacture/)() const | 제조 날짜를 식별합니다. 이 필드를 사용하지 않으려면 제조 날짜를 DateTime.MinValue로 설정할 수 있습니다. 기본값: DateTime.MinValue |
| [get_ExpiryDate](./get_expirydate/)() const | 만료 날짜를 식별합니다. ExpiryDateFormat이 None으로 설정되지 않은 경우 사용됩니다. |
| [get_ExpiryDateFormat](./get_expirydateformat/)() const | 만료 날짜 형식을 식별합니다. |
| [get_LotNumber](./get_lotnumber/)() const | 로트 또는 배치 번호를 식별합니다. 로트/배치 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다. |
| [get_Quantity](./get_quantity/)() const | 수량을 식별합니다. 0에서 500 사이의 정수값이어야 합니다. 이 필드를 사용하지 않으려면 수량을 -1로 설정할 수 있습니다. 기본값: -1 |
| [get_SerialNumber](./get_serialnumber/)() const | 시리얼 번호를 식별합니다. 시리얼 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [ParseFromString](./parsefromstring/)(System::String) | HIBC LIC 사양에 따라 문자열 형식에서 보조 및 추가 보충 데이터를 인스턴스화합니다. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/)() |  |
| [set_DateOfManufacture](./set_dateofmanufacture/)(System::DateTime) | 제조 날짜를 식별합니다. 이 필드를 사용하지 않으려면 제조 날짜를 DateTime.MinValue로 설정할 수 있습니다. 기본값: DateTime.MinValue |
| [set_ExpiryDate](./set_expirydate/)(System::DateTime) | 만료 날짜를 식별합니다. ExpiryDateFormat이 None으로 설정되지 않은 경우 사용됩니다. |
| [set_ExpiryDateFormat](./set_expirydateformat/)(HIBCLICDateFormat) | 만료 날짜 형식을 식별합니다. |
| [set_LotNumber](./set_lotnumber/)(System::String) | 로트 또는 배치 번호를 식별합니다. 로트/배치 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다. |
| [set_Quantity](./set_quantity/)(int32_t) | 수량을 식별합니다. 0에서 500 사이의 정수값이어야 합니다. 이 필드를 사용하지 않으려면 수량을 -1로 설정할 수 있습니다. 기본값: -1 |
| [set_SerialNumber](./set_serialnumber/)(System::String) | 시리얼 번호를 식별합니다. 시리얼 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다. |
| [ToString](./tostring/)() const override | HIBC LIC 사양에 따라 데이터를 문자열 형식으로 변환합니다. |
## 또 보기

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
