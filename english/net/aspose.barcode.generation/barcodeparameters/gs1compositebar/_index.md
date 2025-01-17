---
title: BarcodeParameters.GS1CompositeBar
second_title: Aspose.BarCode for .NET API Reference
description: BarcodeParameters property. GS1 Composite Bar parameters
type: docs
weight: 180
url: /net/aspose.barcode.generation/barcodeparameters/gs1compositebar/
---
## BarcodeParameters.GS1CompositeBar property

GS1 Composite Bar parameters.

```csharp
public GS1CompositeBarParameters GS1CompositeBar { get; set; }
```

## Examples

This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '&#x7C;'

```csharp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
  {
      generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
      generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
      
      // Aspect ratio of 2D component
      generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
          
      // X-Dimension of 1D and 2D components
      generator.Parameters.Barcode.XDimension.Pixels = 3;
          
      // Height of 1D component
      generator.Parameters.Barcode.BarHeight.Pixels = 100;
      
      generator.Save("test.png");
  }
```

### See Also

* class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* class [BarcodeParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


