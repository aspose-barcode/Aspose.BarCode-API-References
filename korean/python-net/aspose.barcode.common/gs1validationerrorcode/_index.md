---
title: "GS1ValidationErrorCode"
second_title: "Aspose.Sildes for Python via .NET API Reference"
description: 
type: docs
url: /ko/python-net/aspose.barcode.common/gs1validationerrorcode/
---

## GS1ValidationErrorCode enumeration

GS1 요소 문자열, 디지털 링크 URI 또는 값 검증 오류를 식별합니다.

## Members
| 멤버 이름 | 설명 |
| :- | :- |
| EMPTY_ELEMENT_STRING | 제공된 GS1 요소 문자열이 비어 있습니다. |
| MISSING_OPENING_PARENTHESIS | Application Identifier를 시작해야 하는 여는 괄호가 누락되었습니다. |
| MISSING_CLOSING_PARENTHESIS | Application Identifier에 닫는 괄호가 없습니다. |
| INVALID_APPLICATION_IDENTIFIER | Application Identifier에 두 자리에서 네 자리 사이의 ASCII 숫자가 포함되어 있지 않습니다. |
| UNKNOWN_APPLICATION_IDENTIFIER | 제공된 Application Identifier는 지원되는 GS1 구문 사전에서 정의되지 않았습니다. |
| MISSING_VALUE | Application Identifier가 값 없이 존재합니다. |
| INVALID_ESCAPE_SEQUENCE | 값에 지원되지 않는 이스케이프 시퀀스가 포함되어 있습니다. 오직 \(만 지원됩니다. |
| VALUE_TOO_SHORT | 값이 해당 Application Identifier에 정의된 최소 길이보다 짧습니다. |
| VALUE_TOO_LONG | 값이 해당 Application Identifier에 정의된 최대 길이보다 깁니다. |
| INVALID_CHARACTER | 값에 해당 구성 요소에 허용된 문자 집합 밖의 문자가 포함되어 있습니다. |
| INVALID_CHECKSUM | 숫자 또는 알파벳 체크섬이 유효하지 않습니다. |
| INVALID_DATE | 날짜 구성 요소가 해당 Application Identifier에 정의된 규칙에 따라 의미 있는 날짜가 아닙니다. |
| INVALID_TIME | 시간 구성 요소가 허용된 범위를 벗어나거나 잘못된 구조를 가지고 있습니다. |
| INVALID_CODE_LIST_VALUE | 구성 요소 값이 허용된 폐쇄 코드 목록에 존재하지 않습니다. |
| INVALID_COMPONENT_LENGTH | 구성 요소가 해당 구성 요소별 길이 구조를 만족하지 않습니다. |
| TRUNCATED_COMPONENT | 고정 길이 구성 요소가 모든 필수 문자가 존재하기 전에 종료됩니다. |
| UNEXPECTED_DATA | Application Identifier에 대해 정의된 모든 구성 요소가 처리된 후에도 데이터가 남아 있습니다. |
| INVALID_VALUE | 구성 요소가 더 구체적인 검증 오류 코드를 갖지 않는 콘텐츠 규칙을 위반합니다. |
| GCP_PREFIX_TOO_SHORT | 구성 요소가 최소 4자리 구조 GS1 회사 접두사를 포함하기에는 너무 짧습니다. |
| INVALID_GCP_PREFIX | 구조적 GS1 회사 접두사에 ASCII 숫자가 아닌 문자가 포함되어 있습니다. |
| INVALID_DIGITAL_LINK_URI | 제공된 값이 올바르게 형식화된 절대 GS1 Digital Link URI가 아닙니다. |
| UNSUPPORTED_DIGITAL_LINK_SCHEME | GS1 Digital Link URI가 HTTP 또는 HTTPS가 아닌 스킴을 사용하고 있습니다. |
| MISSING_DIGITAL_LINK_PRIMARY_KEY | GS1 Digital Link URI 경로에 지원되는 기본 키가 포함되어 있지 않습니다. |
| INVALID_DIGITAL_LINK_PATH | GS1 Digital Link URI 경로가 유효한 AI와 값 쌍으로 구성되어 있지 않습니다. |
| INVALID_DIGITAL_LINK_QUALIFIER | 경로 Application Identifier가 해당 위치에서 허용된 한정자가 아닙니다. |
| INVALID_DIGITAL_LINK_QUERY_PARAMETER | GS1 디지털 링크 쿼리 매개변수가 잘못되었습니다. |
| APPLICATION_IDENTIFIER_NOT_ALLOWED_IN_DIGITAL_LINK | Application Identifier는 GS1 디지털 링크 데이터 속성으로 허용되지 않습니다. |
| INVALID_PERCENT_ENCODING | GS1 디지털 링크 URI 구성 요소에 잘못된 퍼센트 인코딩이 포함되어 있습니다. |
| MULTIPLE_DIGITAL_LINK_PRIMARY_KEYS | GS1 디지털 링크 기본 키로 하나 이상의 요소가 선택될 수 있습니다. |
| UNSUPPORTED_ELEMENT_COMBINATION | 제공된 GS1 요소 조합은 선택된 심볼 또는 인코딩 모드에서 지원되지 않습니다. |

### 또 보기

* namespace [aspose.barcode.common](/barcode/python-net/aspose.barcode.common/)
* assembly [Aspose.BarCode](/barcode/python-net/)

