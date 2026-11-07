---
title: "Methode"
linktitle: "set_GS1CompositeBar"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. GS1 Composite Bar-Parameter in C++."
type: docs
weight: 2600
url: /de/cpp/aspose.barcode.generation/barcodeparameters/set_gs1compositebar/
---
## BarcodeParameters::set_GS1CompositeBar method


GS1 Composite Bar-Parameter.

```cpp
void Aspose::BarCode::Generation::BarcodeParameters::set_GS1CompositeBar(System::SharedPtr<GS1CompositeBarParameters> value)
```

## Hinweise


Dieses Beispiel zeigt, wie man ein GS1 Composite Bar-Bild erstellt und speichert. Hinweis: 1D-Codetext und 2D-Codetext sind durch das Symbol '|' getrennt.
```cpp
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

## Siehe auch

* Class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* Class [BarcodeParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
