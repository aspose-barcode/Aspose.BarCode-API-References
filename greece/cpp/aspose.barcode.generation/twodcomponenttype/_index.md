---
title: "enum"
linktitle: "TwoDComponentType"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " enum. Τύπος 2D στοιχείου σε C++."
type: docs
weight: 8700
url: /el/cpp/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enum


Τύπος στοιχείου 2D

```cpp
enum class TwoDComponentType
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Αυτόματο | 0 | Αυτόματη επιλογή τύπου 2D στοιχείου |
| CC_A | 1 | CC-A τύπος 2D στοιχείου. Είναι μια δομική παραλλαγή του MicroPDF417 |
| CC_B | 2 | CC-B τύπος 2D στοιχείου. Είναι ένα σύμβολο MicroPDF417. |
| CC_C | 3 | CC-C τύπος 2D στοιχείου. Είναι ένα σύμβολο PDF417. |

## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα GS1 Composite Bar. Σημειώστε ότι το κείμενο κώδικα 1D και το κείμενο κώδικα 2D χωρίζονται με το σύμβολο '/'
```cpp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
    using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
    {
    generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
    generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

    // Αναλογία διαστάσεων 2D στοιχείου
    generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

    // Διάσταση X των 1D και 2D στοιχείων
    generator.Parameters.Barcode.XDimension.Pixels = 3;

    // Ύψος 1D στοιχείου
    generator.Parameters.Barcode.BarHeight.Pixels = 100;

    generator.Save("test.png");
}
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
