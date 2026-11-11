---
title: "QualitySettings.HighQuality"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "QualitySettings-eigenschap. HighQuality-herkenningskwaliteitspreset. Deze preset is ontwikkeld voor barcodes van lage kwaliteit. Maakt het mogelijk om sterk beschadigde barcodes te detecteren."
type: docs
weight: 20
url: /nl/net/aspose.barcode.barcoderecognition/qualitysettings/highquality/
---
## QualitySettings.HighQuality property

HighQuality herkenningskwaliteitspreset. Deze preset is ontwikkeld voor barcodes van lage kwaliteit. Maakt het mogelijk om sterk beschadigde barcodes te detecteren.

```csharp
public static QualitySettings HighQuality { get; }
```

### Property Value

HighQuality herkenningskwaliteitsvoorinstelling.

## Voorbeelden

Dit voorbeeld toont hoe de HighQuality-modus te gebruiken

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Zie ook

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


