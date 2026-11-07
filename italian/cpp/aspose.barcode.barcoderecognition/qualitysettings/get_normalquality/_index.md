---
title: "method"
linktitle: "get_NormalQuality"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Preset di qualità di riconoscimento NormalQuality. Adatto per la maggior parte dei codici a barre in C++."
type: docs
weight: 200
url: /it/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_normalquality/
---
## QualitySettings::get_NormalQuality method


Preset di qualità di riconoscimento NormalQuality. Adatto per la maggior parte dei codici a barre

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_NormalQuality()
```

## Osservazioni


Questo esempio mostra come utilizzare la modalità NormalQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Preset di qualità di riconoscimento NormalQuality.
## Vedi anche

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
