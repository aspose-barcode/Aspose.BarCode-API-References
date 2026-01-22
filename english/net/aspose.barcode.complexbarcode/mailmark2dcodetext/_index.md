---
title: Class Mailmark2DCodetext
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.ComplexBarcode.Mailmark2DCodetext class. Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark code
type: docs
weight: 560
url: /net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class

Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark code.

```csharp
public sealed class Mailmark2DCodetext : IComplexCodetext
```

## Constructors

| Name | Description |
| --- | --- |
| [Mailmark2DCodetext](mailmark2dcodetext/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmark2dcodetext/class/) { get; set; } | Identifies the class of the item. |
| [CustomerContent](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontent/) { get; set; } | Optional space for use by customer. |
| [CustomerContentEncodeMode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontentencodemode/) { get; set; } | Encode mode of Datamatrix barcode. Default value: EncodeMode.C40. |
| [DataMatrixType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/datamatrixtype/) { get; set; } | 2D Mailmark Type defines size of Data Matrix barcode. |
| [DestinationPostCodeAndDPS](../../aspose.barcode.complexbarcode/mailmark2dcodetext/destinationpostcodeanddps/) { get; set; } | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. Area (1 or 2 characters) District(1 or 2 characters) Sector(1 character) Unit(2 characters) DPS (2 characters). The Postcode and DPS must comply with a valid PAF® format. |
| [InformationTypeID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/informationtypeid/) { get; set; } | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [ItemID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/itemid/) { get; set; } | Identifies the unique item within the Supply Chain ID. Every Mailmark barcode is required to carry an ID so it can be uniquely identified for at least 90 days. Max value: 99999999. |
| [ReturnToSenderPostCode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/returntosenderpostcode/) { get; set; } | Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format. |
| [RTSFlag](../../aspose.barcode.complexbarcode/mailmark2dcodetext/rtsflag/) { get; set; } | Flag which indicates what level of Return to Sender service is being requested. |
| [SupplyChainID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/supplychainid/) { get; set; } | Identifies the unique group of customers involved in the mailing. Max value: 9999999. |
| [UPUCountryID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/upucountryid/) { get; set; } | Identifies the UPU Country ID.Max length: 4 characters. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/versionid/) { get; set; } | Identifies the barcode version as relevant to each Information Type ID. |

## Methods

| Name | Description |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getbarcodetype/)() | Gets barcode type. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getconstructedcodetext/)() | Construct codetext from Mailmark data. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmark2dcodetext/initfromstring/)(string) | Initializes Mailmark data from constructed codetext. |

### See Also

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


