---
title: "methode"
linktitle: "get_HighQuality"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " method. HighQuality herkenningskwaliteitsvoorinstelling. Deze voorinstelling is ontwikkeld voor barcodes van lage kwaliteit. Maakt het mogelijk om sterk beschadigde barcodes te detecteren in C++."
type: docs
weight: 300
url: /nl/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highquality/
---
## QualitySettings::get_HighQuality method


HighQuality herkenningskwaliteitspreset. Deze preset is ontwikkeld voor barcodes van lage kwaliteit. Maakt het mogelijk om sterk beschadigde barcodes te detecteren.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighQuality()
```

## Opmerkingen


Dit voorbeeld toont hoe de HighQuality-modus te gebruiken
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighQuality herkenningskwaliteitsvoorinstelling.
## Zie ook

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
