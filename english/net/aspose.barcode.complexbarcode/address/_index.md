---
title: Class Address
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.ComplexBarcode.Address class. Address of creditor or debtor
type: docs
weight: 410
url: /net/aspose.barcode.complexbarcode/address/
---
## Address class

Address of creditor or debtor.

You can either set street, house number, postal code and town (type structured address) or address line 1 and 2 (type combined address elements). The type is automatically set once any of these fields is set. Before setting the fields, the address type is undetermined. If fields of both types are set, the address type becomes conflicting. Name and country code must always be set unless all fields are empty.

```csharp
public sealed class Address : IEquatable<Address>
```

## Constructors

| Name | Description |
| --- | --- |
| [Address](address/)() | Creates instance of Address |

## Properties

| Name | Description |
| --- | --- |
| [AddressLine1](../../aspose.barcode.complexbarcode/address/addressline1/) { get; set; } | Gets or sets the address line 1. |
| [AddressLine2](../../aspose.barcode.complexbarcode/address/addressline2/) { get; set; } | Gets or sets the address line 2. |
| [CountryCode](../../aspose.barcode.complexbarcode/address/countrycode/) { get; set; } | Gets or sets the two-letter ISO country code. |
| [HouseNo](../../aspose.barcode.complexbarcode/address/houseno/) { get; set; } | Gets or sets the house number. |
| [Name](../../aspose.barcode.complexbarcode/address/name/) { get; set; } | Gets or sets the name, either the first and last name of a natural person or the company name of a legal person. |
| [PostalCode](../../aspose.barcode.complexbarcode/address/postalcode/) { get; set; } | Gets or sets the postal code. |
| [Street](../../aspose.barcode.complexbarcode/address/street/) { get; set; } | Gets or sets the street. |
| [Town](../../aspose.barcode.complexbarcode/address/town/) { get; set; } | Gets or sets the town or city. |
| [Type](../../aspose.barcode.complexbarcode/address/type/) { get; } | Gets the address type. |

## Methods

| Name | Description |
| --- | --- |
| [Clear](../../aspose.barcode.complexbarcode/address/clear/)() | Clears all fields and sets the type to Undetermined. |
| [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals)(Address) | Determines whether the specified address is equal to the current address. |
| override [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals_1)(object) | Determines whether the specified object is equal to the current object. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/address/gethashcode/)() | Gets the hash code for this instance. |

### See Also

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


