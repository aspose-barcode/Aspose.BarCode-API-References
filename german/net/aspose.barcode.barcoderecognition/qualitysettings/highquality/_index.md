---
title: "QualitySettings.HighQuality"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "QualitySettings-Eigenschaft. HighQuality-Erkennungsqualitäts‑Voreinstellung. Diese Voreinstellung ist für Barcodes niedriger Qualität entwickelt. Ermöglicht das Erkennen stark beschädigter Barcodes."
type: docs
weight: 20
url: /de/net/aspose.barcode.barcoderecognition/qualitysettings/highquality/
---
## QualitySettings.HighQuality property

HighQuality‑Voreinstellung für die Erkennungsqualität. Diese Voreinstellung ist für Barcodes niedriger Qualität entwickelt. Sie ermöglicht das Erkennen stark beschädigter Barcodes.

```csharp
public static QualitySettings HighQuality { get; }
```

### Property Value

HighQuality-Erkennungsqualitäts‑Voreinstellung.

## Beispiele

Dieses Beispiel zeigt, wie der HighQuality‑Modus verwendet wird.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Siehe auch

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


