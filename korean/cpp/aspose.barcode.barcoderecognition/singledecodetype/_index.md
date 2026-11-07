---
title: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType 클래스"
linktitle: "SingleDecodeType"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType 클래스. 단일 디코드 유형. C++에서 인스턴스를 얻으려면 디코드 유형을 참조하십시오."
type: docs
weight: 3200
url: /ko/cpp/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class


단일 디코드 유형입니다. 인스턴스를 얻으려면 디코드 유형을 참조하세요.

```cpp
class SingleDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                         public System::IEquatable<System::SharedPtr<SingleDecodeType>>
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | 이 인스턴스가 지정된 목록에 포함되어 있는지 여부를 나타내는 값을 반환합니다. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | 이 인스턴스가 지정된 [SingleDecodeType](./) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | 지정된 [MultiDecodeType](../multidecodetype/) 컬렉션에 이 디코드 유형만 포함되어 있는지 여부를 나타내는 값을 반환합니다. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 이 인스턴스가 지정된 [SingleDecodeType](./) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | 이 인스턴스가 지정된 [BaseDecodeType](../basedecodetype/) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [get_TypeIndex](./get_typeindex/)() const | 디코드 유형의 인덱스를 가져옵니다. |
| [get_TypeName](./get_typename/)() const | 디코드 유형의 이름을 가져옵니다. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [GetString](./getstring/)() | [SingleDecodeType](./) 인스턴스를 해당 문자열 표현으로 변환합니다. 문자열 형식은: "Index:-1; Name:None". |
| static [GetString](./getstring/)(System::SharedPtr\<SingleDecodeType\>) | [SingleDecodeType](./) 인스턴스를 해당 문자열 표현으로 변환합니다. 문자열 형식은: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | [SingleDecodeType](./) 이름의 문자열 표현을 인스턴스로 변환합니다. |
| [ToString](./tostring/)() const override | 주어진 [SingleDecodeType](./)의 이름을 문자열로 반환합니다. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | [SingleDecodeType](./)의 문자열 표현을 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | [MultiDecodeType](../multidecodetype/)의 문자열 표현을 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | [BaseDecodeType](../basedecodetype/)의 문자열 표현을 구체 유형을 결정한 후 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다. |
## 비고


이 샘플은 단일 디코드 유형의 인스턴스를 가져오는 방법을 보여줍니다.
```cpp
[C#]
SingleDecodeType singleType = DecodeType.QR

[VB.NET]
Dim singleType As SingleDecodeType
singleType = DecodeType.QR
```

## 또 보기

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
