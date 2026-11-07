---
title: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink κλάση"
linktitle: "GS1DigitalLink"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink κλάση. Αντιπροσωπεύει το κείμενο κώδικα GS1 Digital Link για κωδικοποίηση και αποκωδικοποίηση ως μια διατεταγμένη ακολουθία στοιχείων Application Identifier. Η σειρά προέλευσης και τα επαναλαμβανόμενα Application Identifier διατηρούνται. Το κατασκευασμένο κείμενο κώδικα είναι ένα μη συμπιεσμένο URI GS1 Digital Link. Οι μη‑GS1 παράμετροι ερωτήματος και τα τμήματα URI αγνοούνται κατά την ανάλυση σε C++."
type: docs
weight: 600
url: /el/cpp/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class


Αναπαριστά το κείμενο κώδικα GS1 Digital Link για κωδικοποίηση και αποκωδικοποίηση ως μια διατεταγμένη ακολουθία στοιχείων Αναγνωριστικού Εφαρμογής. Η αρχική σειρά και τα επαναλαμβανόμενα Αναγνωριστικά Εφαρμογής διατηρούνται. Το κατασκευασμένο κείμενο κώδικα είναι ένα ασυμπίεστο URI GS1 Digital Link. Οι μη‑GS1 παράμετροι ερωτήματος και τα τμήματα URI αγνοούνται κατά την ανάλυση.

```cpp
class GS1DigitalLink : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Προσθέτει ένα επικυρωμένο στοιχείο Application Identifier. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>) | Δημιουργεί ένα GS1 Digital Link αντιγράφοντας όλα τα στοιχεία από το κείμενο κώδικα GS1 και επιλέγοντας το μοναδικό διαθέσιμο πρωτεύον κλειδί. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>, System::String) | Δημιουργεί ένα GS1 Digital Link αντιγράφοντας όλα τα στοιχεία από το κείμενο κώδικα GS1 και χρησιμοποιώντας το καθορισμένο πρωτεύον κλειδί. |
| [get_BarcodeType](./get_barcodetype/)() const | Ανακτά τον τύπο barcode που χρησιμοποιείται για την κωδικοποίηση αυτού του GS1 Digital Link. Οι υποστηριζόμενοι τύποι είναι QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF και Code128. Η προεπιλεγμένη τιμή είναι QR. |
| [get_Count](./get_count/)() | Ανακτά τον αριθμό των στοιχείων Application Identifier. |
| [get_Elements](./get_elements/)() | Ανακτά ένα αντίγραφο όλων των στοιχείων με τη σειρά προέλευσης. |
| [get_PrimaryApplicationIdentifier](./get_primaryapplicationidentifier/)() const | Ανακτά το Application Identifier που χρησιμοποιείται ως πρωτεύον κλειδί Digital Link. Η τιμή Null σημαίνει ότι το πρωτεύον κλειδί επιλέγεται αυτόματα όταν κατασκευάζεται το URI. |
| [get_UriStem](./get_uristem/)() const | Ανακτά το απόλυτο πρόθεμα URI πριν από το τμήμα διαδρομής του πρωτεύοντος κλειδιού GS1. Το πρόθεμα δεν περιέχει συμβολοσειρά ερωτήματος ή τμήμα. |
| [GetAll](./getall/)(System::String) | Λαμβάνει όλες τις τιμές για ένα Application Identifier με τη σειρά προέλευσης. |
| [GetBarcodeType](./getbarcodetype/)() override | Λαμβάνει τον τύπο barcode που χρησιμοποιείται για την κωδικοποίηση αυτού του GS1 Digital Link. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Δημιουργεί το μη συμπιεσμένο GS1 Digital Link URI. |
| [GetFirst](./getfirst/)(System::String) | Λαμβάνει την πρώτη τιμή για ένα Application Identifier. |
| [GS1DigitalLink](./gs1digitallink/)(System::String) | Αρχικοποιεί ένα κενό GS1 Digital Link με το καθορισμένο τμήμα URI. Το πρωτεύον κλειδί επιλέγεται αυτόματα όταν υπάρχει ακριβώς ένας υποψήφιος πρωτεύων κλειδιού. |
| [GS1DigitalLink](./gs1digitallink/)(System::String, System::String) | Αρχικοποιεί ένα κενό GS1 Digital Link με το καθορισμένο τμήμα URI και το πρωτεύον κλειδί. |
| [idx_get](./idx_get/)(int32_t) | Λαμβάνει ένα στοιχείο με βάση τη θέση του στην ταξινομημένη ακολουθία. |
| [InitFromString](./initfromstring/)(System::String) override | Αρχικοποιεί αυτήν την παρουσία από ένα μη συμπιεσμένο GS1 Digital Link URI. Η υπάρχουσα κατάσταση αντικαθίσταται μόνο αφού το παρεχόμενο URI αναλυθεί επιτυχώς. Ο επιλεγμένος τύπος barcode διατηρείται. |
| static [Parse](./parse/)(System::String) | Αναλύει ένα μη συμπιεσμένο GS1 Digital Link URI. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Ορίζει τον τύπο barcode που χρησιμοποιείται για την κωδικοποίηση αυτού του GS1 Digital Link. Οι υποστηριζόμενοι τύποι είναι QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF και Code128. Η προεπιλεγμένη τιμή είναι QR. |
| [ToGS1Codetext](./togs1codetext/)() | Δημιουργεί ένα ανεξάρτητο GS1 codetext που περιέχει τα τρέχοντα στοιχεία GS1. Οι πληροφορίες μόνο URI δεν περιλαμβάνονται. |
| [ToString](./tostring/)() const override | Επιστρέφει το μη συμπιεσμένο GS1 Digital Link URI. |
| [ToUriString](./touristring/)() | Διαμορφώνει την τρέχουσα κατάσταση του αντικειμένου ως μη συμπιεσμένο GS1 Digital Link URI. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1DigitalLink\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Προσπαθεί να αναλύσει ένα μη συμπιεσμένο GS1 Digital Link URI και επιστρέφει δομημένα σφάλματα επικύρωσης. |
| static [Validate](./validate/)(System::String) | Επικυρώνει ένα μη συμπιεσμένο GS1 Digital Link URI χωρίς τη δημιουργία αντικειμένου. |
## Δείτε επίσης

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
