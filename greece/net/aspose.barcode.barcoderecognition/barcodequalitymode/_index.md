---
title: "Απαρίθμηση BarcodeQualityMode"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.BarCodeRecognition.BarcodeQualityMode enum. Λειτουργία που επιτρέπει στις μεθόδους να αναγνωρίζουν στοιχεία γραμμωτού κώδικα με την επιλεγμένη ποιότητα. Το στοιχείο γραμμωτού κώδικα χαμηλότερης ποιότητας απαιτεί πιο δύσκολες μεθόδους, κάτι που επιβραδύνει την αναγνώριση."
type: docs
weight: 110
url: /el/net/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enumeration

Λειτουργία που ενεργοποιεί μεθόδους για την αναγνώριση στοιχείων barcode με την επιλεγμένη ποιότητα. Ένα στοιχείο barcode χαμηλότερης ποιότητας απαιτεί πιο απαιτητικές μεθόδους, κάτι που επιβραδύνει την αναγνώριση.

```csharp
public enum BarcodeQualityMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| High | `0` | Ενεργοποιεί τις μεθόδους αναγνώρισης για γραμμωτούς κώδικες υψηλής ποιότητας. |
| Normal | `1` | Ενεργοποιεί τις μεθόδους αναγνώρισης για γραμμωτούς κώδικες κοινής (κανονικής) ποιότητας. |
| Low | `2` | Ενεργοποιεί τις μεθόδους αναγνώρισης για γραμμωτούς κώδικες χαμηλής ποιότητας. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία BarcodeQuality.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Δείτε επίσης

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


