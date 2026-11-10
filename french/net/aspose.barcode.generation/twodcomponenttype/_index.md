---
title: "Enum TwoDComponentType"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Enum Aspose.BarCode.Generation.TwoDComponentType. Type de composant 2D"
type: docs
weight: 1730
url: /fr/net/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enumeration

Type de composant 2D

```csharp
public enum TwoDComponentType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Auto | `0` | Sélection automatique du type de composant 2D |
| CC_A | `1` | Type CC-A de composant 2D. C’est une variante structurelle de MicroPDF417 |
| CC_B | `2` | Type CC-B de composant 2D. C’est un symbole MicroPDF417. |
| CC_C | `3` | Type CC-C de composant 2D. C’est un symbole PDF417. |

## Exemples

Cet exemple montre comment créer et enregistrer une image de barre composite GS1. Notez que le texte de code 1D et le texte de code 2D sont séparés par le symbole '/'

```csharp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
{
    generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
    generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
    
    // Ratio d’aspect du composant 2D
    generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
        
    // Dimension X des composants 1D et 2D
    generator.Parameters.Barcode.XDimension.Pixels = 3;
        
    // Hauteur du composant 1D
    generator.Parameters.Barcode.BarHeight.Pixels = 100;
    
    generator.Save("test.png");
}
```

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


