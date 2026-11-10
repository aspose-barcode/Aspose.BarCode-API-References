---
title: "QualitySettings.MaxQuality"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété QualitySettings. Préréglage de qualité de reconnaissance MaxQuality. Ce préréglage est conçu pour reconnaître tous les codes-barres possibles, même les codes-barres incorrects."
type: docs
weight: 30
url: /fr/net/aspose.barcode.barcoderecognition/qualitysettings/maxquality/
---
## QualitySettings.MaxQuality property

Préréglage de qualité de reconnaissance MaxQuality. Ce préréglage est développé pour reconnaître tous les codes‑barres possibles, même les codes‑barres incorrects.

```csharp
public static QualitySettings MaxQuality { get; }
```

### Property Value

Préréglage de qualité de reconnaissance MaxQuality.

## Exemples

Cet exemple montre comment utiliser le mode MaxQuality.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Voir aussi

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


