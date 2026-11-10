---
title: "Κλάση Mailmark2DCodetext"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.ComplexBarcode.Mailmark2DCodetext κλάση. Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα Royal Mail 2D Mailmark."
type: docs
weight: 650
url: /el/net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα Royal Mail 2D Mailmark.

```csharp
public sealed class Mailmark2DCodetext : IComplexCodetext
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Mailmark2DCodetext](mailmark2dcodetext/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmark2dcodetext/class/) { get; set; } | Αναγνωρίζει την κλάση του αντικειμένου. |
| [CustomerContent](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontent/) { get; set; } | Προαιρετικός χώρος για χρήση από τον πελάτη. |
| [CustomerContentEncodeMode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontentencodemode/) { get; set; } | Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: EncodeMode.C40. |
| [DataMatrixType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/datamatrixtype/) { get; set; } | Ο τύπος 2D Mailmark ορίζει το μέγεθος του barcode Data Matrix. |
| [DestinationPostCodeAndDPS](../../aspose.barcode.complexbarcode/mailmark2dcodetext/destinationpostcodeanddps/) { get; set; } | Περιέχει τον Ταχυδρομικό Κώδικα της Διεύθυνσης Παράδοσης με DPS. Εάν είναι ενδοχώρα, ο Ταχυδρομικός Κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων. Περιοχή (1 ή 2 χαρακτήρες) Περιφέρεια (1 ή 2 χαρακτήρες) Τομέας (1 χαρακτήρας) Μονάδα (2 χαρακτήρες) DPS (2 χαρακτήρες). Ο Ταχυδρομικός Κώδικας και το DPS πρέπει να συμμορφώνονται με έγκυρη μορφή PAF®. |
| [InformationTypeID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/informationtypeid/) { get; set; } | Αναγνωρίζει το payload του barcode Royal Mail Mailmark για κάθε τύπο προϊόντος. |
| [ItemID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/itemid/) { get; set; } | Αναγνωρίζει το μοναδικό στοιχείο μέσα στο Supply Chain ID. Κάθε barcode Mailmark πρέπει να περιέχει ένα ID ώστε να μπορεί να ταυτοποιηθεί μοναδικά για τουλάχιστον 90 ημέρες. Μέγιστη τιμή: 99999999. |
| [ReturnToSenderPostCode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/returntosenderpostcode/) { get; set; } | Περιέχει τον Ταχυδρομικό Κώδικα Επιστροφής στον Αποστολέα αλλά χωρίς DPS. Ο Κώδικας (χωρίς DPS) πρέπει να συμμορφώνεται με μορφή PAF®. |
| [RTSFlag](../../aspose.barcode.complexbarcode/mailmark2dcodetext/rtsflag/) { get; set; } | Σημαία που υποδεικνύει ποιο επίπεδο υπηρεσίας Επιστροφής στον Αποστολέα ζητείται. |
| [SupplyChainID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/supplychainid/) { get; set; } | Αναγνωρίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. Μέγιστη τιμή: 9999999. |
| [UPUCountryID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/upucountryid/) { get; set; } | Αναγνωρίζει το UPU Country ID. Μέγιστο μήκος: 4 χαρακτήρες. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/versionid/) { get; set; } | Αναγνωρίζει την έκδοση του barcode όπως σχετίζεται με κάθε Information Type ID. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getbarcodetype/)() | Λαμβάνει τον τύπο του barcode. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getconstructedcodetext/)() | Δημιουργήστε κείμενο κώδικα από τα δεδομένα Mailmark. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmark2dcodetext/initfromstring/)(string) | Αρχικοποιεί τα δεδομένα Mailmark από το δημιουργημένο κείμενο κώδικα. |

### Δείτε επίσης

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


