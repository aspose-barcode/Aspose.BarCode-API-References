---
title: "QualitySettings.HighPerformance"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "QualitySettings eigenschap. HighPerformance‑herkenningskwaliteitspreset. Barcodes van hoge kwaliteit worden goed herkend in deze modus."
type: docs
weight: 10
url: /nl/net/aspose.barcode.barcoderecognition/qualitysettings/highperformance/
---
## QualitySettings.HighPerformance property

HighPerformance herkenningskwaliteitspreset. Barcodes van hoge kwaliteit worden goed herkend in deze modus.

```csharp
public static QualitySettings HighPerformance { get; }
```

### Property Value

HighPerformance‑herkenningskwaliteitspreset.

## Voorbeelden

Dit voorbeeld toont hoe de HighPerformance-modus te gebruiken.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Zie ook

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


