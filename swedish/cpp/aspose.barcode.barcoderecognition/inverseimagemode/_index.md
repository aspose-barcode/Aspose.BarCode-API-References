---
title: "enum"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Hur man använder enum i C++."
type: docs
weight: 3900
url: /sv/cpp/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enum




```cpp
enum class InverseImageMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | 0 | Inaktiverar ytterligare igenkänning av streckkoder på inverterade bilder för alla streckkodstyper förutom [QR](../../aspose.barcode.barcoderecognition.qr/) Code. |
| Inaktiverad | 1 | Inaktiverar ytterligare igenkänning av streckkoder på inverterade bilder. |
| Aktiverad | 2 | Aktiverar ytterligare igenkänning av streckkoder på inverterade bilder |

## Anmärkningar


Läge som aktiverar eller inaktiverar ytterligare igenkänning av streckkoder på bilder med inverterade färger (luminans).

Detta exempel visar hur man använder InverseImage-läget
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Se även

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
