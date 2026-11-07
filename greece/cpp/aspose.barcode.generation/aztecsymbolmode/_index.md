---
title: "enum"
linktitle: "AztecSymbolMode"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "enum. Καθορίζει τη λειτουργία συμβόλου Aztec σε C++."
type: docs
weight: 5400
url: /el/cpp/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enum


Καθορίζει τη λειτουργία συμβόλου Aztec.

```cpp
enum class AztecSymbolMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Αυτόματο | 0 | Καθορίζει την αυτόματη επιλογή του καλύτερου συμβόλου (Compact ή Full-range) για Aztec. Αυτή είναι η προεπιλεγμένη τιμή. |
| Compact | 1 | Καθορίζει το σύμβολο Compact για Aztec. Το σύμβολο Aztec Compact επιτρέπει μόνο 1, 2, 3 ή 4 επίπεδα. |
| FullRange | 2 | Καθορίζει το σύμβολο Full-range για Aztec. Το σύμβολο Aztec Full-range επιτρέπει από 1 έως 32 επίπεδα. |
| Rune | 3 | Καθορίζει το σύμβολο Rune για Aztec. Τα Aztec Runes είναι μια σειρά από μικρά αλλά διακριτά μηχανικά αναγνώσιμα σημάδια. Επιτρέπει μόνο αριθμητική τιμή από 0 έως 255. |

## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να αλλάξετε τη λειτουργία Aztec Symbol και να αποθηκεύσετε μια εικόνα [BarCode](../../aspose.barcode/).
```cpp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.CodeText = "125";
    generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune;
    generator.Save("test.png");
}
    [VB.NET]
    Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec)
        generator.CodeText = "125"
        generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune
        generator.Save("test.png")
    End Using
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
