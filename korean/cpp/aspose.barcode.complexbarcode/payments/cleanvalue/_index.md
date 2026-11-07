---
title: "메서드"
linktitle: "CleanValue"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " method. 문자열 값을 정리하여 C++에서 Swiss Payment Standards 2018에 적합하도록 만듭니다."
type: docs
weight: 100
url: /ko/cpp/aspose.barcode.complexbarcode/payments/cleanvalue/
---
## Payments::CleanValue method


스위스 결제 표준 2018에 적합하도록 문자열 값을 정리합니다.

```cpp
static void Aspose::BarCode::ComplexBarcode::Payments::CleanValue(System::String value, Payments::CleaningResult &result)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | System::String | 정리할 문자열 값. |
| result | Payments::CleaningResult\& | 정리된 문자열과 플래그가 채워질 결과. |
## 비고


지원되지 않는 문자(Swiss Payment Standards 2018, ch. 2.4.1 및 부록 D에 따라)는 공백(지원되지 않는 공백) 또는 점(그 외 모든 지원되지 않는 문자)으로 대체됩니다. 앞뒤 공백이 제거됩니다.

0xff를 초과하는 문자가 감지되면, 문자열은 먼저 두 개의 코드 포인트로 표현된 움라우트 또는 악센트가 있는 문자를 하나의 코드 포인트로 병합하도록 정규화됩니다(가능한 경우). 이 중 일부는 유효해질 수 있습니다.

결과 문자열이 모두 공백이면 **null**이 반환됩니다.

## 또 보기

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
