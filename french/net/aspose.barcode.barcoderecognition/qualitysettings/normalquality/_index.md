---
title: "QualitySettings.NormalQuality"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété QualitySettings. Préréglage de qualité de reconnaissance NormalQuality. Convient à la plupart des codes-barres."
type: docs
weight: 40
url: /fr/net/aspose.barcode.barcoderecognition/qualitysettings/normalquality/
---
## QualitySettings.NormalQuality property

Préréglage de qualité de reconnaissance NormalQuality. Convient à la plupart des codes‑barres

```csharp
public static QualitySettings NormalQuality { get; }
```

### Property Value

Préréglage de qualité de reconnaissance NormalQuality.

## Exemples

Cet exemple montre comment utiliser le mode NormalQuality.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Voir aussi

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


