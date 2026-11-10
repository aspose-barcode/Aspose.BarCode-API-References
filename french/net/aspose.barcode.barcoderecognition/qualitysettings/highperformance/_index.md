---
title: "QualitySettings.HighPerformance"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété QualitySettings. Préréglage de qualité de reconnaissance HighPerformance. Les codes‑barres de haute qualité sont bien reconnus dans ce mode."
type: docs
weight: 10
url: /fr/net/aspose.barcode.barcoderecognition/qualitysettings/highperformance/
---
## QualitySettings.HighPerformance property

Préréglage de qualité de reconnaissance HighPerformance. Les codes‑barres de haute qualité sont bien reconnus dans ce mode.

```csharp
public static QualitySettings HighPerformance { get; }
```

### Property Value

Préréglage de qualité de reconnaissance HighPerformance.

## Exemples

Cet exemple montre comment utiliser le mode HighPerformance.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Voir aussi

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


