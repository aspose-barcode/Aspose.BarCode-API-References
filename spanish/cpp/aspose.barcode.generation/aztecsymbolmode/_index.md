---
title: "enum"
linktitle: "AztecSymbolMode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " enum. Especifica el modo de símbolo Aztec en C++."
type: docs
weight: 5400
url: /es/cpp/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enum


Especifica el modo de símbolo Aztec.

```cpp
enum class AztecSymbolMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Automático | 0 | Especifica que se seleccione automáticamente el mejor símbolo (Compact o Full-range) para Aztec. Este es el valor predeterminado. |
| Compact | 1 | Especifica el símbolo Compact para Aztec. El símbolo Compact de Aztec permite solo 1, 2, 3 o 4 capas. |
| FullRange | 2 | Especifica el símbolo Full-range para Aztec. El símbolo Full-range de Aztec permite de 1 a 32 capas. |
| Rune | 3 | Especifica el símbolo Rune para Aztec. Los Runes de Aztec son una serie de marcas pequeñas pero distintas legibles por máquina. Permite solo valores numéricos de 0 a 255. |

## Observaciones


Este ejemplo muestra cómo cambiar el modo de símbolo Aztec y guardar una imagen de [BarCode](../../aspose.barcode/).
```cpp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.CodeText = "125";
    generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune;
    generator.Save("test.png");
}
    [VB.NET]
    Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec)
        generator.CodeText = "125"
        generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune
        generator.Save("test.png")
    End Using
```

## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
