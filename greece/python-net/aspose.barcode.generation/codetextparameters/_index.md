---
title: "CodetextParameters"
second_title: "Aspose.BarCode για Python μέσω .NET API Reference"
description: 
type: docs
url: /el/python-net/aspose.barcode.generation/codetextparameters/
---

## CodetextParameters class

Παράμετροι Codetext.

Ο τύπος CodetextParameters εκθέτει τα ακόλουθα μέλη:
## Ιδιότητες
| Όνομα | Περιγραφή |
| :- | :- |
| two_d_display_text | Κείμενο που θα εμφανίζεται αντί για κώδικα κειμένου σε 2D barcode.<br/>            Χρησιμοποιείται για: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| font_mode | Καθορίστε το FontMode. Εάν το FontMode οριστεί σε Auto, το μέγεθος γραμματοσειράς θα υπολογιστεί αυτόματα βάσει της τιμής xDimension.<br/>            Συνιστάται η χρήση του FontMode.Auto ειδικά σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation.<br/>            Προεπιλεγμένη τιμή: FontMode.Auto. |
| font | Καθορίστε τη γραμματοσειρά εμφάνισης του CodeText.<br/>            Προεπιλεγμένη τιμή: Arial 5pt regular.<br/>            Αγνοείται εάν το FontMode οριστεί σε FontMode.Auto. |
| space | Διάστημα μεταξύ του CodeText και του BarCode σε τιμή [Unit](/barcode/python-net/aspose.barcode.generation/unit/).<br/>            Προεπιλεγμένη τιμή: 2pt.<br/>            Αγνοείται για EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| alignment | Λαμβάνει ή ορίζει την ευθυγράμμιση του κειμένου κώδικα.<br/>            Προεπιλεγμένη τιμή: StringAlignment.Center. |
| color | Καθορίστε το χρώμα του εμφανιζόμενου CodeText.<br/>            Προεπιλεγμένη τιμή: Color.Black. |
| location | Καθορίστε τη θέση του εμφανιζόμενου CodeText, ορίστε σε CodeLocation.None για απόκρυψη του CodeText.<br/>            Προεπιλεγμένη τιμή: CodeLocation.Below για 1D barcode και CodeLocation.None για 2D barcode. |
| no_wrap | Καθορίστε την αναδίπλωση λέξεων (αλλαγές γραμμής) μέσα στο κείμενο.<br/>            Προεπιλεγμένη τιμή: false. |

### Δείτε επίσης

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

