---
title: "method"
linktitle: "get_HighPerformance"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Preset di qualità di riconoscimento HighPerformance. I codici a barre di alta qualità sono riconosciuti correttamente in questa modalità in C++."
type: docs
weight: 100
url: /it/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highperformance/
---
## QualitySettings::get_HighPerformance method


Preset di qualità di riconoscimento HighPerformance. I codici a barre di alta qualità sono riconosciuti correttamente in questa modalità.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighPerformance()
```

## Osservazioni


Questo esempio mostra come utilizzare la modalità HighPerformance
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Preset di qualità di riconoscimento HighPerformance.
## Vedi anche

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
