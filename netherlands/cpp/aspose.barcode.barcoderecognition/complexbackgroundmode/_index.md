---
title: "enum"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Hoe gebruik je enum in C++."
type: docs
weight: 3700
url: /nl/cpp/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enum




```cpp
enum class ComplexBackgroundMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | 0 | Op dit moment hetzelfde als Disabled. Schakelt extra herkenning van gekleurde barcodes op kleurafbeeldingen uit. |
| Uitgeschakeld | 1 | Schakelt extra herkenning van gekleurde barcodes op kleurafbeeldingen uit. |
| Ingeschakeld | 2 | Schakelt extra herkenning van gekleurde barcodes op kleurafbeeldingen in. |

## Opmerkingen


Modus die extra herkenning van gekleurde barcodes op kleurafbeeldingen in- of uitschakelt.

Dit voorbeeld laat zien hoe de ComplexBackground-modus te gebruiken.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Zie ook

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
