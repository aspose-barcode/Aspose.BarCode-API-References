---
title: "metot"
linktitle: "get_MaxQuality"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " method. MaxQuality tanıma kalitesi ön ayarı. Bu ön ayar, C++'ta tüm olası barkodları, hatta hatalı barkodları bile tanımak için geliştirilmiştir."
type: docs
weight: 400
url: /tr/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_maxquality/
---
## QualitySettings::get_MaxQuality method


MaxQuality tanıma kalitesi ön ayarı. Bu ön ayar, tüm olası barkodları, hatta hatalı barkodları tanımak için geliştirilmiştir.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_MaxQuality()
```

## Açıklamalar


Bu örnek, MaxQuality modunun nasıl kullanılacağını gösterir
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


MaxQuality tanıma kalitesi ön ayarı.
## Ayrıca Bakınız

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
