---
title: "enum"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Hoe gebruik je enum in C++."
type: docs
weight: 3800
url: /nl/cpp/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enum




```cpp
enum class DeconvolutionMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Snel | 0 | Schakelt snelle deconvolutiemethoden in voor afbeeldingen van hoge kwaliteit. |
| Normal | 1 | Schakelt normale deconvolutiemethoden in voor gangbare afbeeldingen. |
| Langzaam | 2 | Schakelt trage deconvolutiemethoden in voor afbeeldingen van lage kwaliteit. |

## Opmerkingen


Deconvolutie‑modus (beeldherstel) die het niveau van beelddegradatie definieert. Oorspronkelijk is deconvolutie een functie die een beeld kan herstellen dat is gedegradeerd (geconvolueerd) door een natuurlijke functie zoals vervaging, bij het verkrijgen van een beeld met een camera. Omdat we de beeldfunctie die het beeld corrumpeert niet kunnen detecteren, moeten we de meest bekende functies controleren, zoals verscherpen of wiskundige morfologie.

Deze voorbeeld toont hoe de Deconvolution-modus te gebruiken
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Zie ook

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
