---
title: "BarcodeSettings.OnlyRequestedTypes"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "BarcodeSettings ιδιότητα. Επιστρέφει μόνο τους τύπους barcode που έχουν καθοριστεί ρητά για αναγνώριση. Όταν είναι ενεργοποιημένο, τα αναγνωρισμένα barcode άλλων συμβατών ή ισοδύναμων τύπων φιλτράρονται. Η προεπιλεγμένη τιμή είναι false."
type: docs
weight: 50
url: /el/net/aspose.barcode.barcoderecognition/barcodesettings/onlyrequestedtypes/
---
## BarcodeSettings.OnlyRequestedTypes property

Επιστρέφει μόνο τους τύπους barcode που έχουν καθοριστεί ρητά για αναγνώριση. Όταν είναι ενεργό, τα αναγνωρισμένα barcode άλλων συμβατών ή ισοδύναμων τύπων φιλτράρονται. Η προεπιλεγμένη τιμή είναι false.

```csharp
public bool OnlyRequestedTypes { get; set; }
```

### Property Value

Επιστρέφει μόνο τύπους γραμμωτού κώδικα που έχουν καθοριστεί ρητά για αναγνώριση. Η προεπιλεγμένη τιμή είναι ψευδής.

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να περιορίσετε τα αποτελέσματα αναγνώρισης μόνο στους ζητούμενους τύπους γραμμωτού κώδικα.

```csharp
[C#]
//Δημιουργήστε γραμμωτό κώδικα EAN13.
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//Αναγνωρίστε μόνο γραμμωτούς κώδικες UPCA (χωρίς αποτελέσματα, επειδή η πηγή είναι EAN13).
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//Αναγνωρίστε συμβατούς τύπους: EAN13, UPCA, ISSN, ISMN, ISBN (το EAN13 θα επιστραφεί ως ισοδύναμο του UPCA).
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```

### Δείτε επίσης

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


