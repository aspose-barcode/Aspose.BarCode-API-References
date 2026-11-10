---
title: "Enum XDimensionMode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.BarCodeRecognition.XDimensionMode enum. Mode de reconnaissance qui définit la taille de 1 à l'infini de la cellule ou de la barre de la matrice d'élément minimal du code-barres"
type: docs
weight: 400
url: /fr/net/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enumeration

Mode de reconnaissance qui définit la taille (de 1 à l'infini) de l'élément minimal du code‑à‑barres : cellule de matrice ou barre.

```csharp
public enum XDimensionMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Auto | `0` | La valeur de XDimension est détectée par IA (SVM). Pour le moment, elle est identique à Normal |
| Small | `1` | Détecte les codes-barres avec une petite XDimension d'au moins 1 pixel avec une qualité provenant de BarcodeQuality |
| Normal | `2` | Détecte les codes-barres avec une XDimension classique d'au moins 2 pixels avec une qualité provenant de BarcodeQuality ou des codes-barres de haute qualité. |
| Large | `3` | Détecte les codes-barres avec une grande XDimension avec une qualité provenant de BarcodeQuality capturée par des caméras haute résolution. |
| UseMinimalXDimension | `4` | Détecte les codes-barres dont la taille est définie dans MinimalXDimension avec une qualité provenant de BarcodeQuality |

## Exemples

Cet exemple montre comment utiliser le mode XDimension

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Voir aussi

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


