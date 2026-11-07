---
title: "metode"
linktitle: "get_HighQuality"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " metode. Preset kualitas pengenalan HighQuality. Preset ini dikembangkan untuk barcode kualitas rendah. Memungkinkan mendeteksi barcode yang sangat rusak dalam C++."
type: docs
weight: 300
url: /id/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highquality/
---
## QualitySettings::get_HighQuality method


Preset kualitas pengenalan HighQuality. Preset ini dikembangkan untuk kode batang berkualitas rendah. Mengizinkan deteksi kode batang yang sangat rusak.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighQuality()
```

## Catatan


Contoh ini menunjukkan cara menggunakan mode HighQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Preset kualitas pengenalan HighQuality.
## Lihat Juga

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
