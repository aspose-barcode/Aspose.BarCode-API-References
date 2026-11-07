---
title: "Aspose::BarCode::ComplexBarcode::GS1Codetext class"
linktitle: "GS1Codetext"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::GS1Codetext 클래스. 인코딩 및 디코딩을 위해 Application Identifier 요소의 정렬된 시퀀스로서 GS1 코덱스트를 나타냅니다. 소스 순서와 반복된 Application Identifier가 보존됩니다. 괄호 표기법은 (AI)value(AI)value 형식을 가집니다. 값 내부에 있는 리터럴 여는 괄호 ''(''는 (; 로 작성해야 합니다. 이는 지원되는 유일한 이스케이프 시퀀스입니다. 값 내부에 있는 닫는 괄호 '')''는 C++에서 이스케이프가 필요하지 않습니다."
type: docs
weight: 500
url: /ko/cpp/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class


GS1 코덱스트를 인코딩 및 디코딩하기 위해 Application Identifier 요소들의 순서가 지정된 시퀀스로 나타냅니다. 원본 순서와 반복되는 Application Identifier가 보존됩니다. 괄호 표기는 (AI)value(AI)value 형태를 가집니다. 값 안에 있는 리터럴 여는 괄호 '('는 (; 로 기록해야 합니다. 이는 지원되는 유일한 이스케이프 시퀀스입니다. 값 안에 있는 닫는 괄호 ')'는 이스케이프가 필요하지 않습니다.

```cpp
class GS1Codetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Add](./add/)(System::String, System::String) | 검증된 Application Identifier 요소를 추가합니다. |
| [get_BarcodeType](./get_barcodetype/)() const | 이 GS1 codetext를 인코딩하는 데 사용되는 바코드 유형을 가져옵니다. 지원되는 유형은 GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR 및 GS1 DataBar 유형입니다. 기본값은 GS1Code128입니다. |
| [get_Count](./get_count/)() | Application Identifier 요소의 개수를 가져옵니다. |
| [get_Elements](./get_elements/)() | 원본 순서대로 모든 요소의 복사본을 가져옵니다. |
| [GetAll](./getall/)(System::String) | 소스 순서대로 Application Identifier의 모든 값을 가져옵니다. |
| [GetBarcodeType](./getbarcodetype/)() override | 이 GS1 codetext를 인코딩하는 데 사용되는 바코드 유형을 가져옵니다. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 괄호 형식의 GS1 codetext를 (AI)value(AI)value 형태로 구성합니다. 값 내부의 리터럴 여는 괄호는 ( 로 이스케이프됩니다. |
| [GetFirst](./getfirst/)(System::String) | Application Identifier에 대한 첫 번째 값을 가져옵니다. |
| [GS1Codetext](./gs1codetext/)() | 빈 GS1 codetext를 초기화합니다. |
| [idx_get](./idx_get/)(int32_t) | 정렬된 시퀀스에서 위치에 따라 요소를 가져옵니다. |
| [InitFromString](./initfromstring/)(System::String) override | 이 인스턴스를 (AI)value(AI)value 형태의 괄호형 GS1 codetext에서 초기화합니다. 제공된 codetext가 성공적으로 파싱된 후에만 기존 요소가 교체됩니다. |
| static [Parse](./parse/)(System::String) | 괄호형 GS1 요소 문자열을 (AI)value(AI)value 형태로 파싱합니다. 값 내부에 있는 리터럴 '('는 (; 로 작성해야 합니다. 다른 이스케이프 시퀀스는 지원되지 않으며, ')'는 이스케이프가 필요하지 않습니다. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | 이 GS1 codetext를 인코딩하는 데 사용되는 바코드 유형을 설정합니다. 지원되는 유형은 GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR 및 GS1 DataBar 유형입니다. 기본값은 GS1Code128입니다. |
| [ToString](./tostring/)() const override | 괄호로 묶인 GS1 표현을 (AI)value(AI)value 형식으로 반환합니다. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1Codetext\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | 괄호로 묶인 GS1 요소 문자열을 (AI)value(AI)value 형식으로 구문 분석하려 시도하고 구조화된 검증 오류를 반환합니다. 값 내부에 있는 리터럴 '('는 ( 로 작성해야 하며, 다른 이스케이프 시퀀스는 지원되지 않고 ')'는 이스케이프가 필요하지 않습니다. |
| static [Validate](./validate/)(System::String) | 괄호로 묶인 GS1 요소 문자열을 (AI)value(AI)value 형식으로 객체를 생성하지 않고 검증합니다. 값 내부에 있는 리터럴 '('는 ( 로 작성해야 하며, 다른 이스케이프 시퀀스는 지원되지 않고 ')'는 이스케이프가 필요하지 않습니다. |
## 또 보기

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
