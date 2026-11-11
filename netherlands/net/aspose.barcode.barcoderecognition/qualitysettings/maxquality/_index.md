---
title: "QualitySettings.MaxQuality"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "QualitySettings eigenschap. MaxQuality herkenningskwaliteitsvoorinstelling. Deze voorinstelling is ontwikkeld om alle mogelijke barcodes te herkennen, zelfs onjuiste barcodes"
type: docs
weight: 30
url: /nl/net/aspose.barcode.barcoderecognition/qualitysettings/maxquality/
---
## QualitySettings.MaxQuality property

MaxQuality herkenningskwaliteitspreset. Deze preset is ontwikkeld om alle mogelijke barcodes te herkennen, zelfs onjuiste barcodes.

```csharp
public static QualitySettings MaxQuality { get; }
```

### Property Value

MaxQuality herkenningskwaliteitsvoorinstelling.

## Voorbeelden

Dit voorbeeld toont hoe de MaxQuality-modus te gebruiken

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Zie ook

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


