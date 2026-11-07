---
title: "Aspose::BarCode::Generation::SymbologyEncodeType 클래스"
linktitle: "SymbologyEncodeType"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Generation::SymbologyEncodeType 클래스. 심볼 인코드 유형. C++에서 인스턴스를 얻으려면 EncodeTypes를 참조하십시오."
type: docs
weight: 4900
url: /ko/cpp/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class


심볼 인코드 유형. 인스턴스를 얻으려면 [EncodeTypes](../encodetypes/)를 참조하십시오.

```cpp
class SymbologyEncodeType : public Aspose::BarCode::Generation::BaseEncodeType
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Equals](../baseencodetype/equals/)(System::SharedPtr\<BaseEncodeType\>) override | 이 인스턴스가 지정된 [BaseEncodeType](../baseencodetype/) 값과 동일한지 여부를 나타내는 값을 반환합니다. |
| [get_Classification](../baseencodetype/get_classification/)() const | 이 심볼의 분류를 가져옵니다. |
| [get_TypeIndex](../baseencodetype/get_typeindex/)() const | 인코드 유형의 인덱스를 가져옵니다. |
| [get_TypeName](../baseencodetype/get_typename/)() const | 인코드 유형의 이름을 가져옵니다. |
| [GetHashCode](../baseencodetype/gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [GetString](../baseencodetype/getstring/)() | [BaseEncodeType](../baseencodetype/) 인스턴스를 해당 문자열 표현으로 변환합니다. 문자열 형식은 "Index:0; Name:Codabar"입니다. |
| static [GetString](../baseencodetype/getstring/)(System::SharedPtr\<BaseEncodeType\>) | [BaseEncodeType](../baseencodetype/) 인스턴스를 해당 문자열 표현으로 변환합니다. 문자열 형식은 "Index:-1; Name:None"입니다. |
| static [Parse](../baseencodetype/parse/)(System::String) | [BaseEncodeType](../baseencodetype/) 이름의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [ToString](../baseencodetype/tostring/)() const override | 주어진 [BaseEncodeType](../baseencodetype/)의 이름을 문자열로 반환합니다. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | [BaseEncodeType](../baseencodetype/)의 문자열 표현을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | [BaseEncodeType](../baseencodetype/)의 문자열 표현을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다. |
## 비고


This sample shows how to get instance of [SymbologyEncodeType](./) class.
```cpp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR

[VB.NET]
Dim symbologyType As SymbologyEncodeType
symbologyType = EncodeTypes.QR
```

## 또 보기

* Class [BaseEncodeType](../baseencodetype/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
