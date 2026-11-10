---
title: "Κλάση MailmarkCodetext"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.ComplexBarcode.MailmarkCodetext κλάση. Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα 4state Royal Mailmark."
type: docs
weight: 670
url: /el/net/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα 4-state Royal Mailmark.

```csharp
public sealed class MailmarkCodetext : IComplexCodetext
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MailmarkCodetext](mailmarkcodetext/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmarkcodetext/class/) { get; set; } | "0" - Μηδενικό ή Δοκιμή "1" - 1C (Λιανική) "2" - 2C (Λιανική) "3" - 3C (Λιανική) "4" - Premium (RetailPublishing Mail) (για πιθανή μελλοντική χρήση) "5" - Deferred (Λιανική) "6" - Air (Λιανική) (για πιθανή μελλοντική χρήση) "7" - Surface (Λιανική) (για πιθανή μελλοντική χρήση) "8" - Premium (Πρόσβαση Δικτύου) "9" - Standard (Πρόσβαση Δικτύου) |
| [DestinationPostCodePlusDPS](../../aspose.barcode.complexbarcode/mailmarkcodetext/destinationpostcodeplusdps/) { get; set; } | Το PC και το DP πρέπει να συμμορφώνονται με μορφή PAF. Συμβολοσειρά εννέα χαρακτήρων που υποδεικνύει το διεθνές "XY11 " (σημειώστε τα 5 κενά στο τέλος) ή ένα μοτίβο χαρακτήρων που υποδεικνύει έναν εγχώριο κωδικό ταξινόμησης. Ένας εγχώριος κωδικός ταξινόμησης αποτελείται από έναν εξωτερικό ταχυδρομικό κώδικα, έναν εσωτερικό ταχυδρομικό κώδικα και ένα επίθημα σημείου παράδοσης. |
| [Format](../../aspose.barcode.complexbarcode/mailmarkcodetext/format/) { get; set; } | "0" – Μηδενικό ή Δοκιμή "1" – Γράμμα "2" – Μεγάλο Γράμμα |
| [ItemID](../../aspose.barcode.complexbarcode/mailmarkcodetext/itemid/) { get; set; } | Η μέγιστη τιμή είναι 99999999. |
| [SupplychainID](../../aspose.barcode.complexbarcode/mailmarkcodetext/supplychainid/) { get; set; } | Οι μέγιστες τιμές είναι 99 για το Barcode C και 999999 για το Barcode L. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmarkcodetext/versionid/) { get; set; } | Προς το παρόν "1" – Για το barcode Mailmark (0 και 2 έως 9 και A έως Z διατηρούνται για μελλοντική χρήση) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmarkcodetext/getbarcodetype/)() | Λαμβάνει τον τύπο του barcode. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmarkcodetext/getconstructedcodetext/)() | Δημιουργήστε κείμενο κώδικα από τα δεδομένα Mailmark. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmarkcodetext/initfromstring/)(string) | Αρχικοποιεί τα δεδομένα Mailmark από το δημιουργημένο κείμενο κώδικα. |

### Δείτε επίσης

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


