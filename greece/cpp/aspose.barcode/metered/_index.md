---
title: "Aspose::BarCode::Metered κλάση"
linktitle: "Μετρημένο"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::Metered κλάση. Παρέχει μεθόδους για ορισμό του κλειδιού metered σε C++."
type: docs
weight: 500
url: /el/cpp/aspose.barcode/metered/
---
## Metered class


Παρέχει μεθόδους για τον ορισμό κλειδιού μετρητή.

```cpp
class Metered : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | Λαμβάνει πίστωση κατανάλωσης |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | Λαμβάνει το μέγεθος αρχείου κατανάλωσης |
| [GetProductName](./getproductname/)() | Λαμβάνει το όνομα του αδειοδοτημένου προϊόντος |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | Ελέγξτε εάν το metered είναι αδειοδοτημένο |
| [Metered](./metered/)() | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης. |
| [SetMeteredKey](./setmeteredkey/)(System::String, System::String) | Ορίζει το δημόσιο και ιδιωτικό κλειδί metered. Εάν αγοράσετε άδεια metered, όταν ξεκινάτε την εφαρμογή, αυτό το API πρέπει να κληθεί· συνήθως αυτό είναι αρκετό. Ωστόσο, εάν αποτυγχάνει συνεχώς η μεταφόρτωση δεδομένων κατανάλωσης και υπερβαίνει τις 24 ώρες, η άδεια θα οριστεί σε κατάσταση αξιολόγησης· για να αποφύγετε αυτήν την περίπτωση, πρέπει να ελέγχετε τακτικά την κατάσταση της άδειας· εάν είναι σε κατάσταση αξιολόγησης, καλέστε ξανά αυτό το API. |
## Σχόλια


Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να οριστεί το δημόσιο και ιδιωτικό κλειδί metered

<ms>
```cpp
[C#]
@verbatim
Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
@endverbatim
```
</ms>

<java> το αρχείο jar του στοιχείου:
```cpp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```
</java>
## Δείτε επίσης

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
