---
title: "método"
linktitle: "get_GS1CompositeBar"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Parámetros de GS1 Composite Bar en C++."
type: docs
weight: 2500
url: /es/cpp/aspose.barcode.generation/barcodeparameters/get_gs1compositebar/
---
## BarcodeParameters::get_GS1CompositeBar method


Parámetros de GS1 Composite Bar.

```cpp
System::SharedPtr<GS1CompositeBarParameters> Aspose::BarCode::Generation::BarcodeParameters::get_GS1CompositeBar() const
```

## Observaciones


Esta muestra muestra cómo crear y guardar una imagen de GS1 Composite Bar. Tenga en cuenta que el codetexto 1D y el codetexto 2D están separados por el símbolo '|'
```cpp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
      using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
      {
      generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
      generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

      // Relación de aspecto del componente 2D
      generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

      // Dimensión X de los componentes 1D y 2D
      generator.Parameters.Barcode.XDimension.Pixels = 3;

      // Altura del componente 1D
      generator.Parameters.Barcode.BarHeight.Pixels = 100;

      generator.Save("test.png");
  }
```

## Ver también

* Class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* Class [BarcodeParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
