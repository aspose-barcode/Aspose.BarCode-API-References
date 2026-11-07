---
title: "method"
linktitle: "get_GS1CompositeBar"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Parametri GS1 Composite Bar in C++."
type: docs
weight: 2500
url: /it/cpp/aspose.barcode.generation/barcodeparameters/get_gs1compositebar/
---
## BarcodeParameters::get_GS1CompositeBar method


Parametri del GS1 Composite Bar.

```cpp
System::SharedPtr<GS1CompositeBarParameters> Aspose::BarCode::Generation::BarcodeParameters::get_GS1CompositeBar() const
```

## Osservazioni


Questo esempio mostra come creare e salvare un'immagine GS1 Composite Bar. Nota che il testo codificato 1D e 2D sono separati dal simbolo '|'
```cpp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
      using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
      {
      generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
      generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

      // Rapporto d'aspetto del componente 2D
      generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

      // Dimensione X dei componenti 1D e 2D
      generator.Parameters.Barcode.XDimension.Pixels = 3;

      // Altezza del componente 1D
      generator.Parameters.Barcode.BarHeight.Pixels = 100;

      generator.Save("test.png");
  }
```

## Vedi anche

* Class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* Class [BarcodeParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
