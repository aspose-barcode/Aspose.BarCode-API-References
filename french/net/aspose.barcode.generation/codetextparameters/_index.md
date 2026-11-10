---
title: "Classe CodetextParameters"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Generation.CodetextParameters. Paramètres du texte de code"
type: docs
weight: 1160
url: /fr/net/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class

Paramètres du texte de code.

```csharp
public class CodetextParameters
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Alignment](../../aspose.barcode.generation/codetextparameters/alignment/) { get; set; } | Obtient ou définit l'alignement du texte du code. Valeur par défaut : StringAlignment.Center. |
| [Color](../../aspose.barcode.generation/codetextparameters/color/) { get; set; } | Spécifiez la couleur d'affichage du CodeText. Valeur par défaut : Color.Black. |
| [Font](../../aspose.barcode.generation/codetextparameters/font/) { get; } | Spécifiez la police d'affichage du CodeText. Valeur par défaut : Arial 5pt regular. Ignoré si FontMode est défini sur FontMode.Auto. |
| [FontMode](../../aspose.barcode.generation/codetextparameters/fontmode/) { get; set; } | Spécifiez FontMode. Si FontMode est défini sur Auto, la taille de la police sera calculée automatiquement en fonction de la valeur xDimension. Il est recommandé d’utiliser FontMode.Auto notamment dans AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. Valeur par défaut : FontMode.Auto. |
| [Location](../../aspose.barcode.generation/codetextparameters/location/) { get; set; } | Spécifiez l’emplacement d’affichage du CodeText, réglez sur CodeLocation.None pour masquer le CodeText. Valeur par défaut : CodeLocation.Below pour les codes-barres 1D et CodeLocation.None pour les codes-barres 2D. |
| [NoWrap](../../aspose.barcode.generation/codetextparameters/nowrap/) { get; set; } | Spécifiez les retours à la ligne (sauts de ligne) dans le texte. Valeur par défaut : false. |
| [Space](../../aspose.barcode.generation/codetextparameters/space/) { get; set; } | Espace entre le CodeText et le CodeBarres dans la valeur [`Unit`](../unit/). Valeur par défaut : 2pt. Ignoré pour EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [TwoDDisplayText](../../aspose.barcode.generation/codetextparameters/twoddisplaytext/) { get; set; } | Texte qui sera affiché à la place du codetext dans les codes-barres 2D. Utilisé pour : Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/codetextparameters/tostring/)() | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `CodetextParameters`. |

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


