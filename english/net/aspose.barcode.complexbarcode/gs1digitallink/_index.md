---
title: Class GS1DigitalLink
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.ComplexBarcode.GS1DigitalLink class. Represents GS1 Digital Link codetext for encoding and decoding as an ordered sequence of Application Identifier elements. Source order and repeated Application Identifiers are preserved. The constructed codetext is an uncompressed GS1 Digital Link URI. NonGS1 query parameters and URI fragments are ignored when parsing
type: docs
weight: 540
url: /net/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class

Represents GS1 Digital Link codetext for encoding and decoding as an ordered sequence of Application Identifier elements. Source order and repeated Application Identifiers are preserved. The constructed codetext is an uncompressed GS1 Digital Link URI. Non-GS1 query parameters and URI fragments are ignored when parsing.

```csharp
public sealed class GS1DigitalLink : IComplexCodetext
```

## Constructors

| Name | Description |
| --- | --- |
| [GS1DigitalLink](gs1digitallink/#constructor)(string) | Initializes an empty GS1 Digital Link with the specified URI stem. The primary key is selected automatically when exactly one primary-key candidate is present. |
| [GS1DigitalLink](gs1digitallink/#constructor_1)(string, string) | Initializes an empty GS1 Digital Link with the specified URI stem and primary key. |

## Properties

| Name | Description |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/barcodetype/) { get; set; } | Gets or sets the barcode type used to encode this GS1 Digital Link. Supported types are QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF and Code128. The default value is QR. |
| [Count](../../aspose.barcode.complexbarcode/gs1digitallink/count/) { get; } | Gets the number of Application Identifier elements. |
| [Elements](../../aspose.barcode.complexbarcode/gs1digitallink/elements/) { get; } | Gets a copy of all elements in source order. |
| [Item](../../aspose.barcode.complexbarcode/gs1digitallink/item/) { get; } | Gets an element by its position in the ordered sequence. |
| [PrimaryApplicationIdentifier](../../aspose.barcode.complexbarcode/gs1digitallink/primaryapplicationidentifier/) { get; } | Gets the Application Identifier used as the Digital Link primary key. Null means that the primary key is selected automatically when the URI is constructed. |
| [UriStem](../../aspose.barcode.complexbarcode/gs1digitallink/uristem/) { get; } | Gets the absolute URI prefix before the GS1 primary key path segment. The stem does not contain a query string or fragment. |

## Methods

| Name | Description |
| --- | --- |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create)(string, GS1Codetext) | Creates a GS1 Digital Link by copying all elements from GS1 codetext and selecting the only available primary key. |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create_1)(string, GS1Codetext, string) | Creates a GS1 Digital Link by copying all elements from GS1 codetext and using the specified primary key. |
| static [Parse](../../aspose.barcode.complexbarcode/gs1digitallink/parse/)(string) | Parses an uncompressed GS1 Digital Link URI. |
| [Add](../../aspose.barcode.complexbarcode/gs1digitallink/add/)(string, string) | Appends a validated Application Identifier element. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1digitallink/getall/)(string) | Gets all values for an Application Identifier in source order. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/getbarcodetype/)() | Gets the barcode type used to encode this GS1 Digital Link. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1digitallink/getconstructedcodetext/)() | Constructs the uncompressed GS1 Digital Link URI. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1digitallink/getfirst/)(string) | Gets the first value for an Application Identifier. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1digitallink/initfromstring/)(string) | Initializes this instance from an uncompressed GS1 Digital Link URI. Existing state is replaced only after the supplied URI has been parsed successfully. The selected barcode type is preserved. |
| [ToGS1Codetext](../../aspose.barcode.complexbarcode/gs1digitallink/togs1codetext/)() | Creates an independent GS1 codetext containing the current GS1 elements. URI-only information is not included. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1digitallink/tostring/)() | Returns the uncompressed GS1 Digital Link URI. |
| [ToUriString](../../aspose.barcode.complexbarcode/gs1digitallink/touristring/)() | Formats the current object state as an uncompressed GS1 Digital Link URI. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1digitallink/tryparse/)(string, out GS1DigitalLink, out GS1ValidationResult) | Attempts to parse an uncompressed GS1 Digital Link URI and returns structured validation errors. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1digitallink/validate/)(string) | Validates an uncompressed GS1 Digital Link URI without constructing an object. |

### See Also

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


