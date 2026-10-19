---
title: GS1ValidationErrorCode
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
url: /python-net/aspose.barcode.common/gs1validationerrorcode/
---

## GS1ValidationErrorCode enumeration

Identifies a GS1 element string, Digital Link URI or value validation error.

## Members
| Member name | Description |
| :- | :- |
|EMPTY_ELEMENT_STRING|The supplied GS1 element string is empty.|
|MISSING_OPENING_PARENTHESIS|An opening parenthesis that should begin an Application Identifier is missing.|
|MISSING_CLOSING_PARENTHESIS|An Application Identifier has no closing parenthesis.|
|INVALID_APPLICATION_IDENTIFIER|An Application Identifier does not contain two to four ASCII digits.|
|UNKNOWN_APPLICATION_IDENTIFIER|The supplied Application Identifier is not defined by the supported GS1 Syntax Dictionary.|
|MISSING_VALUE|An Application Identifier is present without a value.|
|INVALID_ESCAPE_SEQUENCE|A value contains an unsupported escape sequence. Only \( is supported.|
|VALUE_TOO_SHORT|A value is shorter than the minimum length defined for its Application Identifier.|
|VALUE_TOO_LONG|A value is longer than the maximum length defined for its Application Identifier.|
|INVALID_CHARACTER|A value contains a character outside the character set permitted for its component.|
|INVALID_CHECKSUM|A numeric or alphabetic checksum is invalid.|
|INVALID_DATE|A date component is not a meaningful date under the rules defined for its Application Identifier.|
|INVALID_TIME|A time component is outside its permitted range or has an invalid structure.|
|INVALID_CODE_LIST_VALUE|A component value is not present in its permitted closed code list.|
|INVALID_COMPONENT_LENGTH|A component does not satisfy its component-specific length structure.|
|TRUNCATED_COMPONENT|A fixed-length component ends before all required characters are present.|
|UNEXPECTED_DATA|Data remains after all components defined for the Application Identifier have been consumed.|
|INVALID_VALUE|A component violates a content rule that has no more specific validation error code.|
|GCP_PREFIX_TOO_SHORT|A component is too short to contain the minimum four-digit structural GS1 Company Prefix.|
|INVALID_GCP_PREFIX|The structural GS1 Company Prefix contains a character other than an ASCII digit.|
|INVALID_DIGITAL_LINK_URI|The supplied value is not a well-formed absolute GS1 Digital Link URI.|
|UNSUPPORTED_DIGITAL_LINK_SCHEME|A GS1 Digital Link URI uses a scheme other than HTTP or HTTPS.|
|MISSING_DIGITAL_LINK_PRIMARY_KEY|A GS1 Digital Link URI path does not contain a supported primary key.|
|INVALID_DIGITAL_LINK_PATH|A GS1 Digital Link URI path does not consist of valid AI and value pairs.|
|INVALID_DIGITAL_LINK_QUALIFIER|A path Application Identifier is not a permitted qualifier at that position.|
|INVALID_DIGITAL_LINK_QUERY_PARAMETER|A GS1 Digital Link query parameter is malformed.|
|APPLICATION_IDENTIFIER_NOT_ALLOWED_IN_DIGITAL_LINK|An Application Identifier is not permitted as a GS1 Digital Link data attribute.|
|INVALID_PERCENT_ENCODING|A GS1 Digital Link URI component contains malformed percent encoding.|
|MULTIPLE_DIGITAL_LINK_PRIMARY_KEYS|More than one element could be selected as the GS1 Digital Link primary key.|
|UNSUPPORTED_ELEMENT_COMBINATION|The supplied combination of GS1 elements is not supported by the selected symbology or encoding mode.|

### See Also

* namespace [aspose.barcode.common](/barcode/python-net/aspose.barcode.common/)
* assembly [Aspose.BarCode](/barcode/python-net/)

