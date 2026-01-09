---
title: Aspose::BarCode::ComplexBarcode::USADriveIdCodetext class
linktitle: USADriveIdCodetext
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::USADriveIdCodetext class. Class for encoding and decoding the text embedded in the USA Driving License PDF417 code in C++.'
type: docs
weight: 2700
url: /cpp/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class


Class for encoding and decoding the text embedded in the USA Driving [License](../../aspose.barcode/license/) PDF417 code.

```cpp
class USADriveIdCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Description |
| --- | --- |
| [get_AAMVAVersionNumber](./get_aamvaversionnumber/)() const | AAMVA Version Number 00-99 |
| [get_IssuerIdentificationNumber](./get_issueridentificationnumber/)() const | This number uniquely identifies the issuing jurisdiction and can be obtained by contacting the ISO Issuing Authority(AAMVA). The full 6-digit IIN should be encoded. |
| [get_JurisdictionSpecificSubfile](./get_jurisdictionspecificsubfile/)() const | Jurisdiction Specific Fields |
| [get_JurisdictionVersionNumber](./get_jurisdictionversionnumber/)() const | Jurisdiction Version Number 00-99 |
| [get_MandatoryElements](./get_mandatoryelements/)() const | Mandatory elements (fields) of the card |
| [get_NumberOfEntries](./get_numberofentries/)() const | Number 00-99 of subfiles |
| [get_OptionalElements](./get_optionalelements/)() const | Optional elements (fields) of the card |
| [get_SubfileDesignator](./get_subfiledesignator/)() const | Contains information about following subfiles, types, offsets and lengths. Important: set only type, offset and length will be set automatically. |
| [GetBarcodeType](./getbarcodetype/)() override | Returns barcode type of USA DL (Pdf417) |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construct codetext from USA DL data |
| [InitFromString](./initfromstring/)(System::String) override | Initialize USA DL object from codetext |
| [SaveToXml](./savetoxml/)(System::SharedPtr\<System::IO::Stream\>) | Saves to XML |
| [set_AAMVAVersionNumber](./set_aamvaversionnumber/)(System::String) | AAMVA Version Number 00-99 |
| [set_IssuerIdentificationNumber](./set_issueridentificationnumber/)(System::String) | This number uniquely identifies the issuing jurisdiction and can be obtained by contacting the ISO Issuing Authority(AAMVA). The full 6-digit IIN should be encoded. |
| [set_JurisdictionSpecificSubfile](./set_jurisdictionspecificsubfile/)(System::SharedPtr\<USADriveIdJurisdSubfile\>) | Jurisdiction Specific Fields |
| [set_JurisdictionVersionNumber](./set_jurisdictionversionnumber/)(System::String) | Jurisdiction Version Number 00-99 |
| [set_MandatoryElements](./set_mandatoryelements/)(System::SharedPtr\<USADriveIdCodetext::MandatoryFields\>) | Mandatory elements (fields) of the card |
| [set_NumberOfEntries](./set_numberofentries/)(int32_t) | Number 00-99 of subfiles |
| [set_OptionalElements](./set_optionalelements/)(System::SharedPtr\<USADriveIdCodetext::OptionalFields\>) | Optional elements (fields) of the card |
| [set_SubfileDesignator](./set_subfiledesignator/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<USADriveIdCodetext::SubfileProperties\>>>) | Contains information about following subfiles, types, offsets and lengths. Important: set only type, offset and length will be set automatically. |
| [USADriveIdCodetext](./usadriveidcodetext/)() | Default constructor |
## See Also

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
