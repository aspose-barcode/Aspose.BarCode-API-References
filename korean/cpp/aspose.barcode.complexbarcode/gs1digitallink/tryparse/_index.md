---
title: "메서드"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " method. 압축되지 않은 GS1 디지털 링크 URI를 파싱하려 시도하고 C++에서 구조화된 검증 오류를 반환합니다."
type: docs
weight: 2000
url: /ko/cpp/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink::TryParse method


압축되지 않은 GS1 Digital Link URI를 파싱하려 시도하고 구조화된 검증 오류를 반환합니다.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1DigitalLink::TryParse(System::String value, System::SharedPtr<GS1DigitalLink> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | System::String | 파싱할 GS1 디지털 링크 URI. |
| result | System::SharedPtr\<GS1DigitalLink\>\& | 이 메서드가 true를 반환하면 파싱된 GS1 디지털 링크를 포함합니다; 그렇지 않으면 null입니다. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | 검증 결과를 포함합니다, 또는 *value*가 null일 때 null입니다. |

### ReturnValue

파싱이 성공하면 true; 그렇지 않으면 false.

## 또 보기

* Class [GS1DigitalLink](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
