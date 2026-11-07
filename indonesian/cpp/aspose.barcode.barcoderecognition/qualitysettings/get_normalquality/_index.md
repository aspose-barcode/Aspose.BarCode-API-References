---
title: "metode"
linktitle: "get_NormalQuality"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " metode. Preset kualitas pengenalan NormalQuality. Cocok untuk sebagian besar barcode dalam C++."
type: docs
weight: 200
url: /id/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_normalquality/
---
## QualitySettings::get_NormalQuality method


Preset kualitas pengenalan NormalQuality. Cocok untuk sebagian besar barcode.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_NormalQuality()
```

## Catatan


Contoh ini menunjukkan cara menggunakan mode NormalQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Preset kualitas pengenalan NormalQuality.
## Lihat Juga

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
