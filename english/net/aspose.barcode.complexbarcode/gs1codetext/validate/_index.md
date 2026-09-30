---
title: GS1Codetext.Validate
second_title: Aspose.BarCode for .NET API Reference
description: GS1Codetext method. Validates a bracketed GS1 element string in the form AIvalueAIvalue without constructing an object. A literal  inside a value must be written as  no other escape sequence is supported and  does not require escaping
type: docs
weight: 150
url: /net/aspose.barcode.complexbarcode/gs1codetext/validate/
---
## GS1Codetext.Validate method

Validates a bracketed GS1 element string in the form (AI)value(AI)value without constructing an object. A literal '(' inside a value must be written as \(; no other escape sequence is supported, and ')' does not require escaping.

```csharp
public static GS1ValidationResult Validate(string value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| value | String | Bracketed GS1 element string to validate. |

### Return Value

Structured validation result.

### See Also

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


