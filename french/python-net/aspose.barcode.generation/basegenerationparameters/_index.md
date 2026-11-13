---
title: "BaseGenerationParameters"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

Paramètres de génération d'images de codes-barres.

Le type BaseGenerationParameters expose les membres suivants :
## Properties
| Name | Description |
| :- | :- |
| use_anti_alias | Obtient ou définit une valeur indiquant si le mode anti-aliasing est utilisé pour rendre l'image |
| back_color | Couleur d'arrière-plan de l'image du code-barres.<br/>            Valeur par défaut : Color.White.<br/>            Voir [Color](/barcode/python-net/aspose.drawing/color/). |
| résolution | Obtient ou définit la résolution de l'image du code-barres.<br/>            Une valeur pour les deux dimensions.<br/>            Valeur par défaut : 96 dpi. |
| rotation_angle | Angle de rotation de l'image du code-barres, mesuré en degrés, par ex. RotationAngle = 0 ou RotationAngle = 360 signifie aucune rotation.<br/>            Si RotationAngle n'est PAS égal à 90, 180, 270 ou 0, cela peut augmenter la difficulté pour le scanner de lire l'image.<br/>            Valeur par défaut : 0. |
| caption_above | Légende au-dessus de l'image du code-barres. Voir [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| caption_below | Légende en dessous de l'image du code-barres. Voir [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| image | Paramètres d'image. Voir [ImageParameters](/barcode/python-net/aspose.barcode.generation/imageparameters/). |
| auto_size_mode | Spécifie les différents types de modes de dimensionnement automatique.<br/>            Valeur par défaut : AutoSizeMode.None. |
| image_height | Hauteur de l'image BarCode lorsque la propriété [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |
| image_width | Largeur de l'image BarCode lorsque la propriété [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |
| barcode | Obtient les [BarcodeParameters](/barcode/python-net/aspose.barcode.generation/barcodeparameters/) qui contiennent toutes les propriétés du code-barres. |
| border | Obtient les [BorderParameters](/barcode/python-net/aspose.barcode.generation/borderparameters/) qui contiennent toutes les propriétés de configuration pour la bordure du code-barres. |

### Voir aussi

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

