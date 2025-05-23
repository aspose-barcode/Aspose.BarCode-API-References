---
title: Class MailmarkCodetext
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.ComplexBarcode.MailmarkCodetext class. Class for encoding and decoding the text embedded in the 4state Royal Mailmark code
type: docs
weight: 570
url: /net/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class

Class for encoding and decoding the text embedded in the 4-state Royal Mailmark code.

```csharp
public sealed class MailmarkCodetext : IComplexCodetext
```

## Constructors

| Name | Description |
| --- | --- |
| [MailmarkCodetext](mailmarkcodetext/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmarkcodetext/class/) { get; set; } | "0" - Null or Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Retail) "6" - Air (Retail) (for potential future use) "7" - Surface (Retail) (for potential future use) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [DestinationPostCodePlusDPS](../../aspose.barcode.complexbarcode/mailmarkcodetext/destinationpostcodeplusdps/) { get; set; } | The PC and DP must comply with a PAF format. Nine character string denoting international "XY11 " (note the 5 trailing spaces) or a pattern of characters denoting a domestic sorting code. A domestic sorting code consists of an outward postcode, an inward postcode, and a Delivery Point Suffix. |
| [Format](../../aspose.barcode.complexbarcode/mailmarkcodetext/format/) { get; set; } | "0" – Null or Test "1" – Letter "2" – Large Letter |
| [ItemID](../../aspose.barcode.complexbarcode/mailmarkcodetext/itemid/) { get; set; } | Maximum value is 99999999. |
| [SupplychainID](../../aspose.barcode.complexbarcode/mailmarkcodetext/supplychainid/) { get; set; } | Maximum values are 99 for Barcode C and 999999 for Barcode L. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmarkcodetext/versionid/) { get; set; } | Currently "1" – For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use) |

## Methods

| Name | Description |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmarkcodetext/getbarcodetype/)() | Gets barcode type. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmarkcodetext/getconstructedcodetext/)() | Construct codetext from Mailmark data. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmarkcodetext/initfromstring/)(string) | Initializes Mailmark data from constructed codetext. |

### See Also

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


