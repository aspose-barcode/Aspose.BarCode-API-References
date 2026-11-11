---
title: "Enum InverseImageMode"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.BarCodeRecognition.InverseImageMode enum. Läge som möjliggör eller inaktiverar ytterligare igenkänning av streckkoder på bilder med inverterad färgluminans"
type: docs
weight: 270
url: /sv/net/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enumeration

Läge som möjliggör eller inaktiverar ytterligare igenkänning av streckkoder på bilder med inverterade färger (luminans).

```csharp
public enum InverseImageMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | `0` | Inaktiverar ytterligare igenkänning av streckkoder på inverterade bilder för alla streckkodstyper förutom QR‑kod. |
| Disabled | `1` | Inaktiverar ytterligare igenkänning av streckkoder på inverterade bilder. |
| Enabled | `2` | Möjliggör ytterligare igenkänning av streckkoder på inverterade bilder |

## Exempel

Detta exempel visar hur man använder InverseImage‑läget

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Se även

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


