---
title: "QualitySettings.NormalQuality"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "QualitySettings eigenschap. NormalQuality herkenningskwaliteitsvoorinstelling. Geschikt voor de meeste barcodes"
type: docs
weight: 40
url: /nl/net/aspose.barcode.barcoderecognition/qualitysettings/normalquality/
---
## QualitySettings.NormalQuality property

NormalQuality herkenningskwaliteitspreset. Geschikt voor de meeste barcodes

```csharp
public static QualitySettings NormalQuality { get; }
```

### Property Value

NormalQuality herkenningskwaliteitsvoorinstelling.

## Voorbeelden

Dit voorbeeld toont hoe de NormalQuality-modus te gebruiken

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Zie ook

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


