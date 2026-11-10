---
title: "BarcodeParameters.GS1CompositeBar"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "BarcodeParameters propriété. Paramètres GS1 Composite Bar"
type: docs
weight: 180
url: /fr/net/aspose.barcode.generation/barcodeparameters/gs1compositebar/
---
## BarcodeParameters.GS1CompositeBar property

Paramètres de la barre composite GS1.

```csharp
public GS1CompositeBarParameters GS1CompositeBar { get; set; }
```

## Exemples

Cet exemple montre comment créer et enregistrer une image GS1 Composite Bar. Notez que le codetext 1D et le codetext 2D sont séparés par le symbole '&#x7C;'

```csharp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
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

* class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* class [BarcodeParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


