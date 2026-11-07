---
title: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType 클래스"
linktitle: "MultiDecodeType"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType 클래스. C++의 복합 디코드 유형입니다."
type: docs
weight: 2600
url: /ko/cpp/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class


복합 디코드 유형입니다.

```cpp
class MultiDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                        public System::IEquatable<System::SharedPtr<MultiDecodeType>>
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<SingleDecodeType\>) | 하나의 [SingleDecodeType](../singledecodetype/)을 [MultiDecodeType](./)에 추가합니다. |
| [ContainsAll](./containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | 이 객체가 바코드 유형의 모든 타입을 포함하는지 확인합니다. |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | 어떤 타입이라도 포함하는지 확인합니다. |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | 이 인스턴스가 지정된 [MultiDecodeType](./) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | 이 디코드 타입 컬렉션이 지정된 [SingleDecodeType](../singledecodetype/) 값만 포함하는지 여부를 나타내는 값을 반환합니다. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 이 인스턴스가 지정된 [MultiDecodeType](./) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | 이 인스턴스가 지정된 [BaseDecodeType](../basedecodetype/) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [Exclude](./exclude/)(System::SharedPtr\<SingleDecodeType\>) | [SingleDecodeType](../singledecodetype/)을 [MultiDecodeType](./)에서 제외하고 새로운 [MultiDecodeType](./) 인스턴스를 반환합니다. |
| [get_GetSingleTypesCount](./get_getsingletypescount/)() | 단일 타입의 개수를 반환합니다. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [GetSingleTypes](./getsingletypes/)() | 단일 타입 목록을 나타냅니다. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | 새로운 [MultiDecodeType](./) 클래스 인스턴스를 초기화합니다. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | 새로운 [MultiDecodeType](./) 클래스 인스턴스를 초기화합니다. |
| [ToString](./tostring/)() const override | [MultiDecodeType](./)을 문자열로 나타내는 재정의된 메서드입니다. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | [MultiDecodeType](./)의 문자열 표현을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | [SingleDecodeType](../singledecodetype/)의 문자열 표현을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | [BaseDecodeType](../basedecodetype/)의 문자열 표현을 구체 유형을 결정한 후 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다. |
## 비고


이 예제는 [SingleDecodeType](../singledecodetype/)과 MultiDecode 타입을 결합한 복합 MultiDecode 타입을 만드는 방법을 보여줍니다.
```cpp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

## 또 보기

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
