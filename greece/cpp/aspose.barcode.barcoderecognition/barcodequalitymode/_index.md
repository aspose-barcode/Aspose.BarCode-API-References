---
title: "enum"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Πώς να χρησιμοποιήσετε enum σε C++."
type: docs
weight: 3600
url: /el/cpp/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enum




```cpp
enum class BarcodeQualityMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Υψηλή | 0 | Ενεργοποιεί τις μεθόδους αναγνώρισης για barcodes υψηλής ποιότητας. |
| Κανονική | 1 | Ενεργοποιεί τις μεθόδους αναγνώρισης για barcodes κοινής (Κανονικής) ποιότητας. |
| Χαμηλή | 2 | Ενεργοποιεί τις μεθόδους αναγνώρισης για barcodes χαμηλής ποιότητας. |

## Σχόλια


Λειτουργία που ενεργοποιεί μεθόδους για την αναγνώριση στοιχείων barcode με την επιλεγμένη ποιότητα. Στοιχείο barcode χαμηλότερης ποιότητας απαιτεί πιο απαιτητικές μεθόδους, κάτι που επιβραδύνει την αναγνώριση.

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία BarcodeQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
