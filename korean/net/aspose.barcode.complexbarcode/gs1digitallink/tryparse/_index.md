---
title: "GS1DigitalLink.TryParse"
second_title: "Aspose.BarCode for .NET API 참조"
description: "GS1DigitalLink 메서드. 압축되지 않은 GS1 Digital Link URI를 구문 분석하려 시도하고 구조화된 검증 오류를 반환합니다"
type: docs
weight: 190
url: /ko/net/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink.TryParse method

압축되지 않은 GS1 디지털 링크 URI를 구문 분석하려 시도하고 구조화된 검증 오류를 반환합니다.

```csharp
public static bool TryParse(string value, out GS1DigitalLink result, 
    out GS1ValidationResult validationResult)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | String | 구문 분석할 GS1 Digital Link URI. |
| 결과 | GS1DigitalLink& | 이 메서드가 true를 반환하면 구문 분석된 GS1 Digital Link를 포함합니다; 그렇지 않으면 null입니다. |
| validationResult | GS1ValidationResult& | 검증 결과를 포함하거나, *value*가 null인 경우 null을 반환합니다 |

### 반환 값

구문 분석이 성공하면 true, 그렇지 않으면 false.

### 또 보기

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


