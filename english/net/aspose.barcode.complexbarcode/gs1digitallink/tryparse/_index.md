---
title: GS1DigitalLink.TryParse
second_title: Aspose.BarCode for .NET API Reference
description: GS1DigitalLink method. Attempts to parse an uncompressed GS1 Digital Link URI and returns structured validation errors
type: docs
weight: 190
url: /net/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink.TryParse method

Attempts to parse an uncompressed GS1 Digital Link URI and returns structured validation errors.

```csharp
public static bool TryParse(string value, out GS1DigitalLink result, 
    out GS1ValidationResult validationResult)
```

| Parameter | Type | Description |
| --- | --- | --- |
| value | String | GS1 Digital Link URI to parse. |
| result | GS1DigitalLink& | When this method returns true, contains the parsed GS1 Digital Link; otherwise null. |
| validationResult | GS1ValidationResult& | Contains the validation result, or null when *value* is null. |

### Return Value

True when parsing succeeds; otherwise false.

### See Also

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


