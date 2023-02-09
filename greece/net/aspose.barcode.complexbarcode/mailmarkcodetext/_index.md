---
title: MailmarkCodetext
second_title: Aspose.BarCode για Αναφορά API .NET
description: Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που είναι ενσωματωμένο στον κωδικό Royal Mailmark 4 καταστάσεων.
type: docs
weight: 490
url: /el/net/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που είναι ενσωματωμένο στον κωδικό Royal Mailmark 4 καταστάσεων.

```csharp
public sealed class MailmarkCodetext : IComplexCodetext
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [MailmarkCodetext](mailmarkcodetext/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmarkcodetext/class/) { get; set; } | "0" - Null ή Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (για μελλοντική χρήση) "5" - Deferred (Retail) "6" - Air (Retail) (για πιθανή μελλοντική χρήση) "7" - Surface (Retail) (για πιθανή μελλοντική χρήση) "8" - Premium (Πρόσβαση στο δίκτυο) "9" - Τυπική (Πρόσβαση δικτύου) |
| [DestinationPostCodePlusDPS](../../aspose.barcode.complexbarcode/mailmarkcodetext/destinationpostcodeplusdps/) { get; set; } | Ο υπολογιστής και το DP πρέπει να συμμορφώνονται με μια μορφή PAF. Συμβολοσειρά εννέα χαρακτήρων που δηλώνει διεθνή "XY11" (σημειώστε τα 5 κενά μετά) ή ένα μοτίβο χαρακτήρων που υποδηλώνουν έναν εγχώριο κωδικό ταξινόμησης. Ένας εγχώριος κωδικός ταξινόμησης αποτελείται από έναν εξωτερικό κωδικό έναν εισερχόμενο ταχυδρομικό κώδικα και ένα επίθημα σημείου παράδοσης. |
| [Format](../../aspose.barcode.complexbarcode/mailmarkcodetext/format/) { get; set; } | "0" – Null ή Test "1" – Letter "2" – Large Letter |
| [ItemID](../../aspose.barcode.complexbarcode/mailmarkcodetext/itemid/) { get; set; } | Η μέγιστη τιμή είναι 99999999. |
| [SupplychainID](../../aspose.barcode.complexbarcode/mailmarkcodetext/supplychainid/) { get; set; } | Οι μέγιστες τιμές είναι 99 για τον γραμμωτό κώδικα C και 999999 για τον γραμμωτό κώδικα L. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmarkcodetext/versionid/) { get; set; } | Επί του παρόντος "1" – Για τον γραμμωτό κώδικα αλληλογραφίας (0 και 2 έως 9 και από Α έως Ω εφεδρικό για μελλοντική χρήση) |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmarkcodetext/getbarcodetype/)() | Λαμβάνει τύπο γραμμικού κώδικα. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmarkcodetext/getconstructedcodetext/)() | Δημιουργία κωδικοποιημένου κειμένου από δεδομένα Mailmark. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmarkcodetext/initfromstring/)(string) | Αρχικοποιεί δεδομένα Mailmark από κατασκευασμένο κώδικα κειμένου. |

### Δείτε επίσης

* interface [IComplexCodetext](../icomplexcodetext/)
* χώρος ονομάτων [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* συνέλευση [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->