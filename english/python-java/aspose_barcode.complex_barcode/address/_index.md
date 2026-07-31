---
title: "Address Class"
linktitle: "Address"
articleTitle: "Address"
second_title: "Aspose.BarCode for Python via Java"
description: "Address of creditor or debtor. You can either set street, house number, postal code and town (type structured address) or address line 1 and 2 (type combined ad"
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode.address/address/
---

## Address class

**Module:** `aspose_barcode.complex_barcode.address`


Address of creditor or debtor. You can either set street, house number, postal code and town (type structured address) or address line 1 and 2 (type combined address elements). The type is automatically set once any of these fields is set. Before setting the fields, the address type is undetermined. If fields of both types are set, the address type becomes conflicting. Name and country code must always be set unless all fields are empty.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](/python-java/aspose_barcode.complex_barcode.address/address/address/) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__eq__](/python-java/aspose_barcode.complex_barcode.address/address/__eq__/) | `bool` | No | Determines whether the specified object is equal to the current object. |
| [__hash__](/python-java/aspose_barcode.complex_barcode.address/address/__hash__/) | `int` | No | Returns the hash code for the current instance. |
| [clear](/python-java/aspose_barcode.complex_barcode.address/address/clear/) | `None` | No | Clears all fields and sets the type to AddressType.Undetermined. |
| [type](/python-java/aspose_barcode.complex_barcode.address/address/type/) | `AddressType` | No |  |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [address_line1](/python-java/aspose_barcode.complex_barcode.address/address/address_line1/) | `Optional[str]` | Gets the address line 1. Address line 1 contains street name, house number or P.O. box. Setting this field sets the address type to AddressType.CombinedElements unless it's already AddressType.Structured, in which case it becomes AddressType.Conflicting. This field is only used for combined elements addresses and is optional. |
| [address_line2](/python-java/aspose_barcode.complex_barcode.address/address/address_line2/) | `Optional[str]` | Gets the address line 2. Address line 2 contains postal code and town. Setting this field sets the address type to AddressType.CombinedElements unless it's already AddressType.Structured, in which case it becomes AddressType.Conflicting. This field is only used for combined elements addresses. For this type, it's mandatory. |
| [country_code](/python-java/aspose_barcode.complex_barcode.address/address/country_code/) | `Optional[str]` | Gets the two-letter ISO country code. The country code is mandatory unless the entire address contains None or emtpy values. |
| [house_no](/python-java/aspose_barcode.complex_barcode.address/address/house_no/) | `Optional[str]` | Gets the house number. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses and is optional. |
| [name](/python-java/aspose_barcode.complex_barcode.address/address/name/) | `Optional[str]` | Gets the name, either the first and last name of a natural person or the company name of a legal person. |
| [postal_code](/python-java/aspose_barcode.complex_barcode.address/address/postal_code/) | `Optional[str]` | Gets the postal code. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses. For this type, it's mandatory. |
| [street](/python-java/aspose_barcode.complex_barcode.address/address/street/) | `Optional[str]` | Gets the street. The street must be speicfied without house number. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses and is optional. |
| [town](/python-java/aspose_barcode.complex_barcode.address/address/town/) | `Optional[str]` | Gets the town or city. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses. For this type, it's mandatory. |
