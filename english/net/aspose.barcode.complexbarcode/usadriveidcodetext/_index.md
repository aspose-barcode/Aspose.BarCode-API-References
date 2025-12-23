---
title: Class USADriveIdCodetext
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.ComplexBarcode.USADriveIdCodetext class. Class for encoding and decoding the text embedded in the USA Driving License PDF417 code
type: docs
weight: 710
url: /net/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class

Class for encoding and decoding the text embedded in the USA Driving License PDF417 code.

```csharp
public sealed class USADriveIdCodetext : IComplexCodetext
```

## Constructors

| Name | Description |
| --- | --- |
| [USADriveIdCodetext](usadriveidcodetext/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AAMVAVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/aamvaversionnumber/) { get; set; } | AAMVA Version Number 00-99 |
| [IssuerIdentificationNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/issueridentificationnumber/) { get; set; } | This number uniquely identifies the issuing jurisdiction and can be obtained by contacting the ISO Issuing Authority(AAMVA). The full 6-digit IIN should be encoded. |
| [JurisdictionSpecificSubfile](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionspecificsubfile/) { get; set; } | Jurisdiction Specific Fields |
| [JurisdictionVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionversionnumber/) { get; set; } | Jurisdiction Version Number 00-99 |
| [MandatoryElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/mandatoryelements/) { get; set; } | Mandatory elements (fields) of the card |
| [NumberOfEntries](../../aspose.barcode.complexbarcode/usadriveidcodetext/numberofentries/) { get; set; } | Number 00-99 of subfiles |
| [OptionalElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/optionalelements/) { get; set; } | Optional elements (fields) of the card |
| [SubfileDesignator](../../aspose.barcode.complexbarcode/usadriveidcodetext/subfiledesignator/) { get; set; } | Contains information about following subfiles, types, offsets and lengths. Important: set only type, offset and length will be set automatically. |

## Methods

| Name | Description |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/usadriveidcodetext/getbarcodetype/)() | Returns barcode type of USA DL (Pdf417) |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/usadriveidcodetext/getconstructedcodetext/)() | Construct codetext from USA DL data |
| [InitFromString](../../aspose.barcode.complexbarcode/usadriveidcodetext/initfromstring/)(string) | Initialize USA DL object from codetext |
| [SaveToXml](../../aspose.barcode.complexbarcode/usadriveidcodetext/savetoxml/)(Stream) | Saves to XML |

## Other Members

| Name | Description |
| --- | --- |
| class [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields) | Mandatory elements (fields) of the card |
| class [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields) | Optional elements (fields) of the card |
| class [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties) | USA DL subfile properties, offset and length are set automatically. |

### See Also

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


