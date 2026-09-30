---
title: GS1DigitalLink
second_title: Aspose.BarCode for Python via .NET API Reference
description: 
type: docs
url: /aspose.barcode.complexbarcode/gs1digitallink/
---

## GS1DigitalLink class

Represents GS1 Digital Link codetext for encoding and decoding as an ordered sequence of<br/>            Application Identifier elements. Source order and repeated Application Identifiers are preserved.<br/>            The constructed codetext is an uncompressed GS1 Digital Link URI.<br/>            Non-GS1 query parameters and URI fragments are ignored when parsing.

The GS1DigitalLink type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|GS1DigitalLink(uri_stem)|Initializes a new instance of the GS1DigitalLink class|
|GS1DigitalLink(uri_stem, primary_application_identifier)|Initializes a new instance of the GS1DigitalLink class|
## Properties
| Name | Description |
| :- | :- |
|uri_stem|Gets the absolute URI prefix before the GS1 primary key path segment.<br/>            The stem does not contain a query string or fragment.|
|primary_application_identifier|Gets the Application Identifier used as the Digital Link primary key.<br/>            Null means that the primary key is selected automatically when the URI is constructed.|
|barcode_type|Gets or sets the barcode type used to encode this GS1 Digital Link.<br/>            Supported types are QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF and Code128.<br/>            The default value is QR.|
|count|Gets the number of Application Identifier elements.|
|elements|Gets a copy of all elements in source order.|
## Indexer
| Name | Description |
| :- | :- |
|[index]|Gets an element by its position in the ordered sequence.|
## Methods
| Name | Description |
| :- | :- |
|create(uri_stem, codetext)|Creates a GS1 Digital Link by copying all elements from GS1 codetext and selecting<br/>            the only available primary key.|
|create(uri_stem, codetext, primary_application_identifier)|Creates a GS1 Digital Link by copying all elements from GS1 codetext and selecting<br/>            the only available primary key.|
|get_first(application_identifier)|Gets the first value for an Application Identifier.|
|get_all(application_identifier)|Gets all values for an Application Identifier in source order.|
|add(application_identifier, value)|Appends a validated Application Identifier element.|
|validate(value)|Validates an uncompressed GS1 Digital Link URI without constructing an object.|
|parse(value)|Parses an uncompressed GS1 Digital Link URI.|
|try_parse(value, result, validation_result)|Attempts to parse an uncompressed GS1 Digital Link URI and returns structured validation errors.|
|to_gs1_codetext()|Creates an independent GS1 codetext containing the current GS1 elements.<br/>            URI-only information is not included.|
|to_uri_string()|Formats the current object state as an uncompressed GS1 Digital Link URI.|
|get_constructed_codetext()|Constructs the uncompressed GS1 Digital Link URI.|
|init_from_string(constructed_codetext)|Initializes this instance from an uncompressed GS1 Digital Link URI.<br/>            Existing state is replaced only after the supplied URI has been parsed successfully.<br/>            The selected barcode type is preserved.|
|get_barcode_type()|Gets the barcode type used to encode this GS1 Digital Link.|

### See Also

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

