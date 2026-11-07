---
title: "Methode"
linktitle: "get_HighQuality"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. HighQuality Erkennungsqualitäts‑Voreinstellung. Diese Voreinstellung wurde für Barcodes niedriger Qualität entwickelt. Ermöglicht das Erkennen stark beschädigter Barcodes in C++."
type: docs
weight: 300
url: /de/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highquality/
---
## QualitySettings::get_HighQuality method


HighQuality Erkennungsqualitätsvorgabe. Diese Vorgabe wurde für Strichcodes niedriger Qualität entwickelt. Ermöglicht das Erkennen stark beschädigter Strichcodes.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighQuality()
```

## Hinweise


Dieses Beispiel zeigt, wie man den HighQuality‑Modus verwendet
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighQuality Erkennungsqualitäts‑Voreinstellung.
## Siehe auch

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
