---
title: "Classe CodetextParametersUI"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Windows.Forms.CodetextParametersUI. Paramètres du texte du code"
type: docs
weight: 1820
url: /fr/net/aspose.barcode.windows.forms/codetextparametersui/
---
## CodetextParametersUI class

Paramètres du texte de code.

```csharp
public class CodetextParametersUI
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Alignment](../../aspose.barcode.windows.forms/codetextparametersui/alignment/) { get; set; } | Obtient ou définit l'alignement du texte du code. Valeur par défaut : StringAlignment.Center. |
| [Color](../../aspose.barcode.windows.forms/codetextparametersui/color/) { get; set; } | Spécifiez la couleur d'affichage du CodeText. Valeur par défaut : Color.Black. |
| [Font](../../aspose.barcode.windows.forms/codetextparametersui/font/) { get; set; } | Spécifiez la police d'affichage du CodeText. Valeur par défaut : Arial 5pt regular. Ignoré si FontMode est défini sur FontMode.Auto. |
| [FontMode](../../aspose.barcode.windows.forms/codetextparametersui/fontmode/) { get; set; } | Spécifiez FontMode. Si FontMode est défini sur Auto, la taille de la police sera calculée automatiquement en fonction de la valeur xDimension. Il est recommandé d’utiliser FontMode.Auto notamment dans AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. Valeur par défaut : FontMode.Auto. |
| [Location](../../aspose.barcode.windows.forms/codetextparametersui/location/) { get; set; } | Spécifiez l’emplacement d’affichage du CodeText, réglez sur CodeLocation.None pour masquer le CodeText. Valeur par défaut : CodeLocation.Below pour les codes-barres 1D et CodeLocation.None pour les codes-barres 2D. |
| [Space](../../aspose.barcode.windows.forms/codetextparametersui/space/) { get; } | Espace entre le CodeText et le CodeBarre en valeur [`Unit`](../../aspose.barcode.generation/unit/). Valeur par défaut : 2 pt. Ignoré pour EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [TwoDDisplayText](../../aspose.barcode.windows.forms/codetextparametersui/twoddisplaytext/) { get; set; } | Texte qui sera affiché à la place du codetext dans les codes-barres 2D. Utilisé pour : Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/codetextparametersui/tostring/)() | Renvoie une représentation sous forme de chaîne lisible de cet objet [`CodetextParameters`](../../aspose.barcode.generation/codetextparameters/). |

### Voir aussi

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


