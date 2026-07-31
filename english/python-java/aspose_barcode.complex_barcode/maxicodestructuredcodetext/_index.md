---
title: "MaxiCodeStructuredCodetext Class"
linktitle: "MaxiCodeStructuredCodetext"
articleTitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for Python via Java"
description: "Base class for encoding and decoding the text embedded in the MaxiCode code for modes 2 and 3."
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

**Module:** `aspose_barcode.complex_barcode.maxi_code_structured_codetext`

**Inherits:** `MaxiCodeCodetext`


Base class for encoding and decoding the text embedded in the MaxiCode code for modes 2 and 3.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](./maxicodestructuredcodetext/) | Reimplemented from IComplexCodetext. |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__eq__](./__eq__/) | `bool` | No | Returns a value indicating whether this instance is equal to a specified MaxiCodeStructuredCodetext value. |
| [__hash__](./__hash__/) | `int` | No | Returns the hash code for this instance. |
| [constructed_codetext](./constructed_codetext/) | `Optional[str]` | No | Constructs codetext. |
| [init_from_string](./init_from_string/) | `None` | No | Initializes instance from constructed codetext. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [country_code](./country_code/) | `int` | Identifies 3 digit country code. |
| [postal_code](./postal_code/) | `Optional[str]` | Identifies the postal code. Must be 9 digits in mode 2 or 6 alphanumeric symbols in mode 3. |
| [second_message](./second_message/) | `Optional[MaxiCodeSecondMessage]` | Identifies second message of the barcode. |
| [service_category](./service_category/) | `int` | Identifies 3 digit service category. |
