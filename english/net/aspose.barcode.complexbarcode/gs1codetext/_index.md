---
title: Class GS1Codetext
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.ComplexBarcode.GS1Codetext class. Represents GS1 codetext for encoding and decoding as an ordered sequence of Application Identifier elements. Source order and repeated Application Identifiers are preserved. The bracketed representation has the form AIvalueAIvalue. A literal opening parenthesis  inside a value must be written as  this is the only supported escape sequence. A closing parenthesis  inside a value does not require escaping
type: docs
weight: 510
url: /net/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class

Represents GS1 codetext for encoding and decoding as an ordered sequence of Application Identifier elements. Source order and repeated Application Identifiers are preserved. The bracketed representation has the form (AI)value(AI)value. A literal opening parenthesis '(' inside a value must be written as \(; this is the only supported escape sequence. A closing parenthesis ')' inside a value does not require escaping.

```csharp
public sealed class GS1Codetext : IComplexCodetext
```

## Constructors

| Name | Description |
| --- | --- |
| [GS1Codetext](gs1codetext/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/barcodetype/) { get; set; } | Gets or sets the barcode type used to encode this GS1 codetext. Supported types are GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR and GS1 DataBar types. The default value is GS1Code128. |
| [Count](../../aspose.barcode.complexbarcode/gs1codetext/count/) { get; } | Gets the number of Application Identifier elements. |
| [Elements](../../aspose.barcode.complexbarcode/gs1codetext/elements/) { get; } | Gets a copy of all elements in source order. |
| [Item](../../aspose.barcode.complexbarcode/gs1codetext/item/) { get; } | Gets an element by its position in the ordered sequence. |

## Methods

| Name | Description |
| --- | --- |
| static [Parse](../../aspose.barcode.complexbarcode/gs1codetext/parse/)(string) | Parses a bracketed GS1 element string in the form (AI)value(AI)value. A literal '(' inside a value must be written as \(; no other escape sequence is supported, and ')' does not require escaping. |
| [Add](../../aspose.barcode.complexbarcode/gs1codetext/add/)(string, string) | Appends a validated Application Identifier element. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1codetext/getall/)(string) | Gets all values for an Application Identifier in source order. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/getbarcodetype/)() | Gets the barcode type used to encode this GS1 codetext. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1codetext/getconstructedcodetext/)() | Constructs the bracketed GS1 codetext in the form (AI)value(AI)value. Literal opening parentheses in values are escaped as \(. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1codetext/getfirst/)(string) | Gets the first value for an Application Identifier. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1codetext/initfromstring/)(string) | Initializes this instance from bracketed GS1 codetext in the form (AI)value(AI)value. Existing elements are replaced only after the supplied codetext has been parsed successfully. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1codetext/tostring/)() | Returns the bracketed GS1 representation in the form (AI)value(AI)value. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1codetext/tryparse/)(string, out GS1Codetext, out GS1ValidationResult) | Attempts to parse a bracketed GS1 element string in the form (AI)value(AI)value and returns structured validation errors. A literal '(' inside a value must be written as \(; no other escape sequence is supported, and ')' does not require escaping. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1codetext/validate/)(string) | Validates a bracketed GS1 element string in the form (AI)value(AI)value without constructing an object. A literal '(' inside a value must be written as \(; no other escape sequence is supported, and ')' does not require escaping. |

### See Also

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


