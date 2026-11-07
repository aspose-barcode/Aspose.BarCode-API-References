---
title: "Aspose::BarCode::ComplexBarcode::Payments κλάση"
linktitle: "Payments"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::ComplexBarcode::Payments κλάση. Επικυρώσεις πεδίων σχετικές με τα πρότυπα Swiss Payment σε C++."
type: docs
weight: 2400
url: /el/cpp/aspose.barcode.complexbarcode/payments/
---
## Payments class


Επικυρώσεις πεδίων σχετικές με τα πρότυπα Swiss Payment.

```cpp
class Payments
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| static [CleanValue](./cleanvalue/)(System::String, Payments::CleaningResult\&) | Καθαρίζει μια τιμή συμβολοσειράς ώστε να είναι κατάλληλη για τα Swiss Payment Standards 2018. |
| static [CreateIso11649Reference](./createiso11649reference/)(System::String) | Δημιουργεί μια αναφορά πιστωτή ISO11649 από μια ακατέργαστη συμβολοσειρά προσθέτοντας στην αρχή της τη συμβολοσειρά "RF" και το υπόλοιπο modulo 97. |
| static [FormatIban](./formatiban/)(System::String) | Μορφοποιεί ένα IBAN ή μια αναφορά πιστωτή προσθέτοντας κενά. |
| static [FormatQrReferenceNumber](./formatqrreferencenumber/)(System::String) | Μορφοποιεί έναν αριθμό QR αναφοράς προσθέτοντας κενά. |
| static [IsAlphaNumeric](./isalphanumeric/)(System::String) |  |
| static [IsValidIban](./isvalidiban/)(System::String) | Επικυρώνει εάν η συμβολοσειρά είναι έγκυρος αριθμός IBAN |
| static [IsValidIso11649Reference](./isvalidiso11649reference/)(System::String) | Επικυρώνει εάν η συμβολοσειρά είναι έγκυρος αριθμός αναφοράς ISO 11649 |
| static [IsValidQrReference](./isvalidqrreference/)(System::String) | Επικυρώνει εάν η συμβολοσειρά είναι έγκυρη QR αναφορά. |
| [Payments](./payments/)() |  |
## Δείτε επίσης

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
