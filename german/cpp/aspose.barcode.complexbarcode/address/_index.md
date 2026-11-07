---
title: "Aspose::BarCode::ComplexBarcode::Address Klasse"
linktitle: "Address"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::Address Klasse. Address des Gläubigers oder Schuldners in C++."
type: docs
weight: 100
url: /de/cpp/aspose.barcode.complexbarcode/address/
---
## Address class


[Address](./) of creditor or debtor.

```cpp
class Address : public System::IEquatable<System::SharedPtr<Address>>
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [Address](./address/)() | Erstellt eine Instanz von [Address](./) |
| [Clear](./clear/)() | Löscht alle Felder und setzt den Typ auf [AddressType::Undetermined](../addresstype/). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Bestimmt, ob das angegebene Objekt dem aktuellen Objekt gleich ist. |
| [Equals](./equals/)(System::SharedPtr\<Address\>) override | Bestimmt, ob die angegebene Adresse der aktuellen Adresse entspricht. |
| [get_AddressLine1](./get_addressline1/)() const | Liefert die Adresszeile 1. |
| [get_AddressLine2](./get_addressline2/)() const | Liefert die Adresszeile 2. |
| [get_CountryCode](./get_countrycode/)() const | Liefert den zweibuchstabigen ISO-Ländercode. |
| [get_HouseNo](./get_houseno/)() const | Liefert die Hausnummer. |
| [get_Name](./get_name/)() const | Liefert den Namen, entweder den Vor- und Nachnamen einer natürlichen Person oder den Firmennamen einer juristischen Person. |
| [get_PostalCode](./get_postalcode/)() const | Liefert die Postleitzahl. |
| [get_Street](./get_street/)() const | Liefert die Straße. |
| [get_Town](./get_town/)() const | Liefert die Stadt oder Gemeinde. |
| [get_Type](./get_type/)() const | Liefert den Adresstyp. |
| [GetHashCode](./gethashcode/)() const override | Liefert den Hashcode für diese Instanz. |
| [set_AddressLine1](./set_addressline1/)(System::String) | Setzt die Adresszeile 1. |
| [set_AddressLine2](./set_addressline2/)(System::String) | Setzt die Adresszeile 2. |
| [set_CountryCode](./set_countrycode/)(System::String) | Setzt den zweibuchstabigen ISO-Ländercode. |
| [set_HouseNo](./set_houseno/)(System::String) | Setzt die Hausnummer. |
| [set_Name](./set_name/)(System::String) | Setzt den Namen, entweder den Vor- und Nachnamen einer natürlichen Person oder den Firmennamen einer juristischen Person. |
| [set_PostalCode](./set_postalcode/)(System::String) | Setzt die Postleitzahl. |
| [set_Street](./set_street/)(System::String) | Setzt die Straße. |
| [set_Town](./set_town/)(System::String) | Setzt die Stadt oder Gemeinde. |
## Hinweise


Sie können entweder Straße, Hausnummer, Postleitzahl und Stadt (Typ *structured address*) oder Adresszeile 1 und 2 (Typ *combined address elements*) festlegen. Der Typ wird automatisch gesetzt, sobald eines dieser Felder gesetzt ist. Vor dem Setzen der Felder ist der Adresstyp *undetermined*. Wenn Felder beider Typen gesetzt werden, wird der Adresstyp *conflicting*. Name und Ländercode müssen immer gesetzt sein, es sei denn, alle Felder sind leer.
## Siehe auch

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
