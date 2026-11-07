---
title: "enum"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Πώς να χρησιμοποιήσετε enum σε C++."
type: docs
weight: 3900
url: /el/cpp/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enum




```cpp
enum class InverseImageMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Auto | 0 | Απενεργοποιεί την πρόσθετη αναγνώριση των barcode σε αντίστροφες εικόνες για όλους τους τύπους barcode εκτός του κώδικα [QR](../../aspose.barcode.barcoderecognition.qr/) Code. |
| Απενεργοποιημένο | 1 | Απενεργοποιεί την πρόσθετη αναγνώριση των barcode σε αντίστροφες εικόνες. |
| Ενεργοποιημένο | 2 | Ενεργοποιεί την πρόσθετη αναγνώριση των barcode σε αντίστροφες εικόνες |

## Σχόλια


Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση barcode σε εικόνες με ανεστραμμένα χρώματα (φωτεινότητα).

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία InverseImage
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
