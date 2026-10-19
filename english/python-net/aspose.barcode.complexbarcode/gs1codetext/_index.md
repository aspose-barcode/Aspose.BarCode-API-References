---
title: GS1Codetext
second_title: Aspose.BarCode for Python via .NET API Reference
description: 
type: docs
url: /python-net/aspose.barcode.complexbarcode/gs1codetext/
---

## GS1Codetext class

Represents GS1 codetext for encoding and decoding as an ordered sequence of<br/>            Application Identifier elements. Source order and repeated Application Identifiers<br/>            are preserved. The bracketed representation has the form (AI)value(AI)value.<br/>            A literal opening parenthesis '(' inside a value must be written as \(; this is the<br/>            only supported escape sequence. A closing parenthesis ')' inside a value does not<br/>            require escaping.

The GS1Codetext type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|GS1Codetext()|Initializes a new instance of the GS1Codetext class|
## Properties
| Name | Description |
| :- | :- |
|barcode_type|Gets or sets the barcode type used to encode this GS1 codetext.<br/>            Supported types are GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix,<br/>            GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR and GS1 DataBar types.<br/>            The default value is GS1Code128.|
|count|Gets the number of Application Identifier elements.|
|elements|Gets a copy of all elements in source order.|
## Indexer
| Name | Description |
| :- | :- |
|[index]|Gets an element by its position in the ordered sequence.|
## Methods
| Name | Description |
| :- | :- |
|get_first(application_identifier)|Gets the first value for an Application Identifier.|
|get_all(application_identifier)|Gets all values for an Application Identifier in source order.|
|add(application_identifier, value)|Appends a validated Application Identifier element.|
|validate(value)|Validates a bracketed GS1 element string in the form (AI)value(AI)value without<br/>            constructing an object. A literal '(' inside a value must be written as \(; no<br/>            other escape sequence is supported, and ')' does not require escaping.|
|parse(value)|Parses a bracketed GS1 element string in the form (AI)value(AI)value. A literal<br/>            '(' inside a value must be written as \(; no other escape sequence is supported,<br/>            and ')' does not require escaping.|
|try_parse(value, result, validation_result)|Attempts to parse a bracketed GS1 element string in the form (AI)value(AI)value<br/>            and returns structured validation errors. A literal '(' inside a value must be<br/>            written as \(; no other escape sequence is supported, and ')' does not require<br/>            escaping.|
|get_constructed_codetext()|Constructs the bracketed GS1 codetext in the form (AI)value(AI)value.<br/>            Literal opening parentheses in values are escaped as \(.|
|init_from_string(constructed_codetext)|Initializes this instance from bracketed GS1 codetext in the form (AI)value(AI)value.<br/>            Existing elements are replaced only after the supplied codetext has been parsed successfully.|
|get_barcode_type()|Gets the barcode type used to encode this GS1 codetext.|

### See Also

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

