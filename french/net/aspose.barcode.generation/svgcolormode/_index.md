---
title: "Enum SvgColorMode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.Generation.SvgColorMode enum. Modes possibles pour le remplissage de couleur dans un fichier svg. RGB est le défaut et pris en charge par SVG 1.1. RGBA, HSL, HSLA sont autorisés dans la norme SVG 2.0. Même en RGB, l'opacité sera définie via le paramètre fillopacity."
type: docs
weight: 1690
url: /fr/net/aspose.barcode.generation/svgcolormode/
---
## SvgColorMode enumeration

Modes possibles pour la couleur de remplissage dans un fichier svg, RGB est la valeur par défaut et prise en charge par SVG 1.1. RGBA, HSL, HSLA sont autorisés dans la norme SVG 2.0. Même en RGB, l'opacité sera définie via le paramètre "fill-opacity".

```csharp
public enum SvgColorMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| RGB | `0` | Mode RGB, exemple : fill="#ff5511" fill-opacity="0.73". Mode par défaut. |
| RGBA | `1` | Mode RGBA, exemple : fill="rgba(255, 85, 17, 0.73)" |
| HSL | `2` | Mode HSL, exemple : fill="hsl(17, 100%, 53%)" fill-opacity="0.73" |
| HSLA | `3` | Mode HSLA, exemple : fill="hsla(30, 50%, 70%, 0.8)" |

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


