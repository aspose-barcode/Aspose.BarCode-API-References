---
title: "methode"
linktitle: "get_MaxQuality"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. MaxQuality herkenningskwaliteitsvoorinstelling. Deze voorinstelling is ontwikkeld om alle mogelijke barcodes te herkennen, zelfs onjuiste barcodes in C++."
type: docs
weight: 400
url: /nl/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_maxquality/
---
## QualitySettings::get_MaxQuality method


MaxQuality herkenningskwaliteitsvoorkeur. Deze voorkeur is ontwikkeld om alle mogelijke barcodes te herkennen, zelfs onjuiste barcodes.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_MaxQuality()
```

## Opmerkingen


Dit voorbeeld toont hoe de MaxQuality-modus te gebruiken
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


MaxQuality herkenningskwaliteitsvoorinstelling.
## Zie ook

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
