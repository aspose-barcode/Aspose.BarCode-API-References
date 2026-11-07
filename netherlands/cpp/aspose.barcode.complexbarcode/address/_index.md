---
title: "Aspose::BarCode::ComplexBarcode::Address klasse"
linktitle: "Adres"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::Address klasse. Adres van schuldeiser of schuldenaar in C++."
type: docs
weight: 100
url: /nl/cpp/aspose.barcode.complexbarcode/address/
---
## Address class


[Address](./) of creditor or debtor.

```cpp
class Address : public System::IEquatable<System::SharedPtr<Address>>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Address](./address/)() | Maakt een instantie van [Address](./) |
| [Clear](./clear/)() | Wis alle velden en stelt het type in op [AddressType::Undetermined](../addresstype/). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Bepaalt of het opgegeven object gelijk is aan het huidige object. |
| [Equals](./equals/)(System::SharedPtr\<Address\>) override | Bepaalt of het opgegeven adres gelijk is aan het huidige adres. |
| [get_AddressLine1](./get_addressline1/)() const | Haalt de adresregel 1 op. |
| [get_AddressLine2](./get_addressline2/)() const | Haalt de adresregel 2 op. |
| [get_CountryCode](./get_countrycode/)() const | Haalt de tweeletterige ISO-landcode op. |
| [get_HouseNo](./get_houseno/)() const | Haalt het huisnummer op. |
| [get_Name](./get_name/)() const | Haalt de naam op, ofwel de voor- en achternaam van een natuurlijke persoon of de bedrijfsnaam van een rechtspersoon. |
| [get_PostalCode](./get_postalcode/)() const | Haalt de postcode op. |
| [get_Street](./get_street/)() const | Haalt de straat op. |
| [get_Town](./get_town/)() const | Haalt de plaats of stad op. |
| [get_Type](./get_type/)() const | Haalt het adrestype op. |
| [GetHashCode](./gethashcode/)() const override | Haalt de hashcode op voor deze instantie. |
| [set_AddressLine1](./set_addressline1/)(System::String) | Stelt de adresregel 1 in. |
| [set_AddressLine2](./set_addressline2/)(System::String) | Stelt de adresregel 2 in. |
| [set_CountryCode](./set_countrycode/)(System::String) | Stelt de tweeletterige ISO-landcode in. |
| [set_HouseNo](./set_houseno/)(System::String) | Stelt het huisnummer in. |
| [set_Name](./set_name/)(System::String) | Stelt de naam in, ofwel de voor- en achternaam van een natuurlijke persoon of de bedrijfsnaam van een rechtspersoon. |
| [set_PostalCode](./set_postalcode/)(System::String) | Stelt de postcode in. |
| [set_Street](./set_street/)(System::String) | Stelt de straat in. |
| [set_Town](./set_town/)(System::String) | Stelt de plaats of stad in. |
## Opmerkingen


U kunt ofwel straat, huisnummer, postcode en plaats instellen (type *structured address*) of adresregel 1 en 2 (type *combined address elements*). Het type wordt automatisch ingesteld zodra een van deze velden is ingesteld. Voor het instellen van de velden is het adrestype *undetermined*. Als velden van beide types zijn ingesteld, wordt het adrestype *conflicting*. Naam en landcode moeten altijd worden ingesteld, tenzij alle velden leeg zijn.
## Zie ook

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
