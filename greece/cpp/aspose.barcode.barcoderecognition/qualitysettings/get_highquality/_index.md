---
title: "μέθοδος"
linktitle: "get_HighQuality"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " μέθοδος. Προεπιλογή ποιότητας αναγνώρισης HighQuality. Αυτή η προεπιλογή έχει αναπτυχθεί για γραμμωτούς κώδικες χαμηλής ποιότητας. Επιτρέπει την ανίχνευση πολύ κατεστραμμένων γραμμωτών κωδίκων σε C++."
type: docs
weight: 300
url: /el/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highquality/
---
## QualitySettings::get_HighQuality method


Προεπιλογή ποιότητας αναγνώρισης HighQuality. Αυτή η προεπιλογή έχει αναπτυχθεί για barcode χαμηλής ποιότητας. Επιτρέπει τον εντοπισμό πολύ κατεστραμμένων barcode.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighQuality()
```

## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία HighQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Προεπιλογή ποιότητας αναγνώρισης HighQuality.
## Δείτε επίσης

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
