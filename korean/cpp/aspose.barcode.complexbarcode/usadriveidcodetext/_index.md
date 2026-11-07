---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext 클래스"
linktitle: "USADriveIdCodetext"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext 클래스. C++에서 미국 운전 면허 PDF417 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 클래스입니다."
type: docs
weight: 2900
url: /ko/cpp/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class


미국 운전 [License](../../aspose.barcode/license/) PDF417 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 클래스입니다.

```cpp
class USADriveIdCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_AAMVAVersionNumber](./get_aamvaversionnumber/)() const | AAMVA 버전 번호 00-99 |
| [get_IssuerIdentificationNumber](./get_issueridentificationnumber/)() const | 이 번호는 발행 관할 구역을 고유하게 식별하며 ISO 발행 기관(AAMVA)에 문의하여 얻을 수 있습니다. 전체 6자리 IIN을 인코딩해야 합니다. |
| [get_JurisdictionSpecificSubfile](./get_jurisdictionspecificsubfile/)() const | 관할 구역별 필드 |
| [get_JurisdictionVersionNumber](./get_jurisdictionversionnumber/)() const | 관할 구역 버전 번호 00-99 |
| [get_MandatoryElements](./get_mandatoryelements/)() const | 카드의 필수 요소(필드) |
| [get_NumberOfEntries](./get_numberofentries/)() const | 하위 파일 번호 00-99 |
| [get_OptionalElements](./get_optionalelements/)() const | 카드의 선택적 요소(필드) |
| [get_SubfileDesignator](./get_subfiledesignator/)() const | 다음 하위 파일, 유형, 오프셋 및 길이에 대한 정보를 포함합니다. 중요: 유형만 설정하면 오프셋과 길이는 자동으로 설정됩니다. |
| [GetBarcodeType](./getbarcodetype/)() override | USA DL (Pdf417)의 바코드 유형을 반환합니다. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | USA DL 데이터에서 코드텍스트를 구성합니다. |
| [InitFromString](./initfromstring/)(System::String) override | 코드텍스트에서 USA DL 객체를 초기화합니다. |
| [SaveToXml](./savetoxml/)(System::SharedPtr\<System::IO::Stream\>) | XML에 저장 |
| [set_AAMVAVersionNumber](./set_aamvaversionnumber/)(System::String) | AAMVA 버전 번호 00-99 |
| [set_IssuerIdentificationNumber](./set_issueridentificationnumber/)(System::String) | 이 번호는 발행 관할 구역을 고유하게 식별하며 ISO 발행 기관(AAMVA)에 문의하여 얻을 수 있습니다. 전체 6자리 IIN을 인코딩해야 합니다. |
| [set_JurisdictionSpecificSubfile](./set_jurisdictionspecificsubfile/)(System::SharedPtr\<USADriveIdJurisdSubfile\>) | 관할 구역별 필드 |
| [set_JurisdictionVersionNumber](./set_jurisdictionversionnumber/)(System::String) | 관할 구역 버전 번호 00-99 |
| [set_MandatoryElements](./set_mandatoryelements/)(System::SharedPtr\<USADriveIdCodetext::MandatoryFields\>) | 카드의 필수 요소(필드) |
| [set_NumberOfEntries](./set_numberofentries/)(int32_t) | 하위 파일 번호 00-99 |
| [set_OptionalElements](./set_optionalelements/)(System::SharedPtr\<USADriveIdCodetext::OptionalFields\>) | 카드의 선택적 요소(필드) |
| [set_SubfileDesignator](./set_subfiledesignator/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<USADriveIdCodetext::SubfileProperties\>>>) | 다음 하위 파일, 유형, 오프셋 및 길이에 대한 정보를 포함합니다. 중요: 유형만 설정하면 오프셋과 길이는 자동으로 설정됩니다. |
| [USADriveIdCodetext](./usadriveidcodetext/)() | 기본 생성자 |
## 또 보기

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
