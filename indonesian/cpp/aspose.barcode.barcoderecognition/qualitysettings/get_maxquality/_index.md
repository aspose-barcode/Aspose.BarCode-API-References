---
title: "metode"
linktitle: "get_MaxQuality"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " metode. Preset kualitas pengenalan MaxQuality. Preset ini dikembangkan untuk mengenali semua barcode yang mungkin, bahkan barcode yang salah dalam C++."
type: docs
weight: 400
url: /id/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_maxquality/
---
## QualitySettings::get_MaxQuality method


Preset kualitas pengenalan MaxQuality. Preset ini dikembangkan untuk mengenali semua barcode yang mungkin, bahkan barcode yang tidak benar.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_MaxQuality()
```

## Catatan


Contoh ini menunjukkan cara menggunakan mode MaxQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Preset kualitas pengenalan MaxQuality.
## Lihat Juga

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
