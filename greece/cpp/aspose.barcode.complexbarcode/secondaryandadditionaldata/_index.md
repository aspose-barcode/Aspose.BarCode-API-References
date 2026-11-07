---
title: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class. Κλάση για αποθήκευση δευτερευόντων και πρόσθετων δεδομένων HIBC LIC σε C++."
type: docs
weight: 2600
url: /el/cpp/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class


Κλάση για αποθήκευση των δευτερευόντων και πρόσθετων δεδομένων HIBC LIC.

```cpp
class SecondaryAndAdditionalData : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [SecondaryAndAdditionalData](./). |
| [get_DateOfManufacture](./get_dateofmanufacture/)() const | Αναγνωρίζει την ημερομηνία κατασκευής. Η ημερομηνία κατασκευής μπορεί να οριστεί σε DateTime.MinValue ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Προεπιλεγμένη τιμή: DateTime.MinValue |
| [get_ExpiryDate](./get_expirydate/)() const | Αναγνωρίζει την ημερομηνία λήξης. Θα χρησιμοποιηθεί εάν το ExpiryDateFormat δεν έχει οριστεί σε None. |
| [get_ExpiryDateFormat](./get_expirydateformat/)() const | Αναγνωρίζει τη μορφή ημερομηνίας λήξης. |
| [get_LotNumber](./get_lotnumber/)() const | Αναγνωρίζει τον αριθμό παρτίδας ή δέσμης. Ο αριθμός παρτίδας/δέσμης πρέπει να είναι αλφαριθμητικό συμβολοσειρά με μήκος έως 18 χαρακτήρες. . |
| [get_Quantity](./get_quantity/)() const | Αναγνωρίζει την ποσότητα, πρέπει να είναι ακέραια τιμή από 0 έως 500. Η ποσότητα μπορεί να οριστεί σε -1 ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Προεπιλεγμένη τιμή: -1 |
| [get_SerialNumber](./get_serialnumber/)() const | Αναγνωρίζει τον σειριακό αριθμό. Ο σειριακός αριθμός πρέπει να είναι αλφαριθμητική συμβολοσειρά έως 18 χαρακτήρες. |
| [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [ParseFromString](./parsefromstring/)(System::String) | Δημιουργεί δευτερεύοντα και πρόσθετα συμπληρωματικά δεδομένα από μορφή συμβολοσειράς σύμφωνα με την προδιαγραφή HIBC LIC. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/)() |  |
| [set_DateOfManufacture](./set_dateofmanufacture/)(System::DateTime) | Αναγνωρίζει την ημερομηνία κατασκευής. Η ημερομηνία κατασκευής μπορεί να οριστεί σε DateTime.MinValue ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Προεπιλεγμένη τιμή: DateTime.MinValue |
| [set_ExpiryDate](./set_expirydate/)(System::DateTime) | Αναγνωρίζει την ημερομηνία λήξης. Θα χρησιμοποιηθεί εάν το ExpiryDateFormat δεν έχει οριστεί σε None. |
| [set_ExpiryDateFormat](./set_expirydateformat/)(HIBCLICDateFormat) | Αναγνωρίζει τη μορφή ημερομηνίας λήξης. |
| [set_LotNumber](./set_lotnumber/)(System::String) | Αναγνωρίζει τον αριθμό παρτίδας ή δέσμης. Ο αριθμός παρτίδας/δέσμης πρέπει να είναι αλφαριθμητικό συμβολοσειρά με μήκος έως 18 χαρακτήρες. . |
| [set_Quantity](./set_quantity/)(int32_t) | Αναγνωρίζει την ποσότητα, πρέπει να είναι ακέραια τιμή από 0 έως 500. Η ποσότητα μπορεί να οριστεί σε -1 ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Προεπιλεγμένη τιμή: -1 |
| [set_SerialNumber](./set_serialnumber/)(System::String) | Αναγνωρίζει τον σειριακό αριθμό. Ο σειριακός αριθμός πρέπει να είναι αλφαριθμητική συμβολοσειρά έως 18 χαρακτήρες. |
| [ToString](./tostring/)() const override | Μετατρέπει τα δεδομένα σε μορφή συμβολοσειράς σύμφωνα με την προδιαγραφή HIBC LIC. |
## Δείτε επίσης

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
