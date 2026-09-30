---
title:  enum
linktitle: GS1ValidationErrorCode
second_title: Aspose.BarCode for C++ API Reference
description: ' enum. Identifies a GS1 element string, Digital Link URI or value validation error in C++.'
type: docs
weight: 600
url: /cpp/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enum


Identifies a GS1 element string, Digital Link URI or value validation error.

```cpp
enum class GS1ValidationErrorCode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| EmptyElementString | 0 | The supplied GS1 element string is empty. |
| MissingOpeningParenthesis | 1 | An opening parenthesis that should begin an Application Identifier is missing. |
| MissingClosingParenthesis | 2 | An Application Identifier has no closing parenthesis. |
| InvalidApplicationIdentifier | 3 | An Application Identifier does not contain two to four ASCII digits. |
| UnknownApplicationIdentifier | 4 | The supplied Application Identifier is not defined by the supported GS1 Syntax Dictionary. |
| MissingValue | 5 | An Application Identifier is present without a value. |
| InvalidEscapeSequence | 6 | A value contains an unsupported escape sequence. Only ( is supported. |
| ValueTooShort | 7 | A value is shorter than the minimum length defined for its Application Identifier. |
| ValueTooLong | 8 | A value is longer than the maximum length defined for its Application Identifier. |
| InvalidCharacter | 9 | A value contains a character outside the character set permitted for its component. |
| InvalidChecksum | 10 | A numeric or alphabetic checksum is invalid. |
| InvalidDate | 11 | A date component is not a meaningful date under the rules defined for its Application Identifier. |
| InvalidTime | 12 | A time component is outside its permitted range or has an invalid structure. |
| InvalidCodeListValue | 13 | A component value is not present in its permitted closed code list. |
| InvalidComponentLength | 14 | A component does not satisfy its component-specific length structure. |
| TruncatedComponent | 15 | A fixed-length component ends before all required characters are present. |
| UnexpectedData | 16 | Data remains after all components defined for the Application Identifier have been consumed. |
| InvalidValue | 17 | A component violates a content rule that has no more specific validation error code. |
| GcpPrefixTooShort | 18 | A component is too short to contain the minimum four-digit structural GS1 Company Prefix. |
| InvalidGcpPrefix | 19 | The structural GS1 Company Prefix contains a character other than an ASCII digit. |
| InvalidDigitalLinkUri | 20 | The supplied value is not a well-formed absolute GS1 Digital Link URI. |
| UnsupportedDigitalLinkScheme | 21 | A GS1 Digital Link URI uses a scheme other than HTTP or HTTPS. |
| MissingDigitalLinkPrimaryKey | 22 | A GS1 Digital Link URI path does not contain a supported primary key. |
| InvalidDigitalLinkPath | 23 | A GS1 Digital Link URI path does not consist of valid AI and value pairs. |
| InvalidDigitalLinkQualifier | 24 | A path Application Identifier is not a permitted qualifier at that position. |
| InvalidDigitalLinkQueryParameter | 25 | A GS1 Digital Link query parameter is malformed. |
| ApplicationIdentifierNotAllowedInDigitalLink | 26 | An Application Identifier is not permitted as a GS1 Digital Link data attribute. |
| InvalidPercentEncoding | 27 | A GS1 Digital Link URI component contains malformed percent encoding. |
| MultipleDigitalLinkPrimaryKeys | 28 | More than one element could be selected as the GS1 Digital Link primary key. |
| UnsupportedElementCombination | 29 | The supplied combination of GS1 elements is not supported by the selected symbology or encoding mode. |

## See Also

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)
