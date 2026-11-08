---
title: "metot"
linktitle: "get_NormalQuality"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " method. NormalQuality tanıma kalite ön ayarı. C++'ta çoğu barkod için uygundur."
type: docs
weight: 200
url: /tr/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_normalquality/
---
## QualitySettings::get_NormalQuality method


NormalQuality tanıma kalitesi ön ayarı. Çoğu barkod için uygundur.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_NormalQuality()
```

## Açıklamalar


Bu örnek NormalQuality modunun nasıl kullanılacağını gösterir.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


NormalQuality tanıma kalitesi ön ayarı.
## Ayrıca Bakınız

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
