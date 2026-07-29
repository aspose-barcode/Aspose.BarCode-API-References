---
title: "Address Class"
linktitle: "Address"
articleTitle: "Address"
second_title: "Aspose.BarCode for PHP via Java"
description: "Address of creditor or debtor. You can either set street, house number, postal code and town (type structured address) or address line 1 and 2 (type combined address elements). The type is automatical"
type: docs
weight: 10
url: /php/aspose/barcode/complexbarcode/address/
---

## Address class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


Address of creditor or debtor. You can either set street, house number, postal code and town (type structured address) or address line 1 and 2 (type combined address elements). The type is automatically set once any of these fields is set. Before setting the fields, the address type is undetermined. If fields of both types are set, the address type becomes conflicting. Name and country code must always be set unless all fields are empty.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](./address/) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [clear](./clear/) | No | Clears all fields and sets the type to AddressType.Undetermined. |
| [construct](./construct/) | Yes | Constructs an Address object from AddressDTO. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [AddressLine1](./addressline1/) | Read/Write | Gets the address line 1. Address line 1 contains street name, house number or P.O. box. Setting this field sets the address type to AddressType.CombinedElements unless it's already AddressType.Structured, in which case it becomes AddressType.Conflicting. This field is only used for combined elements addresses and is optional. |
| [AddressLine2](./addressline2/) | Read/Write | Gets the address line 2. Address line 2 contains postal code and town. Setting this field sets the address type to AddressType.CombinedElements unless it's already AddressType.Structured, in which case it becomes AddressType.Conflicting. This field is only used for combined elements addresses. For this type, it's mandatory. |
| [CountryCode](./countrycode/) | Read/Write | Gets the two-letter ISO country code. The country code is mandatory unless the entire address contains null or emtpy values. |
| [HouseNo](./houseno/) | Read/Write | Gets the house number. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses and is optional. |
| [Name](./name/) | Read/Write | Gets the name, either the first and last name of a natural person or the company name of a legal person. |
| [PostalCode](./postalcode/) | Read/Write | Gets the postal code. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses. For this type, it's mandatory. |
| [Street](./street/) | Read/Write | Gets the street. The street must be speicfied without house number. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses and is optional. |
| [Town](./town/) | Read/Write | Gets the town or city. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses. For this type, it's mandatory. |
| [Type](./type/) | Read-only | Gets the address type. The address type is automatically set by either setting street / house number or address line 1 and 2. Before setting the fields, the address type is Undetermined. If fields of both types are set, the address type becomes Conflicting. |
