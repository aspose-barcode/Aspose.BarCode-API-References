---
title: "Aspose::BarCode::Generation::Unit κλάση"
linktitle: "Unit"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::Generation::Unit κλάση. Καθορίζει την τιμή μεγέθους σε διαφορετικές μονάδες (Pixel, Inches, κλ.) σε C++."
type: docs
weight: 5000
url: /el/cpp/aspose.barcode.generation/unit/
---
## Unit class


Καθορίζει την τιμή μεγέθους σε διαφορετικές μονάδες (Pixel, ίντσες, κ.λπ.).

```cpp
class Unit : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Καθορίζει εάν αυτή η παρουσία και ένα καθορισμένο αντικείμενο, το οποίο πρέπει επίσης να είναι ένα αντικείμενο [Unit](./), έχουν την ίδια τιμή. |
| [get_Document](./get_document/)() | Λαμβάνει την τιμή μεγέθους σε μονάδες εγγράφου. |
| [get_Inches](./get_inches/)() | Λαμβάνει την τιμή μεγέθους σε ίντσες. |
| [get_Millimeters](./get_millimeters/)() | Λαμβάνει την τιμή μεγέθους σε χιλιοστά. |
| [get_Pixels](./get_pixels/)() | Λαμβάνει την τιμή μεγέθους σε pixel. |
| [get_Point](./get_point/)() | Λαμβάνει την τιμή μεγέθους σε point. |
| [get_Resolution](./get_resolution/)() const | Ανάλυση |
| [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό hash για αυτό το αντικείμενο. |
| [set_Document](./set_document/)(float) | Ορίζει την τιμή μεγέθους σε μονάδες εγγράφου. |
| [set_Inches](./set_inches/)(float) | Ορίζει την τιμή μεγέθους σε ίντσες. |
| [set_Millimeters](./set_millimeters/)(float) | Ορίζει την τιμή μεγέθους σε χιλιοστά. |
| [set_Pixels](./set_pixels/)(float) | Ορίζει την τιμή μεγέθους σε pixel. |
| [set_Point](./set_point/)(float) | Ορίζει την τιμή μεγέθους σε point. |
| [ToString](./tostring/)() const override | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [Unit](./). |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα [BarCode](../../aspose.barcode/).
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
