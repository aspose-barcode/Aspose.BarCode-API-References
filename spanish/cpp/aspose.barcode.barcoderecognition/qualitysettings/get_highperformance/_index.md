---
title: "método"
linktitle: "get_HighPerformance"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Configuración preestablecida de calidad de reconocimiento HighPerformance. Los códigos de barras de alta calidad se reconocen bien en este modo en C++."
type: docs
weight: 100
url: /es/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highperformance/
---
## QualitySettings::get_HighPerformance method


Preset de calidad de reconocimiento HighPerformance. Los códigos de barras de alta calidad se reconocen bien en este modo.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighPerformance()
```

## Observaciones


Este ejemplo muestra cómo usar el modo HighPerformance
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Configuración preestablecida de calidad de reconocimiento HighPerformance.
## Ver también

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
