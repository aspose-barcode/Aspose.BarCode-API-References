---
title: Class SecondaryAndAdditionalData
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.ComplexBarcode.SecondaryAndAdditionalData class. Class for storing HIBC LIC secondary and additional data
type: docs
weight: 670
url: /net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class

Class for storing HIBC LIC secondary and additional data.

```csharp
public class SecondaryAndAdditionalData
```

## Constructors

| Name | Description |
| --- | --- |
| [SecondaryAndAdditionalData](secondaryandadditionaldata/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [DateOfManufacture](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/dateofmanufacture/) { get; set; } | Identifies date of manufacture. Date of manufacture can be set to DateTime.MinValue in order not to use this field. Default value: DateTime.MinValue |
| [ExpiryDate](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydate/) { get; set; } | Identifies expiry date. Will be used if ExpiryDateFormat is not set to None. |
| [ExpiryDateFormat](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydateformat/) { get; set; } | Identifies expiry date format. |
| [LotNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/lotnumber/) { get; set; } | Identifies lot or batch number. Lot/batch number must be alphanumeric string with up to 18 sybmols length. . |
| [Quantity](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/quantity/) { get; set; } | Identifies quantity, must be integer value from 0 to 500. Quantity can be set to -1 in order not to use this field. Default value: -1 |
| [SerialNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/serialnumber/) { get; set; } | Identifies serial number. Serial number must be alphanumeric string up to 18 sybmols length. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/equals/)(object) | Returns a value indicating whether this instance is equal to a specified `SecondaryAndAdditionalData` value. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/gethashcode/)() | Returns the hash code for this instance. |
| [ParseFromString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/parsefromstring/)(string) | Instantiates secondary and additional supplemental data from string format according HIBC LIC specification. |
| override [ToString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/tostring/)() | Converts data to string format according HIBC LIC specification. |

### See Also

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


