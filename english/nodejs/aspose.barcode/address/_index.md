---
title: "Address Class"
linktitle: "Address"
articleTitle: "Address"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Address of creditor or debtor. You can either set street, house number, postal code and town (type structured address) or address line 1 and 2 (type combined..."
type: docs
weight: 10
url: /nodejs/aspose.barcode/address/
---

## Address class

Address of creditor or debtor. You can either set street, house number, postal code and town (type structured address) or address line 1 and 2 (type combined address elements). The type is automatically set once any of these fields is set. Before setting the fields, the address type is undetermined. If fields of both types are set, the address type becomes conflicting. Name and country code must always be set unless all fields are empty.

```js
new Address()
```

## Methods

| Name | Description |
| --- | --- |
| [clear()](./clear/) | Clears all fields and sets the type to AddressType.UNDETERMINED. |
| [equals(obj)](./equals/) | Determines whether the specified object is equal to the current object. |
| [getAddressLine1()](./getaddressline1/) | Gets the address line 1. Address line 1 contains street name, house number or P.O. box. Setting this field sets the addr |
| [getAddressLine2()](./getaddressline2/) | Gets the address line 2. Address line 2 contains postal code and town. Setting this field sets the address type to Addre |
| [getCountryCode()](./getcountrycode/) | Gets the two-letter ISO country code. The country code is mandatory unless the entire address contains null or emtpy val |
| [getHouseNo()](./gethouseno/) | Gets the house number. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressTyp |
| [getName()](./getname/) | Gets the name, either the first and last name of a natural person or the company name of a legal person. |
| [getPostalCode()](./getpostalcode/) | Gets the postal code. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressType |
| [getStreet()](./getstreet/) | Gets the street. The street must be speicfied without house number. Setting this field sets the address type to AddressT |
| [getTown()](./gettown/) | Gets the town or city. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressTyp |
| [getType()](./gettype/) | Gets the address type. The address type is automatically set by either setting street / house number or address line 1 a |
| [hashCode()](./hashcode/) | Gets the hash code for this instance. |
| [setAddressLine1(value:)](./setaddressline1/) | Sets the address line 1. Address line 1 contains street name, house number or P.O. box. Setting this field sets the addr |
| [setAddressLine2(value:)](./setaddressline2/) | Sets the address line 2. Address line 2 contains postal code and town. Setting this field sets the address type to Addre |
| [setCountryCode(value)](./setcountrycode/) | Sets the two-letter ISO country code. The country code is mandatory unless the entire address contains null or emtpy val |
| [setHouseNo(value:)](./sethouseno/) | Sets the house number. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressTyp |
| [setName(value:)](./setname/) | Sets the name, either the first and last name of a natural person or the company name of a legal person. |
| [setPostalCode(value)](./setpostalcode/) | Sets the postal code. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressType |
| [setStreet(value:)](./setstreet/) | Sets the street. The street must be speicfied without house number. Setting this field sets the address type to AddressT |
| [setTown(value)](./settown/) | Sets the town or city. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressTyp |
