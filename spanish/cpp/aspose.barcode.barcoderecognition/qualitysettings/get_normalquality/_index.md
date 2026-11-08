---
title: "método"
linktitle: "get_NormalQuality"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Preajuste de calidad de reconocimiento NormalQuality. Adecuado para la mayoría de los códigos de barras en C++."
type: docs
weight: 200
url: /es/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_normalquality/
---
## QualitySettings::get_NormalQuality method


Preajuste de calidad de reconocimiento NormalQuality. Adecuado para la mayoría de los códigos de barras.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_NormalQuality()
```

## Observaciones


Este ejemplo muestra cómo usar el modo NormalQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Preajuste de calidad de reconocimiento NormalQuality.
## Ver también

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
