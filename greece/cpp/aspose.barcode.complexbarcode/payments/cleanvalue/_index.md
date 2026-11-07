---
title: "μέθοδος"
linktitle: "CleanValue"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " μέθοδος. Καθαρίζει μια τιμή συμβολοσειράς ώστε να είναι κατάλληλη για τα Swiss Payment Standards 2018 σε C++."
type: docs
weight: 100
url: /el/cpp/aspose.barcode.complexbarcode/payments/cleanvalue/
---
## Payments::CleanValue method


Καθαρίζει μια τιμή συμβολοσειράς ώστε να είναι κατάλληλη για τα Swiss Payment Standards 2018.

```cpp
static void Aspose::BarCode::ComplexBarcode::Payments::CleanValue(System::String value, Payments::CleaningResult &result)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | System::String | Η τιμή της συμβολοσειράς για καθαρισμό. |
| result | Payments::CleaningResult\& | Το αποτέλεσμα που θα συμπληρωθεί με την καθαρισμένη συμβολοσειρά και τη σημαία. |
## Σχόλια


Οι μη υποστηριζόμενοι χαρακτήρες (σύμφωνα με τα Swiss Payment Standards 2018, κεφ. 2.4.1 και παράρτημα D) αντικαθίστανται με κενά (μη υποστηριζόμενο λευκό διάστημα) ή τελείες (όλοι οι άλλοι μη υποστηριζόμενοι χαρακτήρες). Τα αρχικά και τα τελικά λευκά διαστήματα αφαιρούνται.

Εάν εντοπιστούν χαρακτήρες πέρα από το 0xff, η συμβολοσειρά πρώτα κανονικοποιείται έτσι ώστε τα γράμματα με ούμλα ή τόνους που εκφράζονται με δύο σημεία κώδικα να συγχωνεύονται σε ένα ενιαίο σημείο κώδικα (εάν είναι δυνατόν), μερικά από τα οποία μπορεί να γίνουν έγκυρα.

Εάν η προκύπτουσα συμβολοσειρά είναι μόνο λευκό διάστημα, **null** επιστρέφεται.

## Δείτε επίσης

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
