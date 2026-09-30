---
title: GS1Codetext.TryParse
second_title: Aspose.BarCode for .NET API Reference
description: GS1Codetext method. Attempts to parse a bracketed GS1 element string in the form AIvalueAIvalue and returns structured validation errors. A literal  inside a value must be written as  no other escape sequence is supported and  does not require escaping
type: docs
weight: 140
url: /net/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext.TryParse method

Attempts to parse a bracketed GS1 element string in the form (AI)value(AI)value and returns structured validation errors. A literal '(' inside a value must be written as \(; no other escape sequence is supported, and ')' does not require escaping.

```csharp
public static bool TryParse(string value, out GS1Codetext result, 
    out GS1ValidationResult validationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| value | String | Bracketed GS1 element string to parse. |
| result | GS1Codetext& | When this method returns true, contains the parsed GS1 codetext; otherwise null. |
| validationResult | GS1ValidationResult& | Contains the validation result, or null when *value* is null. |

### Return Value

True when parsing succeeds; otherwise false.

### See Also

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


