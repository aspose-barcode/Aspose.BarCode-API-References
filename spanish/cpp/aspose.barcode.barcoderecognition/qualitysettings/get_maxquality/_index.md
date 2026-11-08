---
title: "método"
linktitle: "get_MaxQuality"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Preajuste de calidad de reconocimiento MaxQuality. Este preajuste está desarrollado para reconocer todos los códigos de barras posibles, incluso códigos de barras incorrectos en C++."
type: docs
weight: 400
url: /es/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_maxquality/
---
## QualitySettings::get_MaxQuality method


Preajuste de calidad de reconocimiento MaxQuality. Este preajuste está desarrollado para reconocer todos los códigos de barras posibles, incluso códigos de barras incorrectos.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_MaxQuality()
```

## Observaciones


Este ejemplo muestra cómo usar el modo MaxQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


Preajuste de calidad de reconocimiento MaxQuality.
## Ver también

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
