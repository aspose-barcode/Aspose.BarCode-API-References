---
title: "GS1Codetext"
second_title: "Aspose.BarCode for Python via .NET API 참조"
description: 
type: docs
url: /ko/python-net/aspose.barcode.complexbarcode/gs1codetext/
---

## GS1Codetext class

GS1 코드텍스트를 인코딩 및 디코딩하기 위해 순서가 지정된 Application Identifier 요소들의 시퀀스로 나타냅니다.<br/>            원본 순서와 반복되는 Application Identifier는 유지됩니다. 괄호 표기는 (AI)value(AI)value 형태입니다.<br/>            값 안에 리터럴 여는 괄호 '('는 \( 로 작성해야 하며, 이것이 지원되는 유일한 이스케이프 시퀀스입니다.<br/>            값 안에 닫는 괄호 ')'는 이스케이프가 필요하지 않습니다.

GS1Codetext 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| GS1Codetext() | GS1Codetext 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| barcode_type | 이 GS1 코드텍스트를 인코딩하는 데 사용되는 바코드 유형을 가져오거나 설정합니다.<br/>            지원되는 유형은 GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix,<br/>            GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR 및 GS1 DataBar 유형입니다.<br/>            기본값은 GS1Code128입니다. |
| count | 애플리케이션 식별자 요소의 수를 가져옵니다. |
| 요소 | 원본 순서대로 모든 요소의 복사본을 가져옵니다. |
## Indexer
| 이름 | 설명 |
| :- | :- |
| [index] | 정렬된 순서에서 위치에 따라 요소를 가져옵니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| get_first(application_identifier) | Application Identifier의 첫 번째 값을 가져옵니다. |
| get_all(application_identifier) | Application Identifier의 모든 값을 원본 순서대로 가져옵니다. |
| add(application_identifier, value) | 검증된 Application Identifier 요소를 추가합니다. |
| validate(value) | 객체를 생성하지 않고 (AI)value(AI)value 형식의 괄호로 묶인 GS1 요소 문자열을 검증합니다.<br/>            값 내부에 있는 리터럴 '('는 \( 로 작성해야 합니다. 다른 이스케이프 시퀀스는 지원되지 않으며, ')'는 이스케이프가 필요하지 않습니다. |
| parse(value) | 괄호로 묶인 GS1 요소 문자열을 (AI)value(AI)value 형식으로 구문 분석합니다. 값 내부에 있는 리터럴<br/>            '('는 \( 로 작성해야 합니다. 다른 이스케이프 시퀀스는 지원되지 않으며,<br/>            ')'는 이스케이프가 필요하지 않습니다. |
| try_parse(value, result, validation_result) | 괄호로 묶인 GS1 요소 문자열을 (AI)value(AI)value 형식으로 구문 분석을 시도하고 구조화된 검증 오류를 반환합니다.<br/>            값 내부에 있는 리터럴 '('는<br/>            \( 로 작성해야 합니다. 다른 이스케이프 시퀀스는 지원되지 않으며, ')'는 이스케이프가 필요하지<br/>            않습니다. |
| get_constructed_codetext() | 괄호로 묶인 GS1 코드텍스트를 (AI)value(AI)value 형식으로 구성합니다.<br/>            값 내부의 리터럴 여는 괄호는 \( 로 이스케이프됩니다. |
| init_from_string(constructed_codetext) | 이 인스턴스를 (AI)value(AI)value 형식의 괄호로 묶인 GS1 코드텍스트에서 초기화합니다.<br/>            제공된 코드텍스트가 성공적으로 구문 분석된 후에만 기존 요소가 교체됩니다. |
| get_barcode_type() | 이 GS1 코드텍스트를 인코딩하는 데 사용되는 바코드 유형을 가져옵니다. |

### 또 보기

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

