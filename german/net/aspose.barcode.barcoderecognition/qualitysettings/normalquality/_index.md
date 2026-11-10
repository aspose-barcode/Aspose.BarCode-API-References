---
title: "QualitySettings.NormalQuality"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "QualitySettings-Eigenschaft. NormalQuality-Erkennungsqualitäts‑Voreinstellung. Geeignet für die meisten Barcodes."
type: docs
weight: 40
url: /de/net/aspose.barcode.barcoderecognition/qualitysettings/normalquality/
---
## QualitySettings.NormalQuality property

NormalQuality Erkennungsqualitäts‑Voreinstellung. Geeignet für die meisten Barcodes

```csharp
public static QualitySettings NormalQuality { get; }
```

### Property Value

NormalQuality-Erkennungsqualitäts‑Voreinstellung.

## Beispiele

Dieses Beispiel zeigt, wie der NormalQuality‑Modus verwendet wird.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Siehe auch

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


