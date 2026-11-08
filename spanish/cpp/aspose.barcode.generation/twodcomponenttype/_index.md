---
title: "enum"
linktitle: "TwoDComponentType"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " enum. Tipo de componente 2D en C++."
type: docs
weight: 8700
url: /es/cpp/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enum


Tipo de componente 2D

```cpp
enum class TwoDComponentType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Automático | 0 | Selección automática del tipo de componente 2D |
| CC_A | 1 | Tipo de componente 2D CC-A. Es una variante estructural de MicroPDF417 |
| CC_B | 2 | Tipo de componente 2D CC-B. Es un símbolo MicroPDF417. |
| CC_C | 3 | Tipo de componente 2D CC-C. Es un símbolo PDF417. |

## Observaciones


Esta muestra muestra cómo crear y guardar una imagen de barra compuesta GS1. Nota que el texto de código 1D y el texto de código 2D están separados por el símbolo '/'
```cpp
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

## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
