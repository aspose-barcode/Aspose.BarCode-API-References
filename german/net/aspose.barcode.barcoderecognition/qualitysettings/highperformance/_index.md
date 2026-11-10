---
title: "QualitySettings.HighPerformance"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "QualitySettings-Eigenschaft. HighPerformance-Erkennungsqualitätsvorgabe. Hochwertige Barcodes werden in diesem Modus gut erkannt."
type: docs
weight: 10
url: /de/net/aspose.barcode.barcoderecognition/qualitysettings/highperformance/
---
## QualitySettings.HighPerformance property

HighPerformance‑Voreinstellung für die Erkennungsqualität. Hochwertige Barcodes werden in diesem Modus gut erkannt.

```csharp
public static QualitySettings HighPerformance { get; }
```

### Property Value

HighPerformance-Erkennungsqualitätsvorgabe.

## Beispiele

Dieses Beispiel zeigt, wie man den HighPerformance-Modus verwendet.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Siehe auch

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


