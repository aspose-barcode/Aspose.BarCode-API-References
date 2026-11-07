---
title: "Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings 클래스"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings 클래스. AustraliaPost 디코딩 매개변수입니다. C++에서 AustraliaPost 심볼리즘의 인식된 데이터에 영향을 주는 매개변수를 포함합니다."
type: docs
weight: 200
url: /ko/cpp/aspose.barcode.barcoderecognition/australiapostsettings/
---
## AustraliaPostSettings class


AustraliaPost 디코딩 매개변수. AustraliaPost 심볼로지의 인식된 데이터에 영향을 주는 매개변수를 포함합니다.

```cpp
class AustraliaPostSettings : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_CustomerInformationDecoder](./get_customerinformationdecoder/)() const | AustraliaPost 심볼리즘에서 사용되는 고객 정보 필드 디코딩을 위한 공개 인터페이스입니다. |
| [get_CustomerInformationInterpretingType](./get_customerinformationinterpretingtype/)() const | AustralianPost의 고객 정보에 대한 해석 유형을 가져옵니다. [BarCode.Default](../checksumvalidation/)은 [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/)입니다. |
| [get_IgnoreEndingFillingPatternsForCTable](./get_ignoreendingfillingpatternsforctable/)() const | 디코딩 중에 CTable 방식으로 고객 정보 필드의 마지막 채우기 패턴을 무시하도록 AustraliaPost 디코더를 강제하는 플래그입니다. CTable 인코딩 방식은 인코딩 테이블에 빈틈이 없으며, 채우기 패턴 "333" 시퀀스는 문자 "z"로 디코딩됩니다. |
| [set_CustomerInformationDecoder](./set_customerinformationdecoder/)(System::SharedPtr\<AustraliaPostCustomerInformationDecoder\>) | AustraliaPost 심볼리즘에서 사용되는 고객 정보 필드 디코딩을 위한 공개 인터페이스입니다. |
| [set_CustomerInformationInterpretingType](./set_customerinformationinterpretingtype/)(Aspose::BarCode::CustomerInformationInterpretingType) | AustralianPost의 고객 정보에 대한 해석 유형을 설정합니다. [BarCode.Default](../checksumvalidation/)은 [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/)입니다. |
| [set_IgnoreEndingFillingPatternsForCTable](./set_ignoreendingfillingpatternsforctable/)(bool) | 디코딩 중에 CTable 방식으로 고객 정보 필드의 마지막 채우기 패턴을 무시하도록 AustraliaPost 디코더를 강제하는 플래그입니다. CTable 인코딩 방식은 인코딩 테이블에 빈틈이 없으며, 채우기 패턴 "333" 시퀀스는 문자 "z"로 디코딩됩니다. |
## 또 보기

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
