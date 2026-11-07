---
title: "Methode"
linktitle: "get_HighPerformance"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. HighPerformance-Erkennungsqualitätsvorgabe. Hochwertige Barcodes werden in diesem Modus in C++ gut erkannt."
type: docs
weight: 100
url: /de/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highperformance/
---
## QualitySettings::get_HighPerformance method


HighPerformance Erkennungsqualitätsvorgabe. Hochwertige Strichcodes werden in diesem Modus gut erkannt.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighPerformance()
```

## Hinweise


Dieses Beispiel zeigt, wie man den HighPerformance‑Modus verwendet
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighPerformance-Erkennungsqualitätsvorgabe.
## Siehe auch

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
