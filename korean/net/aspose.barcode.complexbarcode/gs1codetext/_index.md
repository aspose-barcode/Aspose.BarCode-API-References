---
title: "클래스 GS1Codetext"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.GS1Codetext 클래스. Application Identifier 요소의 정렬된 시퀀스로 인코딩 및 디코딩하기 위한 GS1 코덱스트를 나타냅니다. 원본 순서와 반복되는 Application Identifier가 보존됩니다. 괄호 표기법은 AIvalueAIvalue 형태를 가집니다. 값 내부의 리터럴 여는 괄호 '('는 '\\\\(' 로 작성해야 하며, 이는 지원되는 유일한 이스케이프 시퀀스입니다. 값 내부의 닫는 괄호 ')'는 이스케이프가 필요하지 않습니다."
type: docs
weight: 530
url: /ko/net/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class

GS1 코드텍스트를 인코딩 및 디코딩하기 위해 Application Identifier 요소들의 순서가 지정된 시퀀스로 나타냅니다. 원본 순서와 반복되는 Application Identifier가 보존됩니다. 괄호 표기는 (AI)value(AI)value 형태를 가집니다. 값 내부의 리터럴 여는 괄호 '('는 \\( 로 작성해야 합니다; 이것이 지원되는 유일한 이스케이프 시퀀스입니다. 값 내부의 닫는 괄호 ')'는 이스케이프가 필요하지 않습니다.

```csharp
public sealed class GS1Codetext : IComplexCodetext
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [GS1Codetext](gs1codetext/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/barcodetype/) { get; set; } | 이 GS1 코덱스트를 인코딩하는 데 사용되는 바코드 유형을 가져오거나 설정합니다. 지원되는 유형은 GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR 및 GS1 DataBar 유형입니다. 기본값은 GS1Code128입니다. |
| [Count](../../aspose.barcode.complexbarcode/gs1codetext/count/) { get; } | Application Identifier 요소의 개수를 가져옵니다. |
| [Elements](../../aspose.barcode.complexbarcode/gs1codetext/elements/) { get; } | 원본 순서대로 모든 요소의 복사본을 가져옵니다. |
| [Item](../../aspose.barcode.complexbarcode/gs1codetext/item/) { get; } | 정렬된 시퀀스에서 위치에 따라 요소를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Parse](../../aspose.barcode.complexbarcode/gs1codetext/parse/)(string) | 괄호로 묶인 GS1 요소 문자열을 (AI)value(AI)value 형태로 구문 분석합니다. 값 내부의 리터럴 '('는 '\\(' 로 작성해야 하며, 다른 이스케이프 시퀀스는 지원되지 않고, ')'는 이스케이프가 필요하지 않습니다. |
| [Add](../../aspose.barcode.complexbarcode/gs1codetext/add/)(string, string) | 검증된 Application Identifier 요소를 추가합니다. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1codetext/getall/)(string) | 원본 순서대로 Application Identifier의 모든 값을 가져옵니다. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/getbarcodetype/)() | 이 GS1 코덱스트를 인코딩하는 데 사용되는 바코드 유형을 가져옵니다. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1codetext/getconstructedcodetext/)() | 괄호로 묶인 GS1 코드 텍스트를 (AI)value(AI)value 형식으로 구성합니다. 값 안의 리터럴 여는 괄호는 \\(? 로 이스케이프됩니다. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1codetext/getfirst/)(string) | Application Identifier의 첫 번째 값을 가져옵니다. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1codetext/initfromstring/)(string) | 괄호로 묶인 GS1 코드 텍스트 (AI)value(AI)value 형식으로부터 이 인스턴스를 초기화합니다. 제공된 코드 텍스트가 성공적으로 파싱된 후에만 기존 요소가 교체됩니다. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1codetext/tostring/)() | 괄호로 묶인 GS1 표현을 (AI)value(AI)value 형식으로 반환합니다. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1codetext/tryparse/)(string, out GS1Codetext, out GS1ValidationResult) | 괄호로 묶인 GS1 요소 문자열을 (AI)value(AI)value 형식으로 파싱을 시도하고 구조화된 검증 오류를 반환합니다. 값 안의 리터럴 '('는 \\(? 로 작성해야 하며, 다른 이스케이프 시퀀스는 지원되지 않고 ')'는 이스케이프가 필요하지 않습니다. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1codetext/validate/)(string) | 괄호로 묶인 GS1 요소 문자열을 (AI)value(AI)value 형식으로 객체를 생성하지 않고 검증합니다. 값 안의 리터럴 '('는 \\(? 로 작성해야 하며, 다른 이스케이프 시퀀스는 지원되지 않고 ')'는 이스케이프가 필요하지 않습니다. |

### 또 보기

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


