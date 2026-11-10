---
title: "BarcodeParameters.GS1CompositeBar"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BarcodeParameters-Eigenschaft. GS1 Composite Bar-Parameter"
type: docs
weight: 180
url: /de/net/aspose.barcode.generation/barcodeparameters/gs1compositebar/
---
## BarcodeParameters.GS1CompositeBar property

GS1 Composite Bar-Parameter.

```csharp
public GS1CompositeBarParameters GS1CompositeBar { get; set; }
```

## Beispiele

Dieses Beispiel zeigt, wie man ein GS1 Composite Bar‑Bild erstellt und speichert. Hinweis: 1D‑Codetext und 2D‑Codetext werden durch das Symbol '&#x7C;' getrennt.

```csharp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
  {
      generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
      generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
      
      // Seitenverhältnis der 2D-Komponente
      generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
          
      // X-Dimension von 1D- und 2D-Komponenten
      generator.Parameters.Barcode.XDimension.Pixels = 3;
          
      // Höhe der 1D-Komponente
      generator.Parameters.Barcode.BarHeight.Pixels = 100;
      
      generator.Save("test.png");
  }
```

### Siehe auch

* class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* class [BarcodeParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


