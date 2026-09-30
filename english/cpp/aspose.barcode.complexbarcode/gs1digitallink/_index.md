---
title: Aspose::BarCode::ComplexBarcode::GS1DigitalLink class
linktitle: GS1DigitalLink
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::GS1DigitalLink class. Represents GS1 Digital Link codetext for encoding and decoding as an ordered sequence of Application Identifier elements. Source order and repeated Application Identifiers are preserved. The constructed codetext is an uncompressed GS1 Digital Link URI. Non-GS1 query parameters and URI fragments are ignored when parsing in C++.'
type: docs
weight: 600
url: /cpp/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class


Represents GS1 Digital Link codetext for encoding and decoding as an ordered sequence of Application Identifier elements. Source order and repeated Application Identifiers are preserved. The constructed codetext is an uncompressed GS1 Digital Link URI. Non-GS1 query parameters and URI fragments are ignored when parsing.

```cpp
class GS1DigitalLink : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Appends a validated Application Identifier element. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>) | Creates a GS1 Digital Link by copying all elements from GS1 codetext and selecting the only available primary key. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>, System::String) | Creates a GS1 Digital Link by copying all elements from GS1 codetext and using the specified primary key. |
| [get_BarcodeType](./get_barcodetype/)() const | Gets the barcode type used to encode this GS1 Digital Link. Supported types are QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF and Code128. The default value is QR. |
| [get_Count](./get_count/)() | Gets the number of Application Identifier elements. |
| [get_Elements](./get_elements/)() | Gets a copy of all elements in source order. |
| [get_PrimaryApplicationIdentifier](./get_primaryapplicationidentifier/)() const | Gets the Application Identifier used as the Digital Link primary key. Null means that the primary key is selected automatically when the URI is constructed. |
| [get_UriStem](./get_uristem/)() const | Gets the absolute URI prefix before the GS1 primary key path segment. The stem does not contain a query string or fragment. |
| [GetAll](./getall/)(System::String) | Gets all values for an Application Identifier in source order. |
| [GetBarcodeType](./getbarcodetype/)() override | Gets the barcode type used to encode this GS1 Digital Link. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Constructs the uncompressed GS1 Digital Link URI. |
| [GetFirst](./getfirst/)(System::String) | Gets the first value for an Application Identifier. |
| [GS1DigitalLink](./gs1digitallink/)(System::String) | Initializes an empty GS1 Digital Link with the specified URI stem. The primary key is selected automatically when exactly one primary-key candidate is present. |
| [GS1DigitalLink](./gs1digitallink/)(System::String, System::String) | Initializes an empty GS1 Digital Link with the specified URI stem and primary key. |
| [idx_get](./idx_get/)(int32_t) | Gets an element by its position in the ordered sequence. |
| [InitFromString](./initfromstring/)(System::String) override | Initializes this instance from an uncompressed GS1 Digital Link URI. Existing state is replaced only after the supplied URI has been parsed successfully. The selected barcode type is preserved. |
| static [Parse](./parse/)(System::String) | Parses an uncompressed GS1 Digital Link URI. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Sets the barcode type used to encode this GS1 Digital Link. Supported types are QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF and Code128. The default value is QR. |
| [ToGS1Codetext](./togs1codetext/)() | Creates an independent GS1 codetext containing the current GS1 elements. URI-only information is not included. |
| [ToString](./tostring/)() const override | Returns the uncompressed GS1 Digital Link URI. |
| [ToUriString](./touristring/)() | Formats the current object state as an uncompressed GS1 Digital Link URI. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1DigitalLink\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Attempts to parse an uncompressed GS1 Digital Link URI and returns structured validation errors. |
| static [Validate](./validate/)(System::String) | Validates an uncompressed GS1 Digital Link URI without constructing an object. |
## See Also

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
