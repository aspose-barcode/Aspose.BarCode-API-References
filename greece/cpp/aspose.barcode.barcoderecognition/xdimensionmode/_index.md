---
title: "enum"
linktitle: "XDimensionMode"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Πώς να χρησιμοποιήσετε enum σε C++."
type: docs
weight: 4000
url: /el/cpp/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enum




```cpp
enum class XDimensionMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Αυτόματο | 0 | Η τιμή του XDimension ανιχνεύεται από AI (SVM). Αυτή τη στιγμή είναι η ίδια με το Normal |
| Small | 1 | Ανιχνεύει barcode με μικρό XDimension σε 1 pixel ή περισσότερο με ποιότητα από BarcodeQuality |
| Κανονική | 2 | Ανιχνεύει barcode με κλασικό XDimension σε 2 pixels ή περισσότερο με ποιότητα από BarcodeQuality ή barcode υψηλής ποιότητας. |
| Large | 3 | Ανιχνεύει barcode με μεγάλο XDimension με ποιότητα από BarcodeQuality που καταγράφηκε με κάμερες υψηλής ανάλυσης. |
| UseMinimalXDimension | 4 | Ανιχνεύει γραμμικούς κώδικες από το μέγεθος που ορίζεται στο MinimalXDimension με ποιότητα από το BarcodeQuality |

## Σχόλια


[Recognition](../../aspose.barcode.barcoderecognition.recognition/) mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. 

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία XDimension
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
