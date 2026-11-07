---
title: "메서드"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " method. 괄호로 묶인 GS1 요소 문자열을 (AI)value(AI)value 형태로 구문 분석하려 시도하고 구조화된 검증 오류를 반환합니다. 값 내부에 있는 리터럴 ''(''는 ( 로 작성해야 하며, 다른 이스케이프 시퀀스는 지원되지 않고, '')''는 C++에서 이스케이프가 필요하지 않습니다."
type: docs
weight: 1600
url: /ko/cpp/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext::TryParse method


괄호로 묶인 GS1 요소 문자열을 (AI)value(AI)value 형식으로 구문 분석하려 시도하고 구조화된 검증 오류를 반환합니다. 값 내부에 있는 리터럴 '('는 ( 로 작성해야 하며, 다른 이스케이프 시퀀스는 지원되지 않고 ')'는 이스케이프가 필요하지 않습니다.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1Codetext::TryParse(System::String value, System::SharedPtr<GS1Codetext> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | System::String | 구문 분석할 괄호로 묶인 GS1 요소 문자열. |
| result | System::SharedPtr\<GS1Codetext\>\& | 이 메서드가 true를 반환하면 구문 분석된 GS1 코드텍스트를 포함하고; 그렇지 않으면 null입니다. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | 검증 결과를 포함합니다, 또는 *value*가 null일 때 null입니다. |

### ReturnValue

파싱이 성공하면 true; 그렇지 않으면 false.

## 또 보기

* Class [GS1Codetext](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
