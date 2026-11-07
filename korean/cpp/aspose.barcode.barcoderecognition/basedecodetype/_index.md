---
title: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType 클래스"
linktitle: "BaseDecodeType"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType 클래스. C++에서 MultiDecodeType 및 SingleDecodeType의 기본 클래스입니다."
type: docs
weight: 900
url: /ko/cpp/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class


[MultiDecodeType](../multidecodetype/) 및 [SingleDecodeType](../singledecodetype/)의 기본 클래스입니다.

```cpp
class BaseDecodeType : public virtual System::IEquatable<System::SharedPtr<BaseDecodeType>>
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | 주어진 디코드 유형 중 하나가 포함되는지 여부를 결정합니다. |
| virtual [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) | 이 인스턴스가 지정된 [SingleDecodeType](../singledecodetype/) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| virtual [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) | 이 인스턴스가 지정된 [MultiDecodeType](../multidecodetype/) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [Equals](./equals/)(System::SharedPtr\<BaseDecodeType\>) override | 지정된 [BaseDecodeType](./) 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | [SingleDecodeType](../singledecodetype/)의 문자열 표현을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | [MultiDecodeType](../multidecodetype/)의 문자열 표현을 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | [BaseDecodeType](./)의 문자열 표현을 구체적인 유형을 결정한 후 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다. |
## 비고


이 샘플은 [BaseDecodeType](./)을 [SingleDecodeType](../singledecodetype/) 및 [MultiDecodeType](../multidecodetype/)와 함께 사용하는 방법을 보여줍니다.
```cpp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

## 또 보기

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
