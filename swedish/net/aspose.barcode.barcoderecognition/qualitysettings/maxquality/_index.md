---
title: "QualitySettings.MaxQuality"
second_title: "Aspose.BarCode för .NET API-referens"
description: "QualitySettings egenskap. MaxQuality‑igenkänningskvalitetsförinställning. Denna förinställning är utvecklad för att känna igen alla möjliga streckkoder, även felaktiga streckkoder"
type: docs
weight: 30
url: /sv/net/aspose.barcode.barcoderecognition/qualitysettings/maxquality/
---
## QualitySettings.MaxQuality property

MaxQuality‑igenkänningskvalitetsförinställning. Denna förinställning är utvecklad för att känna igen alla möjliga streckkoder, även felaktiga streckkoder.

```csharp
public static QualitySettings MaxQuality { get; }
```

### Property Value

MaxQuality‑igenkänningskvalitetsförinställning.

## Exempel

Detta exempel visar hur man använder MaxQuality‑läget

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Se även

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


