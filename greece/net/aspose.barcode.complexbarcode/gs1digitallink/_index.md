---
title: "Class GS1DigitalLink"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.ComplexBarcode.GS1DigitalLink class. Αντιπροσωπεύει το κείμενο κώδικα GS1 Digital Link για κωδικοποίηση και αποκωδικοποίηση ως μια διατεταγμένη ακολουθία στοιχείων Αναγνωριστικού Εφαρμογής. Η σειρά προέλευσης και τα επαναλαμβανόμενα Αναγνωριστικά Εφαρμογής διατηρούνται. Το κατασκευασμένο κείμενο κώδικα είναι ένα μη συμπιεσμένο URI GS1 Digital Link. Οι μη‑GS1 παράμετροι ερωτήματος και τα τμήματα URI αγνοούνται κατά την ανάλυση."
type: docs
weight: 540
url: /el/net/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class

Αντιπροσωπεύει το κείμενο κώδικα GS1 Digital Link για κωδικοποίηση και αποκωδικοποίηση ως μια διατεταγμένη ακολουθία στοιχείων Αναγνωριστικού Εφαρμογής. Η αρχική σειρά και τα επαναλαμβανόμενα Αναγνωριστικά Εφαρμογής διατηρούνται. Το κατασκευασμένο κείμενο κώδικα είναι ένα μη συμπιεσμένο URI GS1 Digital Link. Οι μη‑GS1 παράμετροι ερωτήματος και τα τμήματα URI αγνοούνται κατά την ανάλυση.

```csharp
public sealed class GS1DigitalLink : IComplexCodetext
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [GS1DigitalLink](gs1digitallink/#constructor)(string) | Αρχικοποιεί ένα κενό GS1 Digital Link με το καθορισμένο τμήμα URI. Το πρωτεύον κλειδί επιλέγεται αυτόματα όταν υπάρχει ακριβώς ένας υποψήφιος πρωτεύον κλειδί. |
| [GS1DigitalLink](gs1digitallink/#constructor_1)(string, string) | Αρχικοποιεί ένα κενό GS1 Digital Link με το καθορισμένο τμήμα URI και το πρωτεύον κλειδί. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/barcodetype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο barcode που χρησιμοποιείται για την κωδικοποίηση αυτού του GS1 Digital Link. Οι υποστηριζόμενοι τύποι είναι QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF και Code128. Η προεπιλεγμένη τιμή είναι QR. |
| [Count](../../aspose.barcode.complexbarcode/gs1digitallink/count/) { get; } | Λαμβάνει τον αριθμό των στοιχείων Application Identifier. |
| [Elements](../../aspose.barcode.complexbarcode/gs1digitallink/elements/) { get; } | Λαμβάνει ένα αντίγραφο όλων των στοιχείων με τη σειρά προέλευσης. |
| [Item](../../aspose.barcode.complexbarcode/gs1digitallink/item/) { get; } | Λαμβάνει ένα στοιχείο με βάση τη θέση του στην ταξινομημένη ακολουθία. |
| [PrimaryApplicationIdentifier](../../aspose.barcode.complexbarcode/gs1digitallink/primaryapplicationidentifier/) { get; } | Λαμβάνει το Application Identifier που χρησιμοποιείται ως το κύριο κλειδί του Digital Link. Null σημαίνει ότι το κύριο κλειδί επιλέγεται αυτόματα όταν δημιουργείται το URI. |
| [UriStem](../../aspose.barcode.complexbarcode/gs1digitallink/uristem/) { get; } | Λαμβάνει το απόλυτο πρόθεμα URI πριν από το τμήμα διαδρομής του κύριου κλειδιού GS1. Το υπόλοιπο δεν περιέχει αλφαριθμητικό ερωτήματος ή απόσπασμα. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create)(string, GS1Codetext) | Δημιουργεί ένα GS1 Digital Link αντιγράφοντας όλα τα στοιχεία από το GS1 codetext και επιλέγοντας το μοναδικό διαθέσιμο κύριο κλειδί. |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create_1)(string, GS1Codetext, string) | Δημιουργεί ένα GS1 Digital Link αντιγράφοντας όλα τα στοιχεία από το GS1 codetext και χρησιμοποιώντας το καθορισμένο κύριο κλειδί. |
| static [Parse](../../aspose.barcode.complexbarcode/gs1digitallink/parse/)(string) | Αναλύει ένα μη συμπιεσμένο GS1 Digital Link URI. |
| [Add](../../aspose.barcode.complexbarcode/gs1digitallink/add/)(string, string) | Προσθέτει ένα επικυρωμένο στοιχείο Application Identifier. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1digitallink/getall/)(string) | Λαμβάνει όλες τις τιμές για ένα Application Identifier με τη σειρά προέλευσης. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/getbarcodetype/)() | Λαμβάνει τον τύπο barcode που χρησιμοποιείται για την κωδικοποίηση αυτού του GS1 Digital Link. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1digitallink/getconstructedcodetext/)() | Κατασκευάζει το μη συμπιεσμένο GS1 Digital Link URI. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1digitallink/getfirst/)(string) | Λαμβάνει την πρώτη τιμή για ένα Application Identifier. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1digitallink/initfromstring/)(string) | Αρχικοποιεί αυτήν την παρουσία από ένα μη συμπιεσμένο GS1 Digital Link URI. Η υπάρχουσα κατάσταση αντικαθίσταται μόνο αφού το παρεχόμενο URI έχει αναλυθεί επιτυχώς. Ο επιλεγμένος τύπος barcode διατηρείται. |
| [ToGS1Codetext](../../aspose.barcode.complexbarcode/gs1digitallink/togs1codetext/)() | Δημιουργεί ένα ανεξάρτητο GS1 codetext που περιέχει τα τρέχοντα στοιχεία GS1. Πληροφορίες μόνο URI δεν περιλαμβάνονται. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1digitallink/tostring/)() | Επιστρέφει το μη συμπιεσμένο GS1 Digital Link URI. |
| [ToUriString](../../aspose.barcode.complexbarcode/gs1digitallink/touristring/)() | Διαμορφώνει την τρέχουσα κατάσταση του αντικειμένου ως μη συμπιεσμένο GS1 Digital Link URI. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1digitallink/tryparse/)(string, out GS1DigitalLink, out GS1ValidationResult) | Προσπαθεί να αναλύσει ένα μη συμπιεσμένο GS1 Digital Link URI και επιστρέφει δομημένα σφάλματα επικύρωσης. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1digitallink/validate/)(string) | Επικυρώνει ένα μη συμπιεσμένο GS1 Digital Link URI χωρίς να δημιουργήσει αντικείμενο. |

### Δείτε επίσης

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


