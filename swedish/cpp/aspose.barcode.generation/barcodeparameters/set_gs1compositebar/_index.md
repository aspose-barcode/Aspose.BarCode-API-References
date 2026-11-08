---
title: "metod"
linktitle: "set_GS1CompositeBar"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. GS1 Composite Bar-parametrar i C++."
type: docs
weight: 2600
url: /sv/cpp/aspose.barcode.generation/barcodeparameters/set_gs1compositebar/
---
## BarcodeParameters::set_GS1CompositeBar method


GS1 Composite Bar-parametrar.

```cpp
void Aspose::BarCode::Generation::BarcodeParameters::set_GS1CompositeBar(System::SharedPtr<GS1CompositeBarParameters> value)
```

## Anmärkningar


Detta exempel visar hur man skapar och sparar en GS1 Composite Bar-bild. Observera att 1D-kodtext och 2D-kodtext separeras av symbolen '|'
```cpp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
      using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
      {
      generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
      generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

      // Bildförhållande för 2D-komponent
      generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

      // X-dimension för 1D- och 2D-komponenter
      generator.Parameters.Barcode.XDimension.Pixels = 3;

      // Höjd för 1D-komponent
      generator.Parameters.Barcode.BarHeight.Pixels = 100;

      generator.Save("test.png");
  }
```

## Se även

* Class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* Class [BarcodeParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
