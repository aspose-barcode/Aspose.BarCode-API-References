---
title: "Address"
linktitle: "Address"
second_title: "Aspose.BarCode for Python via Java"
description: "Address of creditor or debtor. You can either set street, house number, postal code and town (type structured address) or address line 1 and 2 (type combined ad"
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/address/
---

## Address class

**Module:** `aspose_barcode.complex_barcode.address`


Address of creditor or debtor. You can either set street, house number, postal code and town (type structured address) or address line 1 and 2 (type combined address elements). The type is automatically set once any of these fields is set. Before setting the fields, the address type is undetermined. If fields of both types are set, the address type becomes conflicting. Name and country code must always be set unless all fields are empty.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__eq__](#__eq__) | `bool` | No | Determines whether the specified object is equal to the current object. |
| [__hash__](#__hash__) | `int` | No | Returns the hash code for the current instance. |
| [clear](#clear) | `None` | No | Clears all fields and sets the type to AddressType.Undetermined. |
| [type](#type) | `AddressType` | No |  |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [address_line1](#address_line1) | `Optional[str]` | Gets the address line 1. Address line 1 contains street name, house number or P.O. box. Setting this field sets the address type to AddressType.CombinedElements unless it's already AddressType.Structured, in which case it becomes AddressType.Conflicting. This field is only used for combined elements addresses and is optional. |
| [address_line2](#address_line2) | `Optional[str]` | Gets the address line 2. Address line 2 contains postal code and town. Setting this field sets the address type to AddressType.CombinedElements unless it's already AddressType.Structured, in which case it becomes AddressType.Conflicting. This field is only used for combined elements addresses. For this type, it's mandatory. |
| [country_code](#country_code) | `Optional[str]` | Gets the two-letter ISO country code. The country code is mandatory unless the entire address contains None or emtpy values. |
| [house_no](#house_no) | `Optional[str]` | Gets the house number. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses and is optional. |
| [name](#name) | `Optional[str]` | Gets the name, either the first and last name of a natural person or the company name of a legal person. |
| [postal_code](#postal_code) | `Optional[str]` | Gets the postal code. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses. For this type, it's mandatory. |
| [street](#street) | `Optional[str]` | Gets the street. The street must be speicfied without house number. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses and is optional. |
| [town](#town) | `Optional[str]` | Gets the town or city. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses. For this type, it's mandatory. |

### Address Constructor {#constructor}

```python
__init__(self)
```

### Address.__eq__ {#__eq__}

```python
__eq__(self, Address other) -> bool
```

Determines whether the specified object is equal to the current object.

| Parameter | Type | Description |
| --- | --- | --- |
| `other` | `Address` |  |

**Return Type:** `bool` — True if the specified object is equal to the current object; otherwise, false.

### Address.__hash__ {#__hash__}

```python
__hash__(self) -> int
```

Returns the hash code for the current instance.

**Return Type:** `int` — A hash code for the current object.

### Address.clear {#clear}

```python
clear(self)
```

Clears all fields and sets the type to AddressType.Undetermined.

### Address.type {#type}

```python
type(self) -> AddressType
```

**Return Type:** `AddressType`

### Address.address_line1 {#address_line1}

**Type:** `Optional[str]`

Gets the address line 1. Address line 1 contains street name, house number or P.O. box. Setting this field sets the address type to AddressType.CombinedElements unless it's already AddressType.Structured, in which case it becomes AddressType.Conflicting. This field is only used for combined elements addresses and is optional.

**Returns:** The address line 1.

Sets the address line 1. Address line 1 contains street name, house number or P.O. box. Setting this field sets the address type to AddressType.CombinedElements unless it's already AddressType.Structured, in which case it becomes AddressType.Conflicting. This field is only used for combined elements addresses and is optional.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Optional[str]` |  |

### Address.address_line2 {#address_line2}

**Type:** `Optional[str]`

Gets the address line 2. Address line 2 contains postal code and town. Setting this field sets the address type to AddressType.CombinedElements unless it's already AddressType.Structured, in which case it becomes AddressType.Conflicting. This field is only used for combined elements addresses. For this type, it's mandatory.

**Returns:** The address line 2.

Sets the address line 2. Address line 2 contains postal code and town. Setting this field sets the address type to AddressType.CombinedElements unless it's already AddressType.Structured, in which case it becomes AddressType.Conflicting. This field is only used for combined elements addresses. For this type, it's mandatory.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Optional[str]` |  |

### Address.country_code {#country_code}

**Type:** `Optional[str]`

Gets the two-letter ISO country code. The country code is mandatory unless the entire address contains None or emtpy values.

**Returns:** The ISO country code.

Sets the two-letter ISO country code. The country code is mandatory unless the entire address contains None or emtpy values.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Optional[str]` |  |

### Address.house_no {#house_no}

**Type:** `Optional[str]`

Gets the house number. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses and is optional.

**Returns:** The house number.

Sets the house number. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses and is optional.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Optional[str]` |  |

### Address.name {#name}

**Type:** `Optional[str]`

Gets the name, either the first and last name of a natural person or the company name of a legal person.

**Returns:** The name.

Sets the name, either the first and last name of a natural person or the company name of a legal person.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Optional[str]` |  |

### Address.postal_code {#postal_code}

**Type:** `Optional[str]`

Gets the postal code. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses. For this type, it's mandatory.

**Returns:** The postal code.

Sets the postal code. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses. For this type, it's mandatory.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Optional[str]` |  |

### Address.street {#street}

**Type:** `Optional[str]`

Gets the street. The street must be speicfied without house number. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses and is optional.

**Returns:** The street.

Sets the street. The street must be speicfied without house number. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses and is optional.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Optional[str]` |  |

### Address.town {#town}

**Type:** `Optional[str]`

Gets the town or city. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses. For this type, it's mandatory.

**Returns:** The town or city.

Sets the town or city. Setting this field sets the address type to AddressType.Structured unless it's already AddressType.CombinedElements, in which case it becomes AddressType.Conflicting. This field is only used for structured addresses. For this type, it's mandatory.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Optional[str]` |  |

