---
title: "Aspose::BarCode::ComplexBarcode::Payments 클래스"
linktitle: "Payments"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::ComplexBarcode::Payments 클래스. C++에서 스위스 결제 표준과 관련된 필드 검증."
type: docs
weight: 2400
url: /ko/cpp/aspose.barcode.complexbarcode/payments/
---
## Payments class


스위스 결제 표준과 관련된 필드 검증.

```cpp
class Payments
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static [CleanValue](./cleanvalue/)(System::String, Payments::CleaningResult\&) | 스위스 결제 표준 2018에 적합하도록 문자열 값을 정리합니다. |
| static [CreateIso11649Reference](./createiso11649reference/)(System::String) | 문자열 앞에 "RF"를 붙이고 모듈로 97 체크섬을 적용하여 원시 문자열에서 ISO11649 채권자 참조를 생성합니다. |
| static [FormatIban](./formatiban/)(System::String) | 공백을 삽입하여 IBAN 또는 채권자 참조를 포맷합니다. |
| static [FormatQrReferenceNumber](./formatqrreferencenumber/)(System::String) | 공백을 삽입하여 QR 참조 번호를 포맷합니다. |
| static [IsAlphaNumeric](./isalphanumeric/)(System::String) |  |
| static [IsValidIban](./isvalidiban/)(System::String) | 문자열이 유효한 IBAN 번호인지 검증합니다. |
| static [IsValidIso11649Reference](./isvalidiso11649reference/)(System::String) | 문자열이 유효한 ISO 11649 참조 번호인지 검증합니다. |
| static [IsValidQrReference](./isvalidqrreference/)(System::String) | 문자열이 유효한 QR 참조인지 검증합니다. |
| [Payments](./payments/)() |  |
## 또 보기

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
