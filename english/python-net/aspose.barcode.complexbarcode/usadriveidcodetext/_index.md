---
title: USADriveIdCodetext
second_title: Aspose.BarCode for Python via .NET API Reference
description: 
type: docs
url: /python-net/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

Class for encoding and decoding the text embedded in the USA Driving License PDF417 code.

The USADriveIdCodetext type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|USADriveIdCodetext()|Initializes a new instance of the USADriveIdCodetext class|
## Properties
| Name | Description |
| :- | :- |
|issuer_identification_number|This number uniquely identifies <br/>            the issuing jurisdiction and can be obtained by contacting the ISO<br/>            Issuing Authority(AAMVA).  The full 6-digit IIN should be encoded.|
|aamva_version_number|AAMVA Version Number 00-99|
|jurisdiction_version_number|Jurisdiction Version Number 00-99|
|number_of_entries|Number 00-99 of subfiles|
|subfile_designator|Contains information about following subfiles, types, offsets and lengths. <br/>            Important: set only type, offset and length will be set automatically.|
|mandatory_elements|Mandatory elements (fields) of the card|
|optional_elements|Optional elements (fields) of the card|
|jurisdiction_specific_subfile|Jurisdiction Specific Fields|
## Methods
| Name | Description |
| :- | :- |
|get_constructed_codetext()|Construct codetext from USA DL data|
|init_from_string(constructed_codetext)|Initialize USA DL object from codetext|
|get_barcode_type()|Returns barcode type of USA DL (Pdf417)|
|save_to_xml(stream)|Saves to XML|

### See Also

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

