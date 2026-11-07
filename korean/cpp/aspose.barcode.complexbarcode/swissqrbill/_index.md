---
title: "Aspose::BarCode::ComplexBarcode::SwissQRBill class"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::SwissQRBill class. C++에서 SwissQR 청구서 데이터."
type: docs
weight: 2700
url: /ko/cpp/aspose.barcode.complexbarcode/swissqrbill/
---
## SwissQRBill class


SwissQR 청구서 데이터

```cpp
class SwissQRBill : public System::IEquatable<System::SharedPtr<SwissQRBill>>
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [CreateAndSetCreditorReference](./createandsetcreditorreference/)(System::String) | 원시 문자열에 "RF"를 접두사로 붙이고 modulo 97 체크섬을 적용하여 ISO11649 채권자 참조를 생성하고 설정합니다. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 지정된 객체가 현재 객체와 같은지 여부를 결정합니다. |
| [Equals](./equals/)(System::SharedPtr\<SwissQRBill\>) override | 지정된 청구서가 현재 청구서와 동일한지 여부를 결정합니다. |
| [get_Account](./get_account/)() const | 채권자의 계좌 번호를 가져옵니다. |
| [get_AlternativeSchemes](./get_alternativeschemes/)() const | 대체 결제 방식을 가져오거나 설정합니다. |
| [get_Amount](./get_amount/)() const | 결제 금액을 가져옵니다. |
| [get_BillInformation](./get_billinformation/)() const | 추가 구조화된 청구서 정보를 가져옵니다. |
| [get_Creditor](./get_creditor/)() const | 채권자 주소를 가져옵니다. |
| [get_Currency](./get_currency/)() const | 결제 통화를 가져옵니다. |
| [get_Debtor](./get_debtor/)() const | 채무자 주소를 가져옵니다. |
| [get_Reference](./get_reference/)() const | 채권자 결제 참조를 가져옵니다. |
| [get_UnstructuredMessage](./get_unstructuredmessage/)() const | 추가 비구조화 메시지를 가져옵니다. |
| [get_Version](./get_version/)() const | SwissQR 청구서 표준 버전을 가져옵니다. |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 가져옵니다. |
| [set_Account](./set_account/)(System::String) | 채권자의 계좌 번호를 설정합니다. |
| [set_AlternativeSchemes](./set_alternativeschemes/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<AlternativeScheme\>>>) | 대체 결제 방식을 가져오거나 설정합니다. |
| [set_Amount](./set_amount/)(System::Decimal) | 결제 금액을 설정합니다. |
| [set_BillInformation](./set_billinformation/)(System::String) | 추가 구조화된 청구서 정보를 설정합니다. |
| [set_Creditor](./set_creditor/)(System::SharedPtr\<Address\>) | 채권자 주소를 설정합니다. |
| [set_Currency](./set_currency/)(System::String) | 결제 통화를 설정합니다. |
| [set_Debtor](./set_debtor/)(System::SharedPtr\<Address\>) | 채무자 주소를 설정합니다. |
| [set_Reference](./set_reference/)(System::String) | 채권자 결제 참조를 설정합니다. |
| [set_UnstructuredMessage](./set_unstructuredmessage/)(System::String) | 추가 비구조화 메시지를 설정합니다. |
| [set_Version](./set_version/)(SwissQRBill::QrBillStandardVersion) | SwissQR 청구서 표준의 버전을 설정합니다. |
## Typedefs

| 타입 정의 | 설명 |
| --- | --- |
| [QrBillStandardVersion](./qrbillstandardversion/) | SwissQR 청구서 표준 버전 |
## 또 보기

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
