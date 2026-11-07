---
title: "μέθοδος"
linktitle: "get_OnlyRequestedTypes"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " μέθοδος. Επιστρέφει μόνο τους τύπους barcode που έχουν οριστεί ρητά για αναγνώριση. Όταν είναι ενεργοποιημένη, τα αναγνωρισμένα barcodes άλλων συμβατών ή ισοδύναμων τύπων φιλτράρονται. Η προεπιλεγμένη τιμή είναι ψευδής σε C++."
type: docs
weight: 500
url: /el/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_onlyrequestedtypes/
---
## BarcodeSettings::get_OnlyRequestedTypes method


Επιστρέφει μόνο τους τύπους barcode που έχουν οριστεί ρητά για αναγνώριση. Όταν είναι ενεργό, τα αναγνωρισμένα barcode άλλων συμβατών ή ισοδύναμων τύπων φιλτράρονται. Η προεπιλεγμένη τιμή είναι false.

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_OnlyRequestedTypes() const
```

## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να περιορίσετε τα αποτελέσματα αναγνώρισης μόνο στους ζητούμενους τύπους barcode.
```cpp
[C#]
//δημιουργία barcode EAN13
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//αναγνώριση μόνο barcodes UPCA (χωρίς αποτελέσματα, επειδή η πηγή είναι EAN13)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//αναγνώριση συμβατών τύπων: EAN13, UPCA, ISSN, ISMN, ISBN (το EAN13 θα επιστραφεί ως ισοδύναμο UPCA)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```


Επιστρέφει μόνο τους τύπους barcode που έχουν οριστεί ρητά για αναγνώριση. Η προεπιλεγμένη τιμή είναι ψευδής.
## Δείτε επίσης

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
