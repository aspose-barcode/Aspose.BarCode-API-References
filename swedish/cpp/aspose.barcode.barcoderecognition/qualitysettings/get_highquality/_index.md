---
title: "metod"
linktitle: "get_HighQuality"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. HighQuality igenkänningskvalitet förinställning. Denna förinställning är utvecklad för streckkoder med låg kvalitet. Gör det möjligt att upptäcka kraftigt skadade streckkoder i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highquality/
---
## QualitySettings::get_HighQuality method


HighQuality‑förinställning för igenkänningskvalitet. Denna förinställning är utvecklad för lågkvalitativa streckkoder. Gör det möjligt att upptäcka kraftigt skadade streckkoder.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighQuality()
```

## Anmärkningar


Detta exempel visar hur man använder HighQuality-läget
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighQuality igenkänningskvalitet förinställning.
## Se även

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
