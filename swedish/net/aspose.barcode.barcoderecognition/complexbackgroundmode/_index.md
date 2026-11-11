---
title: "Enum ComplexBackgroundMode"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.BarCodeRecognition.ComplexBackgroundMode enum. Läge som aktiverar eller inaktiverar ytterligare igenkänning av färgade streckkoder på färgbilder"
type: docs
weight: 200
url: /sv/net/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enumeration

Läge som aktiverar eller inaktiverar ytterligare igenkänning av färgade streckkoder på färgbilder.

```csharp
public enum ComplexBackgroundMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | `0` | För närvarande samma som Disabled. Inaktiverar ytterligare igenkänning av färgade streckkoder på färgbilder. |
| Disabled | `1` | Inaktiverar ytterligare igenkänning av färgade streckkoder på färgbilder. |
| Enabled | `2` | Aktiverar ytterligare igenkänning av färgade streckkoder på färgbilder. |

## Exempel

Detta exempel visar hur man använder ComplexBackground-läget

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Se även

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


