---
title: "BarcodeParameters.GS1CompositeBar"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "BarcodeParameters eigenschap. GS1 Composite Bar parameters"
type: docs
weight: 180
url: /nl/net/aspose.barcode.generation/barcodeparameters/gs1compositebar/
---
## BarcodeParameters.GS1CompositeBar property

GS1 Composite Bar parameters.

```csharp
public GS1CompositeBarParameters GS1CompositeBar { get; set; }
```

## Voorbeelden

Dit voorbeeld toont hoe een GS1 Composite Bar-afbeelding te maken en op te slaan. Merk op dat 1D-codetext en 2D-codetext gescheiden zijn door het symbool '&#x7C;'

```csharp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
  {
      generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
      generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
      
      // Beeldverhouding van 2D‑component
      generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
          
      // X‑dimensie van 1D‑ en 2D‑componenten
      generator.Parameters.Barcode.XDimension.Pixels = 3;
          
      // Hoogte van 1D‑component
      generator.Parameters.Barcode.BarHeight.Pixels = 100;
      
      generator.Save("test.png");
  }
```

### Zie ook

* class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* class [BarcodeParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


