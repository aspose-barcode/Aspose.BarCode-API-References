---
title: "Enum TwoDComponentType"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Enum Aspose.BarCode.Generation.TwoDComponentType. Tipo de componente 2D"
type: docs
weight: 1730
url: /es/net/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enumeration

Tipo de componente 2D

```csharp
public enum TwoDComponentType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | `0` | Seleccionar automáticamente el tipo de componente 2D |
| CC_A | `1` | Tipo CC-A de componente 2D. Es una variante estructural de MicroPDF417 |
| CC_B | `2` | Tipo CC-B de componente 2D. Es un símbolo MicroPDF417. |
| CC_C | `3` | Tipo CC-C de componente 2D. Es un símbolo PDF417. |

## Ejemplos

Este ejemplo muestra cómo crear y guardar una imagen de barra compuesta GS1. Tenga en cuenta que el texto de código 1D y el texto de código 2D están separados por el símbolo '/'

```csharp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
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

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


