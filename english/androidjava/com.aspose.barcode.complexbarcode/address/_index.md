---
title: Address
second_title: Aspose.BarCode for Android via Java API Reference
description: Address of creditor or debtor.
type: docs
weight: 10
url: /androidjava/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

Address of creditor or debtor.

You can either set street, house number, postal code and town (type  *structured address* ) or address line 1 and 2 (type  *combined address elements* ). The type is automatically set once any of these fields is set. Before setting the fields, the address type is  *undetermined* . If fields of both types are set, the address type becomes  *conflicting* . Name and country code must always be set unless all fields are empty.
## Constructors

| Constructor | Description |
| --- | --- |
| [Address()](#Address--) | Creates instance of Address |
## Methods

| Method | Description |
| --- | --- |
| [clear()](#clear--) | Clears all fields and sets the type to  AddressType.Undetermined . |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified object is equal to the current object. |
| [getAddressLine1()](#getAddressLine1--) | Gets the address line 1. |
| [getAddressLine2()](#getAddressLine2--) | Gets the address line 2. |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | Gets the two-letter ISO country code. |
| [getHouseNo()](#getHouseNo--) | Gets the house number. |
| [getName()](#getName--) | Gets the name, either the first and last name of a natural person or the company name of a legal person. |
| [getPostalCode()](#getPostalCode--) | Gets the postal code. |
| [getStreet()](#getStreet--) | Gets the street. |
| [getTown()](#getTown--) | Gets the town or city. |
| [getType()](#getType--) | Gets the address type. |
| [hashCode()](#hashCode--) | Gets the hash code for this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Sets the address line 1. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Sets the address line 2. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Sets the two-letter ISO country code. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Sets the house number. |
| [setName(String value)](#setName-java.lang.String-) | Sets the name, either the first and last name of a natural person or the company name of a legal person. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Sets the postal code. |
| [setStreet(String value)](#setStreet-java.lang.String-) | Sets the street. |
| [setTown(String value)](#setTown-java.lang.String-) | Sets the town or city. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


Creates instance of Address

### clear() {#clear--}
```
public void clear()
```


Clears all fields and sets the type to  AddressType.Undetermined .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified object is equal to the current object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with the current object. |

**Returns:**
boolean -  true  if the specified object is equal to the current object; otherwise,  false .
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


Gets the address line 1.

Address line 1 contains street name, house number or P.O. box.

Setting this field sets the address type to  AddressType.CombinedElements  unless it's already  AddressType.Structured , in which case it becomes  AddressType.Conflicting .

This field is only used for combined elements addresses and is optional.

Value: The address line 1.

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


Gets the address line 2.

Address line 2 contains postal code and town.

Setting this field sets the address type to  AddressType.CombinedElements  unless it's already  AddressType.Structured , in which case it becomes  AddressType.Conflicting .

This field is only used for combined elements addresses. For this type, it's mandatory.

Value: The address line 2.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryCode() {#getCountryCode--}
```
public String getCountryCode()
```


Gets the two-letter ISO country code.

The country code is mandatory unless the entire address contains  null  or emtpy values.

Value: The ISO country code.

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


Gets the house number.

Setting this field sets the address type to  AddressType.Structured  unless it's already  AddressType.CombinedElements , in which case it becomes  AddressType.Conflicting .

This field is only used for structured addresses and is optional.

Value: The house number.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


Gets the name, either the first and last name of a natural person or the company name of a legal person.

Value: The name.

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Gets the postal code.

Setting this field sets the address type to  AddressType.Structured  unless it's already  AddressType.CombinedElements , in which case it becomes  AddressType.Conflicting .

This field is only used for structured addresses. For this type, it's mandatory.

Value: The postal code.

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


Gets the street.

The street must be speicfied without house number.

Setting this field sets the address type to  AddressType.Structured  unless it's already  AddressType.CombinedElements , in which case it becomes  AddressType.Conflicting .

This field is only used for structured addresses and is optional.

Value: The street.

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


Gets the town or city.

Setting this field sets the address type to  AddressType.Structured  unless it's already  AddressType.CombinedElements , in which case it becomes  AddressType.Conflicting .

This field is only used for structured addresses. For this type, it's mandatory.

Value: The town or city.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


Gets the address type.

The address type is automatically set by either setting street / house number or address line 1 and 2. Before setting the fields, the address type is  *Undetermined* . If fields of both types are set, the address type becomes  *Conflicting* .

Value: The address type.

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gets the hash code for this instance.

**Returns:**
int - A hash code for the current object.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public void setAddressLine1(String value)
```


Sets the address line 1.

Address line 1 contains street name, house number or P.O. box.

Setting this field sets the address type to  AddressType.CombinedElements  unless it's already  AddressType.Structured , in which case it becomes  AddressType.Conflicting .

This field is only used for combined elements addresses and is optional.

Value: The address line 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


Sets the address line 2.

Address line 2 contains postal code and town.

Setting this field sets the address type to  AddressType.CombinedElements  unless it's already  AddressType.Structured , in which case it becomes  AddressType.Conflicting .

This field is only used for combined elements addresses. For this type, it's mandatory.

Value: The address line 2.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


Sets the two-letter ISO country code.

The country code is mandatory unless the entire address contains  null  or emtpy values.

Value: The ISO country code.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


Sets the house number.

Setting this field sets the address type to  AddressType.Structured  unless it's already  AddressType.CombinedElements , in which case it becomes  AddressType.Conflicting .

This field is only used for structured addresses and is optional.

Value: The house number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Sets the name, either the first and last name of a natural person or the company name of a legal person.

Value: The name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


Sets the postal code.

Setting this field sets the address type to  AddressType.Structured  unless it's already  AddressType.CombinedElements , in which case it becomes  AddressType.Conflicting .

This field is only used for structured addresses. For this type, it's mandatory.

Value: The postal code.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


Sets the street.

The street must be speicfied without house number.

Setting this field sets the address type to  AddressType.Structured  unless it's already  AddressType.CombinedElements , in which case it becomes  AddressType.Conflicting .

This field is only used for structured addresses and is optional.

Value: The street.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


Sets the town or city.

Setting this field sets the address type to  AddressType.Structured  unless it's already  AddressType.CombinedElements , in which case it becomes  AddressType.Conflicting .

This field is only used for structured addresses. For this type, it's mandatory.

Value: The town or city.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

