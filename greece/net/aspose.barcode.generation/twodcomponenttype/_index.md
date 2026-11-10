---
title: "Απαρίθμηση TwoDComponentType"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Απαρίθμηση Aspose.BarCode.Generation.TwoDComponentType. Τύπος 2D στοιχείου"
type: docs
weight: 1730
url: /el/net/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enumeration

Τύπος στοιχείου 2D

```csharp
public enum TwoDComponentType
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Auto | `0` | Αυτόματη επιλογή τύπου 2D στοιχείου |
| CC_A | `1` | Τύπος CC-A 2D στοιχείου. Είναι μια δομική παραλλαγή του MicroPDF417 |
| CC_B | `2` | Τύπος CC-B 2D στοιχείου. Είναι ένα σύμβολο MicroPDF417. |
| CC_C | `3` | Τύπος CC-C 2D στοιχείου. Είναι ένα σύμβολο PDF417. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα GS1 Composite Bar. Σημειώστε ότι το κείμενο κώδικα 1D και το κείμενο κώδικα 2D χωρίζονται με το σύμβολο '/'

```csharp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
{
    generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
    generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
    
    // Αναλογία διαστάσεων του 2D στοιχείου
    generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
        
    // Διάσταση X των στοιχείων 1D και 2D
    generator.Parameters.Barcode.XDimension.Pixels = 3;
        
    // Ύψος του στοιχείου 1D
    generator.Parameters.Barcode.BarHeight.Pixels = 100;
    
    generator.Save("test.png");
}
```

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


