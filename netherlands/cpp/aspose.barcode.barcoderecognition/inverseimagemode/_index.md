---
title: "enum"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Hoe gebruik je enum in C++."
type: docs
weight: 3900
url: /nl/cpp/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enum




```cpp
enum class InverseImageMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | 0 | Schakelt extra herkenning van barcodes op inverse afbeeldingen uit voor alle barcode‑typen, behalve [QR](../../aspose.barcode.barcoderecognition.qr/) Code. |
| Uitgeschakeld | 1 | Schakelt extra herkenning van barcodes op inverse afbeeldingen uit. |
| Ingeschakeld | 2 | Schakelt extra herkenning van barcodes op inverse afbeeldingen in |

## Opmerkingen


Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt.

Deze voorbeeld toont hoe de InverseImage-modus te gebruiken
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Zie ook

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
