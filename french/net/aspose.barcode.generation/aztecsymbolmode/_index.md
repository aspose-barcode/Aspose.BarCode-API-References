---
title: AztecSymbolMode
second_title: Référence de l'API Aspose.BarCode pour .NET
description: Spécifie le mode symbole aztèque.
type: docs
weight: 460
url: /fr/net/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enumeration

Spécifie le mode symbole aztèque.

```csharp
public enum AztecSymbolMode
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Auto | `0` | Spécifie de sélectionner automatiquement le meilleur symbole (Compact ou Full-range) pour Aztec. Il s'agit de la valeur par défaut. |
| Compact | `1` | Spécifie le symbole compact pour Aztec. Le symbole compact aztèque n'autorise que 1, 2, 3 ou 4 couches. |
| FullRange | `2` | Spécifie le symbole de plage complète pour Aztec. Le symbole de plage complète aztèque permet de 1 à 32 couches. |
| Rune | `3` | Spécifie le symbole Rune pour Aztec. Les runes aztèques sont une série de petites mais distinctes marques lisibles par machine. Il n'autorise que la valeur numérique de 0 à 255. |

### Exemples

Cet exemple montre comment changer le mode Symbole aztèque et enregistrer une image de code-barres.

```csharp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.CodeText = "125";
    generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune;
    generator.Save("test.png");
}
[VB.NET]
Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec)
    generator.CodeText = "125"
    generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune
    generator.Save("test.png")
End Using
```

### Voir également

* espace de noms [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* Assemblée [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
