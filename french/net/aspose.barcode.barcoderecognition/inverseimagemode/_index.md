---
title: "Enum InverseImageMode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.BarCodeRecognition.InverseImageMode enum. Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres sur des images avec une luminance de couleurs inversée"
type: docs
weight: 270
url: /fr/net/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enumeration

Mode qui active ou désactive la reconnaissance supplémentaire des codes‑à‑barres sur des images aux couleurs inversées (luminance).

```csharp
public enum InverseImageMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Auto | `0` | Désactive la reconnaissance supplémentaire des codes-barres sur les images inversées pour tous les types de codes-barres sauf le QR Code. |
| Disabled | `1` | Désactive la reconnaissance supplémentaire des codes-barres sur les images inversées. |
| Enabled | `2` | Active la reconnaissance supplémentaire des codes-barres sur les images inversées |

## Exemples

Cet exemple montre comment utiliser le mode InverseImage

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Voir aussi

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


