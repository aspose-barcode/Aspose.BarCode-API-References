---
title: "Κλάση Aspose::BarCode::ComplexBarcode::Address"
linktitle: "Διεύθυνση"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Κλάση Aspose::BarCode::ComplexBarcode::Address. Διεύθυνση του πιστωτή ή του οφειλέτη σε C++."
type: docs
weight: 100
url: /el/cpp/aspose.barcode.complexbarcode/address/
---
## Address class


[Address](./) of creditor or debtor.

```cpp
class Address : public System::IEquatable<System::SharedPtr<Address>>
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [Address](./address/)() | Δημιουργεί μια παρουσία του [Address](./) |
| [Clear](./clear/)() | Καθαρίζει όλα τα πεδία και ορίζει τον τύπο σε [AddressType::Undetermined](../addresstype/). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Καθορίζει εάν το καθορισμένο αντικείμενο είναι ίσο με το τρέχον αντικείμενο. |
| [Equals](./equals/)(System::SharedPtr\<Address\>) override | Καθορίζει εάν η καθορισμένη διεύθυνση είναι ίση με την τρέχουσα διεύθυνση. |
| [get_AddressLine1](./get_addressline1/)() const | Λαμβάνει τη γραμμή διεύθυνσης 1. |
| [get_AddressLine2](./get_addressline2/)() const | Λαμβάνει τη γραμμή διεύθυνσης 2. |
| [get_CountryCode](./get_countrycode/)() const | Λαμβάνει τον διψήφιο κωδικό χώρας ISO. |
| [get_HouseNo](./get_houseno/)() const | Λαμβάνει τον αριθμό σπιτιού. |
| [get_Name](./get_name/)() const | Λαμβάνει το όνομα, είτε το όνομα και επώνυμο φυσικού προσώπου είτε το όνομα εταιρείας νομικού προσώπου. |
| [get_PostalCode](./get_postalcode/)() const | Λαμβάνει τον ταχυδρομικό κώδικα. |
| [get_Street](./get_street/)() const | Λαμβάνει το όνομα οδού. |
| [get_Town](./get_town/)() const | Λαμβάνει την κωμόπολη ή την πόλη. |
| [get_Type](./get_type/)() const | Λαμβάνει τον τύπο διεύθυνσης. |
| [GetHashCode](./gethashcode/)() const override | Λαμβάνει τον κώδικα κατακερματισμού για αυτήν την παρουσία. |
| [set_AddressLine1](./set_addressline1/)(System::String) | Ορίζει τη γραμμή διεύθυνσης 1. |
| [set_AddressLine2](./set_addressline2/)(System::String) | Ορίζει τη γραμμή διεύθυνσης 2. |
| [set_CountryCode](./set_countrycode/)(System::String) | Ορίζει τον διψήφιο κωδικό χώρας ISO. |
| [set_HouseNo](./set_houseno/)(System::String) | Ορίζει τον αριθμό σπιτιού. |
| [set_Name](./set_name/)(System::String) | Ορίζει το όνομα, είτε το όνομα και επώνυμο φυσικού προσώπου είτε το όνομα εταιρείας νομικού προσώπου. |
| [set_PostalCode](./set_postalcode/)(System::String) | Ορίζει τον ταχυδρομικό κώδικα. |
| [set_Street](./set_street/)(System::String) | Ορίζει την οδό. |
| [set_Town](./set_town/)(System::String) | Ορίζει την πόλη ή το κωμόπολη. |
## Σχόλια


Μπορείτε είτε να ορίσετε την οδό, τον αριθμό σπιτιού, τον ταχυδρομικό κώδικα και την πόλη (τύπος *structured address*) είτε τη γραμμή διεύθυνσης 1 και 2 (τύπος *combined address elements*). Ο τύπος ορίζεται αυτόματα μόλις οριστεί οποιοδήποτε από αυτά τα πεδία. Πριν οριστούν τα πεδία, ο τύπος διεύθυνσης είναι *undetermined*. Εάν οριστούν πεδία και των δύο τύπων, ο τύπος διεύθυνσης γίνεται *conflicting*. Το όνομα και ο κωδικός χώρας πρέπει πάντα να ορίζονται εκτός εάν όλα τα πεδία είναι κενά.
## Δείτε επίσης

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
