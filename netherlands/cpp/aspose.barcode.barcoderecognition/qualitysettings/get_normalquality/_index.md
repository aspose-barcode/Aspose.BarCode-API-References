---
title: "methode"
linktitle: "get_NormalQuality"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. NormalQuality herkenningskwaliteitsvoorinstelling. Geschikt voor de meeste barcodes in C++."
type: docs
weight: 200
url: /nl/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_normalquality/
---
## QualitySettings::get_NormalQuality method


NormalQuality herkenningskwaliteitsvoorkeur. Geschikt voor de meeste barcodes

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_NormalQuality()
```

## Opmerkingen


Dit voorbeeld laat zien hoe de NormalQuality-modus te gebruiken
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


NormalQuality herkenningskwaliteitsvoorinstelling.
## Zie ook

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
