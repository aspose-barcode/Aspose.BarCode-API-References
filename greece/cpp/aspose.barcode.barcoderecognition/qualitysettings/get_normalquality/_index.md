---
title: "μέθοδος"
linktitle: "get_NormalQuality"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " μέθοδος. Προεπιλογή ποιότητας αναγνώρισης NormalQuality. Κατάλληλη για τα περισσότερα barcode στο C++."
type: docs
weight: 200
url: /el/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_normalquality/
---
## QualitySettings::get_NormalQuality method


Προεπιλογή ποιότητας αναγνώρισης NormalQuality. Κατάλληλη για τους περισσότερους γραμμωτούς κώδικες.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_NormalQuality()
```

## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία NormalQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Προεπιλογή ποιότητας αναγνώρισης NormalQuality.
## Δείτε επίσης

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
