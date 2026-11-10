---
title: "Κλάση GS1Codetext"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.ComplexBarcode.GS1Codetext κλάση. Αντιπροσωπεύει το GS1 codetext για κωδικοποίηση και αποκωδικοποίηση ως μια ταξινομημένη ακολουθία στοιχείων Application Identifier. Η σειρά προέλευσης και τα επαναλαμβανόμενα Application Identifier διατηρούνται. Η αγκυλωμένη αναπαράσταση έχει τη μορφή AIvalueAIvalue. Ένα κυριολεκτικό ανοιχτό παρενθέσεων  μέσα σε μια τιμή πρέπει να γραφτεί ως  αυτό είναι η μοναδική υποστηριζόμενη ακολουθία διαφυγής. Ένα κλειστό παρενθέσεων  μέσα σε μια τιμή δεν απαιτεί διαφυγή."
type: docs
weight: 530
url: /el/net/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class

Αντιπροσωπεύει το κείμενο κώδικα GS1 για κωδικοποίηση και αποκωδικοποίηση ως μια διατεταγμένη ακολουθία στοιχείων Αναγνωριστικού Εφαρμογής. Η αρχική σειρά και τα επαναλαμβανόμενα Αναγνωριστικά Εφαρμογής διατηρούνται. Η παρενθετική αναπαράσταση έχει τη μορφή (AI)value(AI)value. Ένα κυριολεκτικό αριστερό παρενθετικό '(' μέσα σε μια τιμή πρέπει να γραφτεί ως \(; αυτή είναι η μόνη υποστηριζόμενη ακολουθία διαφυγής. Ένα δεξιό παρενθετικό ')' μέσα σε μια τιμή δεν απαιτεί διαφυγή.

```csharp
public sealed class GS1Codetext : IComplexCodetext
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [GS1Codetext](gs1codetext/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/barcodetype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο barcode που χρησιμοποιείται για την κωδικοποίηση αυτού του GS1 codetext. Οι υποστηριζόμενοι τύποι είναι GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR και τύποι GS1 DataBar. Η προεπιλεγμένη τιμή είναι GS1Code128. |
| [Count](../../aspose.barcode.complexbarcode/gs1codetext/count/) { get; } | Λαμβάνει τον αριθμό των στοιχείων Application Identifier. |
| [Elements](../../aspose.barcode.complexbarcode/gs1codetext/elements/) { get; } | Λαμβάνει ένα αντίγραφο όλων των στοιχείων με τη σειρά προέλευσης. |
| [Item](../../aspose.barcode.complexbarcode/gs1codetext/item/) { get; } | Λαμβάνει ένα στοιχείο με βάση τη θέση του στην ταξινομημένη ακολουθία. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [Parse](../../aspose.barcode.complexbarcode/gs1codetext/parse/)(string) | Αναλύει μια αγκυλωμένη συμβολοσειρά στοιχείου GS1 στη μορφή (AI)value(AI)value. Ένα κυριολεκτικό '(' μέσα σε μια τιμή πρέπει να γραφτεί ως \\(; καμία άλλη ακολουθία διαφυγής δεν υποστηρίζεται, και ')' δεν απαιτεί διαφυγή. |
| [Add](../../aspose.barcode.complexbarcode/gs1codetext/add/)(string, string) | Προσθέτει ένα επικυρωμένο στοιχείο Application Identifier. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1codetext/getall/)(string) | Λαμβάνει όλες τις τιμές για ένα Application Identifier με τη σειρά προέλευσης. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/getbarcodetype/)() | Λαμβάνει τον τύπο barcode που χρησιμοποιείται για την κωδικοποίηση αυτού του GS1 codetext. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1codetext/getconstructedcodetext/)() | Δημιουργεί το κωδικοποιημένο κείμενο GS1 σε αγκύλες με τη μορφή (AI)value(AI)value. Η κυριολεκτική ανοικτή παρένθεση στις τιμές κωδικοποιείται ως \(. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1codetext/getfirst/)(string) | Λαμβάνει την πρώτη τιμή για ένα Application Identifier. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1codetext/initfromstring/)(string) | Αρχικοποιεί αυτήν την παρουσία από το κωδικοποιημένο κείμενο GS1 σε αγκύλες με τη μορφή (AI)value(AI)value. Τα υπάρχοντα στοιχεία αντικαθίστανται μόνο αφού το παρεχόμενο κείμενο κώδικα έχει αναλυθεί επιτυχώς. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1codetext/tostring/)() | Επιστρέφει την αναπαράσταση του GS1 σε αγκύλες με τη μορφή (AI)value(AI)value. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1codetext/tryparse/)(string, out GS1Codetext, out GS1ValidationResult) | Προσπαθεί να αναλύσει μια συμβολοσειρά στοιχείου GS1 σε αγκύλες με τη μορφή (AI)value(AI)value και επιστρέφει δομημένα σφάλματα επικύρωσης. Μια κυριολεκτική '(' μέσα σε μια τιμή πρέπει να γραφτεί ως \(; δεν υποστηρίζεται άλλη ακολουθία διαφυγής, και το ')' δεν απαιτεί διαφυγή. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1codetext/validate/)(string) | Επικυρώνει μια συμβολοσειρά στοιχείου GS1 σε αγκύλες με τη μορφή (AI)value(AI)value χωρίς να δημιουργήσει αντικείμενο. Μια κυριολεκτική '(' μέσα σε μια τιμή πρέπει να γραφτεί ως \(; δεν υποστηρίζεται άλλη ακολουθία διαφυγής, και το ')' δεν απαιτεί διαφυγή. |

### Δείτε επίσης

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


