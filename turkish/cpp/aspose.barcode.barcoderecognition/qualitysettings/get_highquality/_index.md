---
title: "metot"
linktitle: "get_HighQuality"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " method. HighQuality tanıma kalitesi ön ayarı. Bu ön ayar düşük kalite barkodlar için geliştirilmiştir. C++'ta yüksek derecede hasar görmüş barkodları tespit etmeyi sağlar."
type: docs
weight: 300
url: /tr/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highquality/
---
## QualitySettings::get_HighQuality method


HighQuality tanıma kalite ön ayarı. Bu ön ayar düşük kaliteli barkodlar için geliştirilmiştir. Aşırı hasarlı barkodları tespit etmeye olanak tanır.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighQuality()
```

## Açıklamalar


Bu örnek, HighQuality modunun nasıl kullanılacağını gösterir
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighQuality tanıma kalitesi ön ayarı.
## Ayrıca Bakınız

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
