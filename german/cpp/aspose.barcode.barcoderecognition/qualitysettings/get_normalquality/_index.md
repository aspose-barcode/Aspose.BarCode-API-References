---
title: "Methode"
linktitle: "get_NormalQuality"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. NormalQuality Erkennungsqualitäts‑Voreinstellung. Geeignet für die meisten Barcodes in C++."
type: docs
weight: 200
url: /de/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_normalquality/
---
## QualitySettings::get_NormalQuality method


NormalQuality-Erkennungsqualitätsvorgabe. Geeignet für die meisten Barcodes.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_NormalQuality()
```

## Hinweise


Dieses Beispiel zeigt, wie man den NormalQuality‑Modus verwendet
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


NormalQuality Erkennungsqualitäts‑Voreinstellung.
## Siehe auch

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
