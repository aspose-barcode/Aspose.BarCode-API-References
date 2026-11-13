---
title: "CodetextParameters"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.generation/codetextparameters/
---

## CodetextParameters class

Paramètres Codetext.

Le type CodetextParameters expose les membres suivants :
## Properties
| Name | Description |
| :- | :- |
| two_d_display_text | Texte qui sera affiché à la place du codetext dans les codes-barres 2D.<br/>            Utilisé pour : Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| font_mode | Spécifiez FontMode. Si FontMode est réglé sur Auto, la taille de la police sera calculée automatiquement en fonction de la valeur xDimension.<br/>            Il est recommandé d'utiliser FontMode.Auto notamment dans AutoSizeMode.Nearest ou AutoSizeMode.Interpolation.<br/>            Valeur par défaut : FontMode.Auto. |
| font | Spécifiez la police du CodeText affiché.<br/>            Valeur par défaut : Arial 5pt regular.<br/>            Ignoré si FontMode est réglé sur FontMode.Auto. |
| space | Espace entre le CodeText et le CodeBarres dans la valeur [Unit](/barcode/python-net/aspose.barcode.generation/unit/).<br/>            Valeur par défaut : 2pt.<br/>            Ignoré pour EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| alignement | Obtient ou définit l'alignement du texte du code.<br/>            Valeur par défaut : StringAlignment.Center. |
| couleur | Spécifie la couleur affichée du CodeText.<br/>            Valeur par défaut : Color.Black. |
| emplacement | Spécifie l'emplacement affiché du CodeText, définissez à CodeLocation.None pour masquer le CodeText.<br/>            Valeur par défaut : CodeLocation.Below pour les codes-barres 1D et CodeLocation.None pour les codes-barres 2D. |
| no_wrap | Spécifie les retours à la ligne (sauts de ligne) dans le texte.<br/>            Valeur par défaut : false. |

### Voir aussi

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

