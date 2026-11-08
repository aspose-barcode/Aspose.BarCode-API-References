---
title: "Aspose::BarCode::ComplexBarcode::Address klass"
linktitle: "Adress"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::Address klass. Adress för borgenär eller gäldenär i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.barcode.complexbarcode/address/
---
## Address class


[Address](./) of creditor or debtor.

```cpp
class Address : public System::IEquatable<System::SharedPtr<Address>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Address](./address/)() | Skapar en instans av [Address](./) |
| [Clear](./clear/)() | Rensar alla fält och sätter typen till [AddressType::Undetermined](../addresstype/). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Bestämmer om det angivna objektet är lika med det aktuella objektet. |
| [Equals](./equals/)(System::SharedPtr\<Address\>) override | Bestämmer om den specificerade adressen är lika med den aktuella adressen. |
| [get_AddressLine1](./get_addressline1/)() const | Hämtar adressrad 1. |
| [get_AddressLine2](./get_addressline2/)() const | Hämtar adressrad 2. |
| [get_CountryCode](./get_countrycode/)() const | Hämtar den tvåbokstaviga ISO-landkoden. |
| [get_HouseNo](./get_houseno/)() const | Hämtar husnumret. |
| [get_Name](./get_name/)() const | Hämtar namnet, antingen för- och efternamnet på en fysisk person eller företagsnamnet på en juridisk person. |
| [get_PostalCode](./get_postalcode/)() const | Hämtar postnumret. |
| [get_Street](./get_street/)() const | Hämtar gatan. |
| [get_Town](./get_town/)() const | Hämtar stad eller ort. |
| [get_Type](./get_type/)() const | Hämtar adresstypen. |
| [GetHashCode](./gethashcode/)() const override | Hämtar hashkoden för denna instans. |
| [set_AddressLine1](./set_addressline1/)(System::String) | Sätter adressrad 1. |
| [set_AddressLine2](./set_addressline2/)(System::String) | Sätter adressrad 2. |
| [set_CountryCode](./set_countrycode/)(System::String) | Sätter den tvåbokstaviga ISO-landkoden. |
| [set_HouseNo](./set_houseno/)(System::String) | Sätter husnumret. |
| [set_Name](./set_name/)(System::String) | Sätter namnet, antingen för- och efternamnet på en fysisk person eller företagsnamnet på en juridisk person. |
| [set_PostalCode](./set_postalcode/)(System::String) | Sätter postnumret. |
| [set_Street](./set_street/)(System::String) | Anger gatan. |
| [set_Town](./set_town/)(System::String) | Anger orten eller staden. |
## Anmärkningar


Du kan antingen ange gata, husnummer, postnummer och ort (typ *structured address*) eller adressrad 1 och 2 (typ *combined address elements*). Typen sätts automatiskt så snart något av dessa fält har angetts. Innan fälten anges är adresstypen *undetermined*. Om fält från båda typerna anges blir adresstypen *conflicting*. Namn och landskod måste alltid anges om inte alla fält är tomma.
## Se även

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
