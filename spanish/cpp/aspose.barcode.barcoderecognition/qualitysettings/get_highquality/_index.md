---
title: "método"
linktitle: "get_HighQuality"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Preajuste de calidad de reconocimiento HighQuality. Este preajuste está desarrollado para códigos de barras de baja calidad. Permite detectar códigos de barras altamente dañados en C++."
type: docs
weight: 300
url: /es/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highquality/
---
## QualitySettings::get_HighQuality method


Preset de calidad de reconocimiento HighQuality. Este preset está desarrollado para códigos de barras de baja calidad. Permite detectar códigos de barras altamente dañados.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighQuality()
```

## Observaciones


Este ejemplo muestra cómo usar el modo HighQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Preajuste de calidad de reconocimiento HighQuality.
## Ver también

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
