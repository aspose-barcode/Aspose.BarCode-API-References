---
title: "enum"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Hur man använder enum i C++."
type: docs
weight: 3700
url: /sv/cpp/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enum




```cpp
enum class ComplexBackgroundMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | 0 | För närvarande samma som Disabled. Inaktiverar ytterligare igenkänning av färgstreckkoder på färgbilder. |
| Inaktiverad | 1 | Inaktiverar ytterligare igenkänning av färgstreckkoder på färgbilder. |
| Aktiverad | 2 | Aktiverar ytterligare igenkänning av färgstreckkoder på färgbilder. |

## Anmärkningar


Läge som aktiverar eller inaktiverar ytterligare igenkänning av färgstreckkoder på färgbilder.

Detta exempel visar hur man använder ComplexBackground-läget
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Se även

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
