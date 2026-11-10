---
title: "Enum BarcodeQualityMode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.BarCodeRecognition.BarcodeQualityMode enum. Mode qui permet aux méthodes de reconnaître les éléments de code-barres avec la qualité sélectionnée. Un élément de code-barres de qualité inférieure nécessite des méthodes plus lourdes, ce qui ralentit la reconnaissance."
type: docs
weight: 110
url: /fr/net/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enumeration

Mode qui active les méthodes permettant de reconnaître les éléments du code‑à‑barres avec la qualité sélectionnée. Un élément de code‑à‑barres de qualité inférieure nécessite des méthodes plus complexes, ce qui ralentit la reconnaissance.

```csharp
public enum BarcodeQualityMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| High | `0` | Active les méthodes de reconnaissance pour les codes-barres de haute qualité. |
| Normal | `1` | Active les méthodes de reconnaissance pour les codes-barres de qualité commune (normale). |
| Low | `2` | Active les méthodes de reconnaissance pour les codes-barres de basse qualité. |

## Exemples

Cet exemple montre comment utiliser le mode BarcodeQuality

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Voir aussi

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


