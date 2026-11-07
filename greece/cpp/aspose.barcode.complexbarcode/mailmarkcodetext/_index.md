---
title: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext class"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext class. Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον 4-κατάστασης κώδικα Royal Mailmark σε C++."
type: docs
weight: 1500
url: /el/cpp/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class


Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα 4-καταστάσεων Royal Mailmark.

```cpp
class MailmarkCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_Class](./get_class/)() const | "0" - Κενό ή Δοκιμή "1" - 1C (Λιανική) "2" - 2C (Λιανική) "3" - 3C (Λιανική) "4" - Πριμ (RetailPublishing Mail) (για πιθανή μελλοντική χρήση) "5" - Αναβαλλόμενο (Λιανική) "6" - Αερο (Λιανική) (για πιθανή μελλοντική χρήση) "7" - Επιφάνεια (Λιανική) (για πιθανή μελλοντική χρήση) "8" - Πριμ (Πρόσβαση Δικτύου) "9" - Κανονικό (Πρόσβαση Δικτύου) |
| [get_DestinationPostCodePlusDPS](./get_destinationpostcodeplusdps/)() const | Το PC και το DP πρέπει να συμμορφώνονται με μορφή PAF. Συμβολοσειρά εννέα χαρακτήρων που δηλώνει διεθνές "XY11     " (σημειώστε τα 5 κενά στο τέλος) ή ένα μοτίβο χαρακτήρων που δηλώνει εσωτερικό κωδικό ταξινόμησης. Ένας εσωτερικός κωδικός ταξινόμησης αποτελείται από εξωτερικό ταχυδρομικό κώδικα, εσωτερικό ταχυδρομικό κώδικα και επίθημα σημείου παράδοσης. |
| [get_Format](./get_format/)() const | "0" – Κενό ή Δοκιμή "1" – Γράμμα "2" – Μεγάλο Γράμμα |
| [get_ItemID](./get_itemid/)() const | Η μέγιστη τιμή είναι 99999999. |
| [get_SupplychainID](./get_supplychainid/)() const | Οι μέγιστες τιμές είναι 99 για το Barcode C και 999999 για το Barcode L. |
| [get_VersionID](./get_versionid/)() const | Προς το παρόν "1" – Για το barcode Mailmark (0 και 2 έως 9 και A έως Z διατηρούνται για μελλοντική χρήση) |
| [GetBarcodeType](./getbarcodetype/)() override | Λαμβάνει τον τύπο barcode. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Δημιουργήστε κείμενο κώδικα από τα δεδομένα Mailmark. |
| [InitFromString](./initfromstring/)(System::String) override | Αρχικοποιεί τα δεδομένα Mailmark από το κατασκευασμένο κείμενο κώδικα. |
| [MailmarkCodetext](./mailmarkcodetext/)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [MailmarkCodetext](./). |
| [set_Class](./set_class/)(System::String) | "0" - Κενό ή Δοκιμή "1" - 1C (Λιανική) "2" - 2C (Λιανική) "3" - 3C (Λιανική) "4" - Πριμ (RetailPublishing Mail) (για πιθανή μελλοντική χρήση) "5" - Αναβαλλόμενο (Λιανική) "6" - Αερο (Λιανική) (για πιθανή μελλοντική χρήση) "7" - Επιφάνεια (Λιανική) (για πιθανή μελλοντική χρήση) "8" - Πριμ (Πρόσβαση Δικτύου) "9" - Κανονικό (Πρόσβαση Δικτύου) |
| [set_DestinationPostCodePlusDPS](./set_destinationpostcodeplusdps/)(System::String) | Το PC και το DP πρέπει να συμμορφώνονται με μορφή PAF. Συμβολοσειρά εννέα χαρακτήρων που δηλώνει διεθνές "XY11     " (σημειώστε τα 5 κενά στο τέλος) ή ένα μοτίβο χαρακτήρων που δηλώνει εσωτερικό κωδικό ταξινόμησης. Ένας εσωτερικός κωδικός ταξινόμησης αποτελείται από εξωτερικό ταχυδρομικό κώδικα, εσωτερικό ταχυδρομικό κώδικα και επίθημα σημείου παράδοσης. |
| [set_Format](./set_format/)(int32_t) | "0" – Κενό ή Δοκιμή "1" – Γράμμα "2" – Μεγάλο Γράμμα |
| [set_ItemID](./set_itemid/)(int32_t) | Η μέγιστη τιμή είναι 99999999. |
| [set_SupplychainID](./set_supplychainid/)(int32_t) | Οι μέγιστες τιμές είναι 99 για το Barcode C και 999999 για το Barcode L. |
| [set_VersionID](./set_versionid/)(int32_t) | Προς το παρόν "1" – Για το barcode Mailmark (0 και 2 έως 9 και A έως Z διατηρούνται για μελλοντική χρήση) |
## Δείτε επίσης

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
