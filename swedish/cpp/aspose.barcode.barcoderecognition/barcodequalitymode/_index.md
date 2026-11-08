---
title: "enum"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Hur man använder enum i C++."
type: docs
weight: 3600
url: /sv/cpp/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enum




```cpp
enum class BarcodeQualityMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Hög | 0 | Aktiverar igenkänningsmetoder för streckkoder av hög kvalitet. |
| Normal | 1 | Aktiverar igenkänningsmetoder för vanliga (normala) kvalitetsstreckkoder. |
| Låg | 2 | Aktiverar igenkänningsmetoder för streckkoder av låg kvalitet. |

## Anmärkningar


Läge som möjliggör metoder för att känna igen streckkodselement med den valda kvaliteten. Streckkodselement med lägre kvalitet kräver mer krävande metoder vilket saktar ner igenkänningen.

Detta exempel visar hur man använder BarcodeQuality-läget
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Se även

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
