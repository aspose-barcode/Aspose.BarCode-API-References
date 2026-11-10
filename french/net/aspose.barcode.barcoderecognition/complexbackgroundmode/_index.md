---
title: "Enum ComplexBackgroundMode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Enum Aspose.BarCode.BarCodeRecognition.ComplexBackgroundMode. Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres couleur sur des images couleur"
type: docs
weight: 200
url: /fr/net/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enumeration

Mode qui active ou désactive la reconnaissance supplémentaire des codes‑à‑barres couleur sur les images en couleur.

```csharp
public enum ComplexBackgroundMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Auto | `0` | Pour le moment, identique à Disabled. Désactive la reconnaissance supplémentaire des codes-barres couleur sur des images couleur. |
| Disabled | `1` | Désactive la reconnaissance supplémentaire des codes-barres couleur sur des images couleur. |
| Enabled | `2` | Active la reconnaissance supplémentaire des codes-barres couleur sur des images couleur. |

## Exemples

Cet exemple montre comment utiliser le mode ComplexBackground

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Voir aussi

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


