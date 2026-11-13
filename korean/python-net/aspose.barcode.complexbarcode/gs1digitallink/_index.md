---
title: "GS1DigitalLink"
second_title: "Aspose.BarCode for Python via .NET API 참조"
description: 
type: docs
url: /ko/python-net/aspose.barcode.complexbarcode/gs1digitallink/
---

## GS1DigitalLink class

GS1 Digital Link 코드텍스트를 인코딩 및 디코딩하기 위해 순서가 지정된 Application Identifier 요소들의 시퀀스로 나타냅니다.<br/>            원본 순서와 반복되는 Application Identifier는 유지됩니다.<br/>            구성된 코드텍스트는 압축되지 않은 GS1 Digital Link URI입니다.<br/>            파싱 시 비-GS1 쿼리 매개변수와 URI 조각은 무시됩니다.

GS1DigitalLink 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| GS1DigitalLink(uri_stem) | GS1DigitalLink 클래스의 새 인스턴스를 초기화합니다 |
| GS1DigitalLink(uri_stem, primary_application_identifier) | GS1DigitalLink 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| uri_stem | GS1 기본 키 경로 세그먼트 앞의 절대 URI 접두사를 가져옵니다.<br/>            스템에는 쿼리 문자열이나 프래그먼트가 포함되지 않습니다. |
| primary_application_identifier | 디지털 링크 기본 키로 사용되는 애플리케이션 식별자를 가져옵니다.<br/>            Null은 URI가 구성될 때 기본 키가 자동으로 선택된다는 의미입니다. |
| barcode_type | 이 GS1 Digital Link를 인코딩하는 데 사용되는 바코드 유형을 가져오거나 설정합니다.<br/>            지원되는 유형은 QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF 및 Code128입니다.<br/>            기본값은 QR입니다. |
| count | 애플리케이션 식별자 요소의 수를 가져옵니다. |
| 요소 | 원본 순서대로 모든 요소의 복사본을 가져옵니다. |
## Indexer
| 이름 | 설명 |
| :- | :- |
| [index] | 정렬된 순서에서 위치에 따라 요소를 가져옵니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| create(uri_stem, codetext) | GS1 코덱스트에서 모든 요소를 복사하고<br/>            유일한 사용 가능한 기본 키를 선택합니다. |
| create(uri_stem, codetext, primary_application_identifier) | GS1 코덱스트에서 모든 요소를 복사하고<br/>            유일한 사용 가능한 기본 키를 선택합니다. |
| get_first(application_identifier) | Application Identifier의 첫 번째 값을 가져옵니다. |
| get_all(application_identifier) | Application Identifier의 모든 값을 원본 순서대로 가져옵니다. |
| add(application_identifier, value) | 검증된 Application Identifier 요소를 추가합니다. |
| validate(value) | 객체를 생성하지 않고 압축되지 않은 GS1 디지털 링크 URI를 검증합니다. |
| parse(value) | 압축되지 않은 GS1 디지털 링크 URI를 구문 분석합니다. |
| try_parse(value, result, validation_result) | 압축되지 않은 GS1 디지털 링크 URI를 구문 분석하려 시도하고 구조화된 검증 오류를 반환합니다. |
| to_gs1_codetext() | 현재 GS1 요소를 포함하는 독립적인 GS1 코덱스트를 생성합니다.<br/>            URI 전용 정보는 포함되지 않습니다. |
| to_uri_string() | 현재 객체 상태를 압축되지 않은 GS1 디지털 링크 URI 형식으로 변환합니다. |
| get_constructed_codetext() | 압축되지 않은 GS1 디지털 링크 URI를 구성합니다. |
| init_from_string(constructed_codetext) | 압축되지 않은 GS1 디지털 링크 URI에서 이 인스턴스를 초기화합니다.<br/>            제공된 URI가 성공적으로 구문 분석된 후에만 기존 상태가 교체됩니다.<br/>            선택된 바코드 유형이 유지됩니다. |
| get_barcode_type() | 이 GS1 디지털 링크를 인코딩하는 데 사용된 바코드 유형을 가져옵니다. |

### 또 보기

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

