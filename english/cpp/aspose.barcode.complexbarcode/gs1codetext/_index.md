---
title: Aspose::BarCode::ComplexBarcode::GS1Codetext class
linktitle: GS1Codetext
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::GS1Codetext class. Represents GS1 codetext for encoding and decoding as an ordered sequence of Application Identifier elements. Source order and repeated Application Identifiers are preserved. The bracketed representation has the form (AI)value(AI)value. A literal opening parenthesis ''('' inside a value must be written as (; this is the only supported escape sequence. A closing parenthesis '')'' inside a value does not require escaping in C++.'
type: docs
weight: 500
url: /cpp/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class


Represents GS1 codetext for encoding and decoding as an ordered sequence of Application Identifier elements. Source order and repeated Application Identifiers are preserved. The bracketed representation has the form (AI)value(AI)value. A literal opening parenthesis '(' inside a value must be written as (; this is the only supported escape sequence. A closing parenthesis ')' inside a value does not require escaping.

```cpp
class GS1Codetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Appends a validated Application Identifier element. |
| [get_BarcodeType](./get_barcodetype/)() const | Gets the barcode type used to encode this GS1 codetext. Supported types are GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR and GS1 DataBar types. The default value is GS1Code128. |
| [get_Count](./get_count/)() | Gets the number of Application Identifier elements. |
| [get_Elements](./get_elements/)() | Gets a copy of all elements in source order. |
| [GetAll](./getall/)(System::String) | Gets all values for an Application Identifier in source order. |
| [GetBarcodeType](./getbarcodetype/)() override | Gets the barcode type used to encode this GS1 codetext. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Constructs the bracketed GS1 codetext in the form (AI)value(AI)value. Literal opening parentheses in values are escaped as (. |
| [GetFirst](./getfirst/)(System::String) | Gets the first value for an Application Identifier. |
| [GS1Codetext](./gs1codetext/)() | Initializes an empty GS1 codetext. |
| [idx_get](./idx_get/)(int32_t) | Gets an element by its position in the ordered sequence. |
| [InitFromString](./initfromstring/)(System::String) override | Initializes this instance from bracketed GS1 codetext in the form (AI)value(AI)value. Existing elements are replaced only after the supplied codetext has been parsed successfully. |
| static [Parse](./parse/)(System::String) | Parses a bracketed GS1 element string in the form (AI)value(AI)value. A literal '(' inside a value must be written as (; no other escape sequence is supported, and ')' does not require escaping. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Sets the barcode type used to encode this GS1 codetext. Supported types are GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR and GS1 DataBar types. The default value is GS1Code128. |
| [ToString](./tostring/)() const override | Returns the bracketed GS1 representation in the form (AI)value(AI)value. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1Codetext\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Attempts to parse a bracketed GS1 element string in the form (AI)value(AI)value and returns structured validation errors. A literal '(' inside a value must be written as (; no other escape sequence is supported, and ')' does not require escaping. |
| static [Validate](./validate/)(System::String) | Validates a bracketed GS1 element string in the form (AI)value(AI)value without constructing an object. A literal '(' inside a value must be written as (; no other escape sequence is supported, and ')' does not require escaping. |
## See Also

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
