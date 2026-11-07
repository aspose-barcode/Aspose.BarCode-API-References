---
title: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink 클래스"
linktitle: "GS1DigitalLink"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink 클래스. GS1 Digital Link 코드 텍스트를 인코딩 및 디코딩하기 위해 Application Identifier 요소들의 순서가 지정된 시퀀스로 나타냅니다. 원본 순서와 반복되는 Application Identifier가 보존됩니다. 구성된 코드 텍스트는 압축되지 않은 GS1 Digital Link URI입니다. C++에서 구문 분석할 때 비GS1 쿼리 매개변수와 URI 조각은 무시됩니다."
type: docs
weight: 600
url: /ko/cpp/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class


GS1 Digital Link 코덱스트를 인코딩 및 디코딩하기 위해 Application Identifier 요소들의 순서가 지정된 시퀀스로 나타냅니다. 원본 순서와 반복되는 Application Identifier가 보존됩니다. 구성된 코덱스트는 압축되지 않은 GS1 Digital Link URI입니다. 파싱 시 비GS1 쿼리 매개변수와 URI 조각은 무시됩니다.

```cpp
class GS1DigitalLink : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Add](./add/)(System::String, System::String) | 검증된 Application Identifier 요소를 추가합니다. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>) | GS1 코드 텍스트의 모든 요소를 복사하고 사용 가능한 유일한 기본 키를 선택하여 GS1 Digital Link를 생성합니다. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>, System::String) | GS1 코드 텍스트의 모든 요소를 복사하고 지정된 기본 키를 사용하여 GS1 Digital Link를 생성합니다. |
| [get_BarcodeType](./get_barcodetype/)() const | 이 GS1 Digital Link를 인코딩하는 데 사용되는 바코드 유형을 가져옵니다. 지원되는 유형은 QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF 및 Code128입니다. 기본값은 QR입니다. |
| [get_Count](./get_count/)() | Application Identifier 요소의 개수를 가져옵니다. |
| [get_Elements](./get_elements/)() | 원본 순서대로 모든 요소의 복사본을 가져옵니다. |
| [get_PrimaryApplicationIdentifier](./get_primaryapplicationidentifier/)() const | Digital Link 기본 키로 사용되는 Application Identifier를 가져옵니다. Null은 URI가 구성될 때 기본 키가 자동으로 선택됨을 의미합니다. |
| [get_UriStem](./get_uristem/)() const | GS1 기본 키 경로 세그먼트 앞의 절대 URI 접두사를 가져옵니다. 해당 경로는 쿼리 문자열이나 조각을 포함하지 않습니다. |
| [GetAll](./getall/)(System::String) | 소스 순서대로 Application Identifier의 모든 값을 가져옵니다. |
| [GetBarcodeType](./getbarcodetype/)() override | 이 GS1 Digital Link를 인코딩하는 데 사용되는 바코드 유형을 가져옵니다. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 압축되지 않은 GS1 Digital Link URI를 구성합니다. |
| [GetFirst](./getfirst/)(System::String) | Application Identifier에 대한 첫 번째 값을 가져옵니다. |
| [GS1DigitalLink](./gs1digitallink/)(System::String) | 지정된 URI 스템으로 빈 GS1 Digital Link를 초기화합니다. 기본 키 후보가 정확히 하나만 존재할 경우 기본 키가 자동으로 선택됩니다. |
| [GS1DigitalLink](./gs1digitallink/)(System::String, System::String) | 지정된 URI 스템과 기본 키를 사용하여 빈 GS1 Digital Link를 초기화합니다. |
| [idx_get](./idx_get/)(int32_t) | 정렬된 시퀀스에서 위치에 따라 요소를 가져옵니다. |
| [InitFromString](./initfromstring/)(System::String) override | 압축되지 않은 GS1 Digital Link URI에서 이 인스턴스를 초기화합니다. 제공된 URI가 성공적으로 파싱된 후에만 기존 상태가 교체됩니다. 선택된 바코드 유형은 유지됩니다. |
| static [Parse](./parse/)(System::String) | 압축되지 않은 GS1 Digital Link URI를 파싱합니다. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | 이 GS1 Digital Link를 인코딩하는 데 사용되는 바코드 유형을 설정합니다. 지원되는 유형은 QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF 및 Code128입니다. 기본값은 QR입니다. |
| [ToGS1Codetext](./togs1codetext/)() | 현재 GS1 요소를 포함하는 독립적인 GS1 코덱스트를 생성합니다. URI 전용 정보는 포함되지 않습니다. |
| [ToString](./tostring/)() const override | 압축되지 않은 GS1 Digital Link URI를 반환합니다. |
| [ToUriString](./touristring/)() | 현재 객체 상태를 압축되지 않은 GS1 Digital Link URI로 포맷합니다. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1DigitalLink\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | 압축되지 않은 GS1 Digital Link URI를 파싱하려 시도하고 구조화된 검증 오류를 반환합니다. |
| static [Validate](./validate/)(System::String) | 객체를 생성하지 않고 압축되지 않은 GS1 Digital Link URI를 검증합니다. |
## 또 보기

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
