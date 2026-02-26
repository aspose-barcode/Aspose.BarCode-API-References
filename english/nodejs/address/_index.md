---
title: Address Class
linktitle: Address
articleTitle: Address
second_title: Aspose.BarCode for Node.js via Java
description: Address of creditor or debtor.
type: docs
weight: 40
url: /nodejs/address/
---
## Address class

Address of creditor or debtor.

```javascript
public class Address : joint.BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [Address](./address/#constructor) | Initializes a new instance of the Address class. |

## Methods

| Name | Description |
| --- | --- |
| [clear](./clear/) | Clears all fields and sets the type to AddressType.UNDETERMINED. |
| [construct](./construct/)(*object*) |  |
| [equals](./equals/)(*object*) | Determines whether the specified object is equal to the current object. |
| [getAddressLine1](./getaddressline1/) | Gets the address line 1. |
| [getAddressLine2](./getaddressline2/) | Gets the address line 2. Address line 2 contains postal code and town. Setting this field sets the address type to AddressType.COMBINED_ELEMENTS unless it's already AddressType.STRUCTURED, in which case it becomes AddressType.CONFLICTING. This field is only used for combined elements addresses. For... |
| [getCountryCode](./getcountrycode/) | Gets the two-letter ISO country code. |
| [getHouseNo](./gethouseno/) | Gets the house number. |
| [getName](./getname/) | Gets the name, either the first and last name of a natural person or the company name of a legal person. |
| [getPostalCode](./getpostalcode/) | Gets the postal code. |
| [getStreet](./getstreet/) | Gets the street. The street must be speicfied without house number. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressType.COMBINED_ELEMENTS, in which case it becomes AddressType.CONFLICTING. This field is only used for structured addresses and is... |
| [getTown](./gettown/) | Gets the town or city. |
| [getType](./gettype/) | Gets the address type. |
| [hashCode](./hashcode/) | Gets the hash code for this instance. |
| [init](./init/) |  |
| [setAddressLine1](./setaddressline1/)(*object*) | Sets the address line 1. |
| [setAddressLine2](./setaddressline2/)(*object*) | Sets the address line 2. Address line 2 contains postal code and town. Setting this field sets the address type to AddressType.COMBINED_ELEMENTS unless it's already AddressType.STRUCTURED, in which case it becomes AddressType.CONFLICTING. This field is only used for combined elements addresses. For... |
| [setCountryCode](./setcountrycode/)(*object*) | Sets the two-letter ISO country code. |
| [setHouseNo](./sethouseno/)(*object*) | Sets the house number. |
| [setName](./setname/)(*object*) | Sets the name, either the first and last name of a natural person or the company name of a legal person. |
| [setPostalCode](./setpostalcode/)(*object*) | Sets the postal code. |
| [setStreet](./setstreet/)(*object*) | Sets the street. |
| [setTown](./settown/)(*object*) | Sets the town or city. |

## Fields

| Name | Description |
| --- | --- |
| [javaClassName](./javaclassname/) |  |

### See Also

* assembly [Aspose.BarCode](../)

