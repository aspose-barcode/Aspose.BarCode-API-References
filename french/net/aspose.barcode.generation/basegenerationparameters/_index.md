---
title: "Classe BaseGenerationParameters"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Generation.BaseGenerationParameters. Paramètres de génération d'image de code-barres"
type: docs
weight: 1030
url: /fr/net/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class

Paramètres de génération d'image de code-barres.

```csharp
public class BaseGenerationParameters
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.generation/basegenerationparameters/autosizemode/) { get; set; } | Spécifie les différents types de modes de dimensionnement automatique. Valeur par défaut : AutoSizeMode.None. |
| [BackColor](../../aspose.barcode.generation/basegenerationparameters/backcolor/) { get; set; } | Couleur d'arrière-plan de l'image du code-barres. Valeur par défaut : Color.White. Voir Color. |
| [Barcode](../../aspose.barcode.generation/basegenerationparameters/barcode/) { get; } | Obtient le [`BarcodeParameters`](../barcodeparameters/) qui contient toutes les propriétés du code-barres. |
| [Border](../../aspose.barcode.generation/basegenerationparameters/border/) { get; } | Obtient le [`BorderParameters`](../borderparameters/) qui contient toutes les propriétés de configuration pour la bordure du code-barres. |
| [CaptionAbove](../../aspose.barcode.generation/basegenerationparameters/captionabove/) { get; } | Légende au-dessus de l'image du code-barres. Voir [`CaptionParameters`](../captionparameters/). |
| [CaptionBelow](../../aspose.barcode.generation/basegenerationparameters/captionbelow/) { get; } | Légende en dessous de l'image du code-barres. Voir [`CaptionParameters`](../captionparameters/). |
| [Image](../../aspose.barcode.generation/basegenerationparameters/image/) { get; } | Paramètres d'image. Voir [`ImageParameters`](../imageparameters/). |
| [ImageHeight](../../aspose.barcode.generation/basegenerationparameters/imageheight/) { get; set; } | Hauteur de l'image du code-barres lorsque la propriété [`AutoSizeMode`](./autosizemode/) est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |
| [ImageWidth](../../aspose.barcode.generation/basegenerationparameters/imagewidth/) { get; set; } | Largeur de l'image du code-barres lorsque la propriété [`AutoSizeMode`](./autosizemode/) est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |
| [Resolution](../../aspose.barcode.generation/basegenerationparameters/resolution/) { get; set; } | Obtient ou définit la résolution de l’image BarCode. Une valeur pour les deux dimensions. Valeur par défaut : 96 dpi. |
| [RotationAngle](../../aspose.barcode.generation/basegenerationparameters/rotationangle/) { get; set; } | Angle de rotation de l'image du code-barres, mesuré en degrés, par ex. RotationAngle = 0 ou RotationAngle = 360 signifie aucune rotation. Si RotationAngle n'est PAS égal à 90, 180, 270 ou 0, cela peut augmenter la difficulté pour le scanner de lire l'image. Valeur par défaut : 0. |
| [UseAntiAlias](../../aspose.barcode.generation/basegenerationparameters/useantialias/) { get; set; } | Obtient ou définit une valeur indiquant si le mode anti-aliasing est utilisé pour rendre l'image |

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


