---
title:  method
linktitle: Validate
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Validates a bracketed GS1 element string in the form (AI)value(AI)value without constructing an object. A literal ''('' inside a value must be written as (; no other escape sequence is supported, and '')'' does not require escaping in C++.'
type: docs
weight: 1400
url: /cpp/aspose.barcode.complexbarcode/gs1codetext/validate/
---
## GS1Codetext::Validate method


Validates a bracketed GS1 element string in the form (AI)value(AI)value without constructing an object. A literal '(' inside a value must be written as (; no other escape sequence is supported, and ')' does not require escaping.

```cpp
static System::SharedPtr<Common::GS1ValidationResult> Aspose::BarCode::ComplexBarcode::GS1Codetext::Validate(System::String value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | System::String | Bracketed GS1 element string to validate. |

### ReturnValue

Structured validation result.

## See Also

* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
