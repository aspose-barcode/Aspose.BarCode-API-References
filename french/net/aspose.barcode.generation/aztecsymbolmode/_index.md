---
title: "Enum AztecSymbolMode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.Generation.AztecSymbolMode enum. Spécifie le mode de symbole Aztec"
type: docs
weight: 970
url: /fr/net/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enumeration

Spécifie le mode du symbole Aztec.

```csharp
public enum AztecSymbolMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Auto | `0` | Spécifie de sélectionner automatiquement le meilleur symbole (Compact ou Full-range) pour Aztec. C'est la valeur par défaut. |
| Compact | `1` | Spécifie le symbole Compact pour Aztec. Le symbole Compact d'Aztec ne permet que 1, 2, 3 ou 4 couches. |
| FullRange | `2` | Spécifie le symbole Full-range pour Aztec. Le symbole Full-range d'Aztec permet de 1 à 32 couches. |
| Rune | `3` | Spécifie le symbole Rune pour Aztec. Les runes Aztec sont une série de petites marques lisibles par machine mais distinctes. Elles ne permettent que des valeurs numériques de 0 à 255. |

## Exemples

Cet exemple montre comment changer le mode de symbole Aztec et enregistrer une image BarCode.

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

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


