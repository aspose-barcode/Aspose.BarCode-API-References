---
title: "GS1Codetext.TryParse"
second_title: "Aspose.BarCode for .NET API 참조"
description: "GS1Codetext 메서드. 괄호로 묶인 형태 AIvalueAIvalue인 GS1 요소 문자열을 구문 분석하려 시도하고 구조화된 검증 오류를 반환합니다. 값 안의 리터럴  은  로 작성해야 하며 다른 이스케이프 시퀀스는 지원되지 않고  은 이스케이프가 필요하지 않습니다."
type: docs
weight: 140
url: /ko/net/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext.TryParse method

괄호로 묶인 GS1 요소 문자열을 (AI)value(AI)value 형식으로 파싱을 시도하고 구조화된 검증 오류를 반환합니다. 값 안의 리터럴 '('는 \\(? 로 작성해야 하며, 다른 이스케이프 시퀀스는 지원되지 않고 ')'는 이스케이프가 필요하지 않습니다.

```csharp
public static bool TryParse(string value, out GS1Codetext result, 
    out GS1ValidationResult validationResult)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | String | 구문 분석할 괄호로 묶인 GS1 요소 문자열. |
| 결과 | GS1Codetext& | 이 메서드가 true를 반환하면 구문 분석된 GS1 코드텍스트를 포함하고; 그렇지 않으면 null을 반환합니다. |
| validationResult | GS1ValidationResult& | 검증 결과를 포함하거나, *value*가 null인 경우 null을 반환합니다 |

### 반환 값

구문 분석이 성공하면 true, 그렇지 않으면 false.

### 또 보기

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


