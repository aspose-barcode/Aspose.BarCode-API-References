---
title: "Classe Unit"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Generation.Unit. Spécifie la valeur de taille dans différentes unités Pixel Pouces etc"
type: docs
weight: 1740
url: /fr/net/aspose.barcode.generation/unit/
---
## Unit class

Spécifie la valeur de taille dans différentes unités (Pixel, Pouces, etc.).

```csharp
public sealed class Unit
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Document](../../aspose.barcode.generation/unit/document/) { get; set; } | Obtient ou définit la valeur de taille en unités du document. |
| [Inches](../../aspose.barcode.generation/unit/inches/) { get; set; } | Obtient ou définit la valeur de taille en pouces. |
| [Millimeters](../../aspose.barcode.generation/unit/millimeters/) { get; set; } | Obtient ou définit la valeur de taille en millimètres. |
| [Pixels](../../aspose.barcode.generation/unit/pixels/) { get; set; } | Obtient ou définit la valeur de taille en pixels. |
| [Point](../../aspose.barcode.generation/unit/point/) { get; set; } | Obtient ou définit la valeur de taille en points. |
| [Resolution](../../aspose.barcode.generation/unit/resolution/) { get; } | Résolution |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.generation/unit/equals/)(object) | Détermine si cette instance et un objet spécifié, qui doit également être un objet `Unit`, ont la même valeur. |
| override [GetHashCode](../../aspose.barcode.generation/unit/gethashcode/)() | Renvoie le code de hachage pour cet objet. |
| override [ToString](../../aspose.barcode.generation/unit/tostring/)() | Renvoie une représentation sous forme de chaîne lisible de cet `Unit`. |

## Exemples

Cet exemple montre comment créer et enregistrer une image BarCode.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


