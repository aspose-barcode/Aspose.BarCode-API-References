---
title: "methode"
linktitle: "get_HighPerformance"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. HighPerformance‑herkenningskwaliteitsvoorinstelling. Hoogwaardige barcodes worden goed herkend in deze modus in C++."
type: docs
weight: 100
url: /nl/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highperformance/
---
## QualitySettings::get_HighPerformance method


HighPerformance herkenningskwaliteitspreset. Hoogwaardige barcodes worden goed herkend in deze modus.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighPerformance()
```

## Opmerkingen


Dit voorbeeld toont hoe de HighPerformance‑modus te gebruiken
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighPerformance‑herkenningskwaliteitsvoorinstelling.
## Zie ook

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
