---
title: "Enum BarcodeQualityMode"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.BarCodeRecognition.BarcodeQualityMode‑enum. Läge som möjliggör metoder för att känna igen streckkodelement med den valda kvaliteten. Streckkodelement med lägre kvalitet kräver fler hårda metoder vilket saktar ner igenkänningen."
type: docs
weight: 110
url: /sv/net/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enumeration

Läge som möjliggör metoder för att känna igen streckkodelement med den valda kvaliteten. Streckkodelement med lägre kvalitet kräver fler hårda metoder vilket saktar ner igenkänningen.

```csharp
public enum BarcodeQualityMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| High | `0` | Aktiverar igenkänningsmetoder för streckkoder av hög kvalitet. |
| Normal | `1` | Aktiverar igenkänningsmetoder för streckkoder av vanlig (normal) kvalitet. |
| Low | `2` | Aktiverar igenkänningsmetoder för streckkoder av låg kvalitet. |

## Exempel

Detta exempel visar hur man använder BarcodeQuality‑läge

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Se även

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


