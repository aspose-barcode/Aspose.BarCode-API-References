---
title: "metot"
linktitle: "get_HighPerformance"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " yöntem. HighPerformance tanıma kalite ön ayarı. Yüksek kaliteli barkodlar bu modda C++ içinde iyi tanınır."
type: docs
weight: 100
url: /tr/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highperformance/
---
## QualitySettings::get_HighPerformance method


HighPerformance tanıma kalite ön ayarı. Yüksek kaliteli barkodlar bu modda iyi tanınır.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighPerformance()
```

## Açıklamalar


Bu örnek, HighPerformance modunun nasıl kullanılacağını gösterir.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighPerformance tanıma kalite ön ayarı.
## Ayrıca Bakınız

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
