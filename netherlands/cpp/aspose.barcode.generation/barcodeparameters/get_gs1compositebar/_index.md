---
title: "methode"
linktitle: "get_GS1CompositeBar"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. GS1 Composite Bar-parameters in C++."
type: docs
weight: 2500
url: /nl/cpp/aspose.barcode.generation/barcodeparameters/get_gs1compositebar/
---
## BarcodeParameters::get_GS1CompositeBar method


GS1 Composite Bar-parameters.

```cpp
System::SharedPtr<GS1CompositeBarParameters> Aspose::BarCode::Generation::BarcodeParameters::get_GS1CompositeBar() const
```

## Opmerkingen


Deze voorbeeld toont hoe een GS1 Composite Bar-afbeelding te maken en op te slaan. Merk op dat 1D-codetekst en 2D-codetekst gescheiden zijn door het symbool '|'
```cpp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
      using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
      {
      generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
      generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

      // Aspectratio van 2D-component
      generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

      // X-dimensie van 1D- en 2D-componenten
      generator.Parameters.Barcode.XDimension.Pixels = 3;

      // Hoogte van 1D-component
      generator.Parameters.Barcode.BarHeight.Pixels = 100;

      generator.Save("test.png");
  }
```

## Zie ook

* Class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* Class [BarcodeParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
