---
title: "μέθοδος"
linktitle: "get_MaxQuality"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " μέθοδος. Προεπιλογή ποιότητας αναγνώρισης MaxQuality. Αυτή η προεπιλογή έχει αναπτυχθεί για την αναγνώριση όλων των πιθανών γραμμωτών κωδίκων, ακόμη και λανθασμένων γραμμωτών κωδίκων σε C++."
type: docs
weight: 400
url: /el/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_maxquality/
---
## QualitySettings::get_MaxQuality method


Προεπιλογή ποιότητας αναγνώρισης MaxQuality. Αυτή η προεπιλογή έχει αναπτυχθεί για την αναγνώριση όλων των πιθανών γραμμωτών κωδίκων, ακόμη και λανθασμένων γραμμωτών κωδίκων.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_MaxQuality()
```

## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία MaxQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Προεπιλογή ποιότητας αναγνώρισης MaxQuality.
## Δείτε επίσης

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
