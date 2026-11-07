---
title: "Aspose::BarCode::ComplexBarcode::GS1Codetext class"
linktitle: "GS1Codetext"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::ComplexBarcode::GS1Codetext class. Αντιπροσωπεύει το GS1 codetext για κωδικοποίηση και αποκωδικοποίηση ως μια ταξινομημένη ακολουθία στοιχείων Application Identifier. Η σειρά προέλευσης και οι επαναλαμβανόμενοι Application Identifiers διατηρούνται. Η αγκυλωμένη αναπαράσταση έχει τη μορφή (AI)value(AI)value. Ένα κυριολεκτικό ανοιχτό παρενθέσιο ''('' μέσα σε τιμή πρέπει να γραφτεί ως (; αυτή είναι η μοναδική υποστηριζόμενη ακολουθία διαφυγής. Ένα κλειστό παρενθέσιο '')'' μέσα σε τιμή δεν απαιτεί διαφυγή σε C++."
type: docs
weight: 500
url: /el/cpp/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class


Αναπαριστά το κείμενο κώδικα GS1 για κωδικοποίηση και αποκωδικοποίηση ως μια διατεταγμένη ακολουθία στοιχείων Αναγνωριστικού Εφαρμογής. Η αρχική σειρά και τα επαναλαμβανόμενα Αναγνωριστικά Εφαρμογής διατηρούνται. Η αναπαράσταση με αγκύλες έχει τη μορφή (AI)value(AI)value. Ένα κυριολεκτικό αριστερό παρενθέσιο '(' μέσα σε μια τιμή πρέπει να γραφτεί ως (; αυτή είναι η μόνη υποστηριζόμενη ακολουθία διαφυγής. Ένα δεξιό παρενθέσιο ')' μέσα σε μια τιμή δεν απαιτεί διαφυγή.

```cpp
class GS1Codetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Προσθέτει ένα επικυρωμένο στοιχείο Application Identifier. |
| [get_BarcodeType](./get_barcodetype/)() const | Λαμβάνει τον τύπο barcode που χρησιμοποιείται για την κωδικοποίηση αυτού του GS1 codetext. Οι υποστηριζόμενοι τύποι είναι GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR και τύποι GS1 DataBar. Η προεπιλεγμένη τιμή είναι GS1Code128. |
| [get_Count](./get_count/)() | Ανακτά τον αριθμό των στοιχείων Application Identifier. |
| [get_Elements](./get_elements/)() | Ανακτά ένα αντίγραφο όλων των στοιχείων με τη σειρά προέλευσης. |
| [GetAll](./getall/)(System::String) | Λαμβάνει όλες τις τιμές για ένα Application Identifier με τη σειρά προέλευσης. |
| [GetBarcodeType](./getbarcodetype/)() override | Λαμβάνει τον τύπο barcode που χρησιμοποιείται για την κωδικοποίηση αυτού του GS1 codetext. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Δημιουργεί το αγκυλωμένο GS1 codetext στη μορφή (AI)value(AI)value. Τα κυριολεκτικά ανοιχτά παρενθέσια στις τιμές διαφεύγουν ως (. |
| [GetFirst](./getfirst/)(System::String) | Λαμβάνει την πρώτη τιμή για ένα Application Identifier. |
| [GS1Codetext](./gs1codetext/)() | Αρχικοποιεί ένα κενό GS1 codetext. |
| [idx_get](./idx_get/)(int32_t) | Λαμβάνει ένα στοιχείο με βάση τη θέση του στην ταξινομημένη ακολουθία. |
| [InitFromString](./initfromstring/)(System::String) override | Αρχικοποιεί αυτήν την παρουσία από αγκυλωμένο GS1 codetext στη μορφή (AI)value(AI)value. Τα υπάρχοντα στοιχεία αντικαθίστανται μόνο αφού το παρεχόμενο codetext αναλυθεί επιτυχώς. |
| static [Parse](./parse/)(System::String) | Αναλύει μια αγκυλωμένη συμβολοσειρά στοιχείου GS1 στη μορφή (AI)value(AI)value. Ένα κυριολεκτικό '(' μέσα σε τιμή πρέπει να γραφτεί ως (; δεν υποστηρίζεται άλλη ακολουθία διαφυγής, και το ')' δεν απαιτεί διαφυγή. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Ορίζει τον τύπο barcode που χρησιμοποιείται για την κωδικοποίηση αυτού του GS1 codetext. Οι υποστηριζόμενοι τύποι είναι GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR και τύποι GS1 DataBar. Η προεπιλεγμένη τιμή είναι GS1Code128. |
| [ToString](./tostring/)() const override | Επιστρέφει την αγκυλωμένη αναπαράσταση GS1 στη μορφή (AI)value(AI)value. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1Codetext\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Προσπαθεί να αναλύσει μια αγκυλωμένη συμβολοσειρά στοιχείου GS1 στη μορφή (AI)value(AI)value και επιστρέφει δομημένα σφάλματα επικύρωσης. Ένα κυριολεκτικό '(' μέσα σε μια τιμή πρέπει να γραφτεί ως (; δεν υποστηρίζεται άλλη ακολουθία διαφυγής, και το ')' δεν απαιτεί διαφυγή. |
| static [Validate](./validate/)(System::String) | Επικυρώνει μια αγκυλωμένη συμβολοσειρά στοιχείου GS1 στη μορφή (AI)value(AI)value χωρίς να δημιουργήσει αντικείμενο. Ένα κυριολεκτικό '(' μέσα σε μια τιμή πρέπει να γραφτεί ως (; δεν υποστηρίζεται άλλη ακολουθία διαφυγής, και το ')' δεν απαιτεί διαφυγή. |
## Δείτε επίσης

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
