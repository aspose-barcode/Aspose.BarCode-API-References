---
title: "열거형 GS1ValidationErrorCode"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Common.GS1ValidationErrorCode 열거형. GS1 요소 문자열 디지털 링크 URI 또는 값 검증 오류를 식별합니다."
type: docs
weight: 430
url: /ko/net/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enumeration

GS1 요소 문자열, Digital Link URI 또는 값 검증 오류를 식별합니다.

```csharp
public enum GS1ValidationErrorCode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| EmptyElementString | `0` | 제공된 GS1 요소 문자열이 비어 있습니다. |
| MissingOpeningParenthesis | `1` | Application Identifier를 시작해야 하는 여는 괄호가 누락되었습니다. |
| MissingClosingParenthesis | `2` | Application Identifier에 닫는 괄호가 없습니다. |
| InvalidApplicationIdentifier | `3` | Application Identifier에 2~4개의 ASCII 숫자가 포함되어 있지 않습니다. |
| UnknownApplicationIdentifier | `4` | 제공된 Application Identifier가 지원되는 GS1 구문 사전에서 정의되지 않았습니다. |
| MissingValue | `5` | Application Identifier가 값 없이 존재합니다. |
| InvalidEscapeSequence | `6` | 값에 지원되지 않는 이스케이프 시퀀스가 포함되어 있습니다. \\(만 지원됩니다. |
| ValueTooShort | `7` | 값이 해당 Application Identifier에 정의된 최소 길이보다 짧습니다. |
| ValueTooLong | `8` | 값이 해당 Application Identifier에 정의된 최대 길이보다 깁니다. |
| InvalidCharacter | `9` | 값에 해당 구성 요소에 허용된 문자 집합 외의 문자가 포함되어 있습니다. |
| InvalidChecksum | `10` | 숫자 또는 알파벳 체크섬이 유효하지 않습니다. |
| InvalidDate | `11` | 날짜 구성 요소가 해당 Application Identifier에 정의된 규칙에 따라 의미 있는 날짜가 아닙니다. |
| InvalidTime | `12` | 시간 구성 요소가 허용 범위를 벗어나거나 구조가 유효하지 않습니다. |
| InvalidCodeListValue | `13` | 구성 요소 값이 허용된 폐쇄 코드 목록에 존재하지 않습니다. |
| InvalidComponentLength | `14` | 구성 요소가 해당 구성 요소별 길이 구조를 만족하지 않습니다. |
| TruncatedComponent | `15` | 고정 길이 구성 요소가 모든 필수 문자가 존재하기 전에 종료됩니다. |
| UnexpectedData | `16` | Application Identifier에 정의된 모든 구성 요소가 처리된 후에도 데이터가 남아 있습니다. |
| InvalidValue | `17` | 구성 요소가 더 구체적인 검증 오류 코드가 없는 콘텐츠 규칙을 위반합니다. |
| GcpPrefixTooShort | `18` | 구성 요소가 최소 네 자리 구조적 GS1 회사 접두사를 포함하기에는 너무 짧습니다. |
| InvalidGcpPrefix | `19` | 구조적 GS1 회사 접두사는 ASCII 숫자가 아닌 문자를 포함하고 있습니다. |
| InvalidDigitalLinkUri | `20` | 제공된 값은 올바른 형식의 절대 GS1 Digital Link URI가 아닙니다. |
| UnsupportedDigitalLinkScheme | `21` | GS1 Digital Link URI가 HTTP 또는 HTTPS가 아닌 스킴을 사용하고 있습니다. |
| MissingDigitalLinkPrimaryKey | `22` | GS1 Digital Link URI 경로에 지원되는 기본 키가 포함되어 있지 않습니다. |
| InvalidDigitalLinkPath | `23` | GS1 Digital Link URI 경로가 유효한 AI 및 값 쌍으로 구성되어 있지 않습니다. |
| InvalidDigitalLinkQualifier | `24` | 경로의 Application Identifier는 해당 위치에서 허용되는 한정자가 아닙니다. |
| InvalidDigitalLinkQueryParameter | `25` | GS1 Digital Link 쿼리 매개변수가 잘못 형성되었습니다. |
| ApplicationIdentifierNotAllowedInDigitalLink | `26` | Application Identifier는 GS1 Digital Link 데이터 속성으로 허용되지 않습니다. |
| InvalidPercentEncoding | `27` | GS1 Digital Link URI 구성 요소에 잘못된 퍼센트 인코딩이 포함되어 있습니다. |
| MultipleDigitalLinkPrimaryKeys | `28` | 하나 이상의 요소가 GS1 Digital Link 기본 키로 선택될 수 있습니다. |
| UnsupportedElementCombination | `29` | 제공된 GS1 요소 조합은 선택된 심볼 또는 인코딩 모드에서 지원되지 않습니다. |

### 또 보기

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)


