---
title: "μέθοδος"
linktitle: "get_HighPerformance"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " method. Προεπιλογή ποιότητας αναγνώρισης HighPerformance. Τα barcode υψηλής ποιότητας αναγνωρίζονται καλά σε αυτή τη λειτουργία σε C++."
type: docs
weight: 100
url: /el/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highperformance/
---
## QualitySettings::get_HighPerformance method


Προεπιλογή ποιότητας αναγνώρισης HighPerformance. Τα barcode υψηλής ποιότητας αναγνωρίζονται καλά σε αυτή τη λειτουργία.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighPerformance()
```

## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία HighPerformance
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Προεπιλογή ποιότητας αναγνώρισης HighPerformance.
## Δείτε επίσης

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
