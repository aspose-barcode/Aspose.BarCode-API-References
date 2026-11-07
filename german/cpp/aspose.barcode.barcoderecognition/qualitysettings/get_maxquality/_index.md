---
title: "Methode"
linktitle: "get_MaxQuality"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. MaxQuality Erkennungsqualitäts‑Voreinstellung. Diese Voreinstellung wurde entwickelt, um alle möglichen Barcodes zu erkennen, sogar fehlerhafte Barcodes in C++."
type: docs
weight: 400
url: /de/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_maxquality/
---
## QualitySettings::get_MaxQuality method


MaxQuality-Erkennungsqualitätsvorgabe. Diese Vorgabe wurde entwickelt, um alle möglichen Barcodes zu erkennen, sogar fehlerhafte Barcodes.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_MaxQuality()
```

## Hinweise


Dieses Beispiel zeigt, wie man den MaxQuality‑Modus verwendet
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


MaxQuality Erkennungsqualitäts‑Voreinstellung.
## Siehe auch

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
