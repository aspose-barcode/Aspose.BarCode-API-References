---
title:  method
linktitle: TryParse
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Attempts to parse a bracketed GS1 element string in the form (AI)value(AI)value and returns structured validation errors. A literal ''('' inside a value must be written as (; no other escape sequence is supported, and '')'' does not require escaping in C++.'
type: docs
weight: 1600
url: /cpp/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext::TryParse method


Attempts to parse a bracketed GS1 element string in the form (AI)value(AI)value and returns structured validation errors. A literal '(' inside a value must be written as (; no other escape sequence is supported, and ')' does not require escaping.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1Codetext::TryParse(System::String value, System::SharedPtr<GS1Codetext> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | System::String | Bracketed GS1 element string to parse. |
| result | System::SharedPtr\<GS1Codetext\>\& | When this method returns true, contains the parsed GS1 codetext; otherwise null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Contains the validation result, or null when *value*  is null. |

### ReturnValue

True when parsing succeeds; otherwise false.

## See Also

* Class [GS1Codetext](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
