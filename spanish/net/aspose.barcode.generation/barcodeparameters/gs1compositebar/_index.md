---
title: "BarcodeParameters.GS1CompositeBar"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "BarcodeParameters propiedad. parámetros GS1 Composite Bar"
type: docs
weight: 180
url: /es/net/aspose.barcode.generation/barcodeparameters/gs1compositebar/
---
## BarcodeParameters.GS1CompositeBar property

Parámetros de barra compuesta GS1.

```csharp
public GS1CompositeBarParameters GS1CompositeBar { get; set; }
```

## Ejemplos

Este ejemplo muestra cómo crear y guardar una imagen GS1 Composite Bar. Nota que el codetext 1D y el codetext 2D están separados por el símbolo '&#x7C;'

```csharp
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

### Ver también

* class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* class [BarcodeParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


