---
title: "Απαρίθμηση AztecSymbolMode"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Generation.AztecSymbolMode enum. Καθορίζει τη λειτουργία συμβόλου Aztec"
type: docs
weight: 970
url: /el/net/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enumeration

Καθορίζει τη λειτουργία συμβόλου Aztec.

```csharp
public enum AztecSymbolMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Auto | `0` | Καθορίζει την αυτόματη επιλογή του καλύτερου συμβόλου (Compact ή Full-range) για Aztec. Αυτή είναι η προεπιλεγμένη τιμή. |
| Compact | `1` | Καθορίζει το Compact σύμβολο για Aztec. Το Compact σύμβολο Aztec επιτρέπει μόνο 1, 2, 3 ή 4 επίπεδα. |
| FullRange | `2` | Καθορίζει το Full-range σύμβολο για Aztec. Το Full-range σύμβολο Aztec επιτρέπει από 1 έως 32 επίπεδα. |
| Rune | `3` | Καθορίζει το Rune σύμβολο για Aztec. Τα Rune του Aztec είναι μια σειρά από μικρές αλλά διακριτές μηχανικά αναγνώσιμες σημάνσεις. Επιτρέπει μόνο αριθμητική τιμή από 0 έως 255. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να αλλάξετε τη λειτουργία Aztec Symbol και να αποθηκεύσετε μια εικόνα BarCode.

```csharp
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

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


