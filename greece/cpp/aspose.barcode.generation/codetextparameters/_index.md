---
title: "Aspose::BarCode::Generation::CodetextParameters class"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::Generation::CodetextParameters class. Παράμετροι κειμένου κώδικα σε C++."
type: docs
weight: 1500
url: /el/cpp/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class


Παράμετροι Codetext.

```cpp
class CodetextParameters : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_Alignment](./get_alignment/)() const | Λαμβάνει την ευθυγράμμιση του κειμένου κώδικα. Προεπιλεγμένη τιμή: [StringAlignment.Center](../textalignment/). |
| [get_Color](./get_color/)() const | Καθορίστε το χρώμα εμφάνισης του CodeText. Προεπιλεγμένη τιμή: Color.Black. |
| [get_Font](./get_font/)() const | Καθορίστε τη γραμματοσειρά εμφάνισης του CodeText. Προεπιλεγμένη τιμή: Arial 5pt regular. Αγνοείται εάν το FontMode έχει οριστεί σε [FontMode.Auto](../aztecencodemode/). |
| [get_FontMode](./get_fontmode/)() const | Καθορίστε το FontMode. Εάν το FontMode οριστεί σε Auto, το μέγεθος γραμματοσειράς θα υπολογιστεί αυτόματα βάσει της τιμής xDimension. Συνιστάται η χρήση του [FontMode.Auto](../aztecencodemode/) ειδικά σε [AutoSizeMode.Nearest](../autosizemode/) ή [AutoSizeMode.Interpolation](../autosizemode/). Προεπιλεγμένη τιμή: [FontMode.Auto](../aztecencodemode/). |
| [get_Location](./get_location/)() const | Καθορίστε τη θέση εμφάνισης του CodeText, ορίστε σε [CodeLocation.None](../codelocation/) για απόκρυψη του CodeText. Προεπιλεγμένη τιμή: [CodeLocation.Below](../codelocation/) για 1D barcode και [CodeLocation.None](../codelocation/) για 2D barcode. |
| [get_NoWrap](./get_nowrap/)() const | Καθορίστε τις αναδιπλώσεις λέξεων (διακοπές γραμμής) μέσα στο κείμενο. Προεπιλεγμένη τιμή: false. |
| [get_Space](./get_space/)() const | Διάστημα μεταξύ του CodeText και του [BarCode](../../aspose.barcode/) σε τιμή [Unit ](../unit/). Προεπιλεγμένη τιμή: 2pt. Αγνοείται για EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [get_TwoDDisplayText](./get_twoddisplaytext/)() const | Κείμενο που θα εμφανίζεται αντί για codetext σε 2D barcode. Χρησιμοποιείται για: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode. |
| [set_Alignment](./set_alignment/)(TextAlignment) | Ορίζει την ευθυγράμμιση του κειμένου κώδικα. Προεπιλεγμένη τιμή: [StringAlignment.Center](../textalignment/). |
| [set_Color](./set_color/)(System::Drawing::Color) | Καθορίστε το χρώμα εμφάνισης του CodeText. Προεπιλεγμένη τιμή: Color.Black. |
| [set_FontMode](./set_fontmode/)(Aspose::BarCode::Generation::FontMode) | Καθορίστε το FontMode. Εάν το FontMode οριστεί σε Auto, το μέγεθος γραμματοσειράς θα υπολογιστεί αυτόματα βάσει της τιμής xDimension. Συνιστάται η χρήση του [FontMode.Auto](../aztecencodemode/) ειδικά σε [AutoSizeMode.Nearest](../autosizemode/) ή [AutoSizeMode.Interpolation](../autosizemode/). Προεπιλεγμένη τιμή: [FontMode.Auto](../aztecencodemode/). |
| [set_Location](./set_location/)(CodeLocation) | Καθορίστε τη θέση εμφάνισης του CodeText, ορίστε σε [CodeLocation.None](../codelocation/) για απόκρυψη του CodeText. Προεπιλεγμένη τιμή: [CodeLocation.Below](../codelocation/) για 1D barcode και [CodeLocation.None](../codelocation/) για 2D barcode. |
| [set_NoWrap](./set_nowrap/)(bool) | Καθορίστε τις αναδιπλώσεις λέξεων (διακοπές γραμμής) μέσα στο κείμενο. Προεπιλεγμένη τιμή: false. |
| [set_Space](./set_space/)(System::SharedPtr\<Unit\>) | Διάστημα μεταξύ του CodeText και του [BarCode](../../aspose.barcode/) σε τιμή [Unit ](../unit/). Προεπιλεγμένη τιμή: 2pt. Αγνοείται για EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [set_TwoDDisplayText](./set_twoddisplaytext/)(System::String) | Κείμενο που θα εμφανίζεται αντί για codetext σε 2D barcode. Χρησιμοποιείται για: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode. |
| [ToString](./tostring/)() const override | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [CodetextParameters](./). |
## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
