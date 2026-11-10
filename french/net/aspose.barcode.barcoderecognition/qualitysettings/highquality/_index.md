---
title: "QualitySettings.HighQuality"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété QualitySettings. Préréglage de qualité de reconnaissance HighQuality. Ce préréglage est développé pour les codes-barres de faible qualité. Permet de détecter les codes-barres fortement endommagés."
type: docs
weight: 20
url: /fr/net/aspose.barcode.barcoderecognition/qualitysettings/highquality/
---
## QualitySettings.HighQuality property

Préréglage de qualité de reconnaissance HighQuality. Ce préréglage est conçu pour les codes‑barres de faible qualité. Il permet de détecter les codes‑barres fortement endommagés.

```csharp
public static QualitySettings HighQuality { get; }
```

### Property Value

Préréglage de qualité de reconnaissance HighQuality.

## Exemples

Cet exemple montre comment utiliser le mode HighQuality.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Voir aussi

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


