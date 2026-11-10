---
title: "QualitySettings.MaxQuality"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "QualitySettings-Eigenschaft. MaxQuality-Erkennungsqualitäts‑Voreinstellung. Diese Voreinstellung ist entwickelt, um alle möglichen Barcodes, sogar fehlerhafte Barcodes, zu erkennen."
type: docs
weight: 30
url: /de/net/aspose.barcode.barcoderecognition/qualitysettings/maxquality/
---
## QualitySettings.MaxQuality property

MaxQuality‑Voreinstellung für die Erkennungsqualität. Diese Voreinstellung ist entwickelt, um alle möglichen Barcodes zu erkennen, sogar fehlerhafte Barcodes.

```csharp
public static QualitySettings MaxQuality { get; }
```

### Property Value

MaxQuality-Erkennungsqualitäts‑Voreinstellung.

## Beispiele

Dieses Beispiel zeigt, wie der MaxQuality‑Modus verwendet wird.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Siehe auch

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


