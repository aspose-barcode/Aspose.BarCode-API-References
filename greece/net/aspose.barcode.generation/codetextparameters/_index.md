---
title: "Κλάση CodetextParameters"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Generation.CodetextParameters κλάση. Παράμετροι κώδικα κειμένου"
type: docs
weight: 1160
url: /el/net/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class

Παράμετροι κειμένου κώδικα.

```csharp
public class CodetextParameters
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Alignment](../../aspose.barcode.generation/codetextparameters/alignment/) { get; set; } | Αποκτά ή ορίζει την ευθυγράμμιση του κειμένου κώδικα. Προεπιλεγμένη τιμή: StringAlignment.Center. |
| [Color](../../aspose.barcode.generation/codetextparameters/color/) { get; set; } | Καθορίστε το χρώμα εμφάνισης του CodeText. Προεπιλεγμένη τιμή: Color.Black. |
| [Font](../../aspose.barcode.generation/codetextparameters/font/) { get; } | Καθορίστε τη γραμματοσειρά εμφάνισης του CodeText. Προεπιλεγμένη τιμή: Arial 5pt regular. Αγνοείται εάν το FontMode οριστεί σε FontMode.Auto. |
| [FontMode](../../aspose.barcode.generation/codetextparameters/fontmode/) { get; set; } | Καθορίστε το FontMode. Εάν το FontMode οριστεί σε Auto, το μέγεθος γραμματοσειράς θα υπολογιστεί αυτόματα με βάση την τιμή xDimension. Συνιστάται η χρήση του FontMode.Auto, ειδικά στο AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. Προεπιλεγμένη τιμή: FontMode.Auto. |
| [Location](../../aspose.barcode.generation/codetextparameters/location/) { get; set; } | Καθορίστε τη θέση εμφάνισης του CodeText, ορίστε το σε CodeLocation.None για απόκρυψη του CodeText. Προεπιλεγμένη τιμή: CodeLocation.Below για 1D barcode και CodeLocation.None για 2D barcode. |
| [NoWrap](../../aspose.barcode.generation/codetextparameters/nowrap/) { get; set; } | Καθορίστε τις αναδιπλώσεις λέξεων (αλλαγές γραμμής) μέσα στο κείμενο. Προεπιλεγμένη τιμή: false. |
| [Space](../../aspose.barcode.generation/codetextparameters/space/) { get; set; } | Διάστημα μεταξύ του CodeText και του BarCode στην τιμή [`Unit`](../unit/). Προεπιλεγμένη τιμή: 2pt. Αγνοείται για EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [TwoDDisplayText](../../aspose.barcode.generation/codetextparameters/twoddisplaytext/) { get; set; } | Κείμενο που θα εμφανίζεται αντί για codetext σε 2D barcode. Χρησιμοποιείται για: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/codetextparameters/tostring/)() | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του `CodetextParameters`. |

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


