---
title: "method"
linktitle: "get_MaxQuality"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Preset di qualità di riconoscimento MaxQuality. Questo preset è sviluppato per riconoscere tutti i possibili codici a barre, anche i codici a barre errati in C++."
type: docs
weight: 400
url: /it/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_maxquality/
---
## QualitySettings::get_MaxQuality method


Preset di qualità di riconoscimento MaxQuality. Questo preset è stato sviluppato per riconoscere tutti i codici a barre possibili, anche i codici a barre errati.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_MaxQuality()
```

## Osservazioni


Questo esempio mostra come utilizzare la modalità MaxQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Preset di qualità di riconoscimento MaxQuality.
## Vedi anche

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
