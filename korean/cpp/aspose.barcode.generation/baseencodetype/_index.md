---
title: "Aspose::BarCode::Generation::BaseEncodeType 클래스"
linktitle: "BaseEncodeType"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Generation::BaseEncodeType 클래스. C++에서 SymbologyEncodeType의 기본 클래스."
type: docs
weight: 600
url: /ko/cpp/aspose.barcode.generation/baseencodetype/
---
## BaseEncodeType class


기본 클래스 [SymbologyEncodeType](../symbologyencodetype/).

```cpp
class BaseEncodeType : public System::IEquatable<System::SharedPtr<BaseEncodeType>>
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<BaseEncodeType\>) override | 이 인스턴스가 지정된 [BaseEncodeType](./) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [get_Classification](./get_classification/)() const | 이 심볼의 분류를 가져옵니다. |
| [get_TypeIndex](./get_typeindex/)() const | 인코드 유형의 인덱스를 가져옵니다. |
| [get_TypeName](./get_typename/)() const | 인코드 유형의 이름을 가져옵니다. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [GetString](./getstring/)() | [BaseEncodeType](./) 인스턴스를 해당 문자열 표현으로 변환합니다. 문자열 형식은: "Index:0; Name:Codabar"입니다. |
| static [GetString](./getstring/)(System::SharedPtr\<BaseEncodeType\>) | [BaseEncodeType](./) 인스턴스를 해당 문자열 표현으로 변환합니다. 문자열 형식은: "Index:-1; Name:None"입니다. |
| static [Parse](./parse/)(System::String) | [BaseEncodeType](./) 이름의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [ToString](./tostring/)() const override | 주어진 [BaseEncodeType](./)의 이름을 문자열로 반환합니다. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | [BaseEncodeType](./)의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | [BaseEncodeType](./)의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다. |
## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
