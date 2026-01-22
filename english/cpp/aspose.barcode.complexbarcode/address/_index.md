---
title: Aspose::BarCode::ComplexBarcode::Address class
linktitle: Address
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::Address class. Address of creditor or debtor in C++.'
type: docs
weight: 100
url: /cpp/aspose.barcode.complexbarcode/address/
---
## Address class


[Address](./) of creditor or debtor.

```cpp
class Address : public System::IEquatable<System::SharedPtr<Aspose::BarCode::ComplexBarcode::Address>>
```

## Methods

| Method | Description |
| --- | --- |
| [Address](./address/)() | Creates instance of [Address](./) |
| [Clear](./clear/)() | Clears all fields and sets the type to [AddressType::Undetermined](../addresstype/). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Determines whether the specified object is equal to the current object. |
| [Equals](./equals/)(System::SharedPtr\<Address\>) override | Determines whether the specified address is equal to the current address. |
| [get_AddressLine1](./get_addressline1/)() | Gets the address line 1. |
| [get_AddressLine2](./get_addressline2/)() | Gets the address line 2. |
| [get_CountryCode](./get_countrycode/)() const | Gets the two-letter ISO country code. |
| [get_HouseNo](./get_houseno/)() | Gets the house number. |
| [get_Name](./get_name/)() const | Gets the name, either the first and last name of a natural person or the company name of a legal person. |
| [get_PostalCode](./get_postalcode/)() | Gets the postal code. |
| [get_Street](./get_street/)() | Gets the street. |
| [get_Town](./get_town/)() | Gets the town or city. |
| [get_Type](./get_type/)() const | Gets the address type. |
| [GetHashCode](./gethashcode/)() const override | Gets the hash code for this instance. |
| [set_AddressLine1](./set_addressline1/)(System::String) | Sets the address line 1. |
| [set_AddressLine2](./set_addressline2/)(System::String) | Sets the address line 2. |
| [set_CountryCode](./set_countrycode/)(System::String) | Sets the two-letter ISO country code. |
| [set_HouseNo](./set_houseno/)(System::String) | Sets the house number. |
| [set_Name](./set_name/)(System::String) | Sets the name, either the first and last name of a natural person or the company name of a legal person. |
| [set_PostalCode](./set_postalcode/)(System::String) | Sets the postal code. |
| [set_Street](./set_street/)(System::String) | Sets the street. |
| [set_Town](./set_town/)(System::String) | Sets the town or city. |
## Remarks


You can either set street, house number, postal code and town (type *structured address*) or address line 1 and 2 (type *combined address elements*). The type is automatically set once any of these fields is set. Before setting the fields, the address type is *undetermined*. If fields of both types are set, the address type becomes *conflicting*. Name and country code must always be set unless all fields are empty. 
## See Also

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
