---
title: "metod"
linktitle: "get_NormalQuality"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. NormalQuality igenkänningskvalitet förinställning. Lämplig för de flesta streckkoder i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_normalquality/
---
## QualitySettings::get_NormalQuality method


NormalQuality igenkänningskvalitetspreset. Lämplig för de flesta streckkoder.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_NormalQuality()
```

## Anmärkningar


Detta exempel visar hur man använder NormalQuality-läget
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


NormalQuality igenkänningskvalitet förinställning.
## Se även

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
