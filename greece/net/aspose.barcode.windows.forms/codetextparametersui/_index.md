---
title: "Κλάση CodetextParametersUI"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Windows.Forms.CodetextParametersUI κλάση. Παράμετροι Codetext"
type: docs
weight: 1820
url: /el/net/aspose.barcode.windows.forms/codetextparametersui/
---
## CodetextParametersUI class

Παράμετροι κειμένου κώδικα.

```csharp
public class CodetextParametersUI
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Alignment](../../aspose.barcode.windows.forms/codetextparametersui/alignment/) { get; set; } | Αποκτά ή ορίζει την ευθυγράμμιση του κειμένου κώδικα. Προεπιλεγμένη τιμή: StringAlignment.Center. |
| [Color](../../aspose.barcode.windows.forms/codetextparametersui/color/) { get; set; } | Καθορίστε το χρώμα εμφάνισης του CodeText. Προεπιλεγμένη τιμή: Color.Black. |
| [Font](../../aspose.barcode.windows.forms/codetextparametersui/font/) { get; set; } | Καθορίστε τη γραμματοσειρά εμφάνισης του CodeText. Προεπιλεγμένη τιμή: Arial 5pt regular. Αγνοείται εάν το FontMode οριστεί σε FontMode.Auto. |
| [FontMode](../../aspose.barcode.windows.forms/codetextparametersui/fontmode/) { get; set; } | Καθορίστε το FontMode. Εάν το FontMode οριστεί σε Auto, το μέγεθος γραμματοσειράς θα υπολογιστεί αυτόματα με βάση την τιμή xDimension. Συνιστάται η χρήση του FontMode.Auto, ειδικά στο AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. Προεπιλεγμένη τιμή: FontMode.Auto. |
| [Location](../../aspose.barcode.windows.forms/codetextparametersui/location/) { get; set; } | Καθορίστε τη θέση εμφάνισης του CodeText, ορίστε το σε CodeLocation.None για απόκρυψη του CodeText. Προεπιλεγμένη τιμή: CodeLocation.Below για 1D barcode και CodeLocation.None για 2D barcode. |
| [Space](../../aspose.barcode.windows.forms/codetextparametersui/space/) { get; } | Διάστημα μεταξύ του CodeText και του BarCode σε τιμή [`Unit`](../../aspose.barcode.generation/unit/). Προεπιλεγμένη τιμή: 2pt. Αγνοείται για EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [TwoDDisplayText](../../aspose.barcode.windows.forms/codetextparametersui/twoddisplaytext/) { get; set; } | Κείμενο που θα εμφανίζεται αντί για codetext σε 2D barcode. Χρησιμοποιείται για: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/codetextparametersui/tostring/)() | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [`CodetextParameters`](../../aspose.barcode.generation/codetextparameters/). |

### Δείτε επίσης

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


