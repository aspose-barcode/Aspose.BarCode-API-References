---
title: "Address"
linktitle: "Address"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Address of creditor or debtor."
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
| [clear()](#clear) | Clears all fields and sets the type to AddressType.UNDETERMINED. |
| [equals(obj)](#equals) | Determines whether the specified object is equal to the current object. |
| [getAddressLine1()](#getaddressline1) | Gets the address line 1. Address line 1 contains street name, house number or P.O. box. Setting this field sets the addr |
| [getAddressLine2()](#getaddressline2) | Gets the address line 2. Address line 2 contains postal code and town. Setting this field sets the address type to Addre |
| [getCountryCode()](#getcountrycode) | Gets the two-letter ISO country code. The country code is mandatory unless the entire address contains null or emtpy val |
| [getHouseNo()](#gethouseno) | Gets the house number. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressTyp |
| [getName()](#getname) | Gets the name, either the first and last name of a natural person or the company name of a legal person. |
| [getPostalCode()](#getpostalcode) | Gets the postal code. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressType |
| [getStreet()](#getstreet) | Gets the street. The street must be speicfied without house number. Setting this field sets the address type to AddressT |
| [getTown()](#gettown) | Gets the town or city. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressTyp |
| [getType()](#gettype) | Gets the address type. The address type is automatically set by either setting street / house number or address line 1 a |
| [hashCode()](#hashcode) | Gets the hash code for this instance. |
| [setAddressLine1(value:)](#setaddressline1) | Sets the address line 1. Address line 1 contains street name, house number or P.O. box. Setting this field sets the addr |
| [setAddressLine2(value:)](#setaddressline2) | Sets the address line 2. Address line 2 contains postal code and town. Setting this field sets the address type to Addre |
| [setCountryCode(value)](#setcountrycode) | Sets the two-letter ISO country code. The country code is mandatory unless the entire address contains null or emtpy val |
| [setHouseNo(value:)](#sethouseno) | Sets the house number. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressTyp |
| [setName(value:)](#setname) | Sets the name, either the first and last name of a natural person or the company name of a legal person. |
| [setPostalCode(value)](#setpostalcode) | Sets the postal code. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressType |
| [setStreet(value:)](#setstreet) | Sets the street. The street must be speicfied without house number. Setting this field sets the address type to AddressT |
| [setTown(value)](#settown) | Sets the town or city. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressTyp |

### clear() {#clear}

Clears all fields and sets the type to AddressType.UNDETERMINED.

### equals(obj) {#equals}

Determines whether the specified object is equal to the current object.

| Parameter | Description |
| --- | --- |
| obj | The object to compare with the current object. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAddressLine1() {#getaddressline1}

Gets the address line 1. Address line 1 contains street name, house number or P.O. box. Setting this field sets the address type to AddressType.COMBINED_ELEMENTS unless it's already AddressType.STRUCTURED, in which case it becomes AddressType.CONFLICTING. This field is only used for combined elements addresses and is optional.

**Returns:** The address line 1.

### getAddressLine2() {#getaddressline2}

Gets the address line 2. Address line 2 contains postal code and town. Setting this field sets the address type to AddressType.COMBINED_ELEMENTS unless it's already AddressType.STRUCTURED, in which case it becomes AddressType.CONFLICTING. This field is only used for combined elements addresses. For this type, it's mandatory.

**Returns:** The address line 2.

### getCountryCode() {#getcountrycode}

Gets the two-letter ISO country code. The country code is mandatory unless the entire address contains null or emtpy values.

**Returns:** The ISO country code.

### getHouseNo() {#gethouseno}

Gets the house number. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressType.COMBINED_ELEMENTS, in which case it becomes AddressType.CONFLICTING. This field is only used for structured addresses and is optional.

**Returns:** The house number.

### getName() {#getname}

Gets the name, either the first and last name of a natural person or the company name of a legal person.

**Returns:** The name.

### getPostalCode() {#getpostalcode}

Gets the postal code. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressType.COMBINED_ELEMENTS, in which case it becomes AddressType.CONFLICTING. This field is only used for structured addresses. For this type, it's mandatory.

**Returns:** The postal code.

### getStreet() {#getstreet}

Gets the street. The street must be speicfied without house number. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressType.COMBINED_ELEMENTS, in which case it becomes AddressType.CONFLICTING. This field is only used for structured addresses and is optional.

**Returns:** The street.

### getTown() {#gettown}

Gets the town or city. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressType.COMBINED_ELEMENTS, in which case it becomes AddressType.CONFLICTING. This field is only used for structured addresses. For this type, it's mandatory.

**Returns:** The town or city.

### getType() {#gettype}

Gets the address type. The address type is automatically set by either setting street / house number or address line 1 and 2. Before setting the fields, the address type is Undetermined. If fields of both types are set, the address type becomes Conflicting.

**Returns:** The address type.

### hashCode() {#hashcode}

Gets the hash code for this instance.

**Returns:** A hash code for the current object .

### setAddressLine1(value:) {#setaddressline1}

Sets the address line 1. Address line 1 contains street name, house number or P.O. box. Setting this field sets the address type to AddressType.COMBINED_ELEMENTS unless it's already AddressType.STRUCTURED, in which case it becomes AddressType.CONFLICTING. This field is only used for combined elements addresses and is optional.

| Parameter | Description |
| --- | --- |
| value: | The address line 1. |

### setAddressLine2(value:) {#setaddressline2}

Sets the address line 2. Address line 2 contains postal code and town. Setting this field sets the address type to AddressType.COMBINED_ELEMENTS unless it's already AddressType.STRUCTURED, in which case it becomes AddressType.CONFLICTING. This field is only used for combined elements addresses. For this type, it's mandatory.

| Parameter | Description |
| --- | --- |
| value: | The address line 2. |

### setCountryCode(value) {#setcountrycode}

Sets the two-letter ISO country code. The country code is mandatory unless the entire address contains null or emtpy values.

| Parameter | Description |
| --- | --- |
| value | The ISO country code. |

### setHouseNo(value:) {#sethouseno}

Sets the house number. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressType.COMBINED_ELEMENTS, in which case it becomes AddressType.CONFLICTING. This field is only used for structured addresses and is optional.

| Parameter | Description |
| --- | --- |
| value: | The house number. |

### setName(value:) {#setname}

Sets the name, either the first and last name of a natural person or the company name of a legal person.

| Parameter | Description |
| --- | --- |
| value: | The name. |

### setPostalCode(value) {#setpostalcode}

Sets the postal code. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressType.COMBINED_ELEMENTS, in which case it becomes AddressType.CONFLICTING. This field is only used for structured addresses. For this type, it's mandatory.

| Parameter | Description |
| --- | --- |
| value | The postal code. |

### setStreet(value:) {#setstreet}

Sets the street. The street must be speicfied without house number. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressType.COMBINED_ELEMENTS, in which case it becomes AddressType.CONFLICTING. This field is only used for structured addresses and is optional.

| Parameter | Description |
| --- | --- |
| value: | The street. |

### setTown(value) {#settown}

Sets the town or city. Setting this field sets the address type to AddressType.STRUCTURED unless it's already AddressType.COMBINED_ELEMENTS, in which case it becomes AddressType.CONFLICTING. This field is only used for structured addresses. For this type, it's mandatory.

| Parameter | Description |
| --- | --- |
| value | The town or city. |
