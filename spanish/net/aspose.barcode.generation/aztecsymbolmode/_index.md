---
title: "Enum AztecSymbolMode"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Aspose.BarCode.Generation.AztecSymbolMode enum. Especifica el modo de símbolo Aztec"
type: docs
weight: 970
url: /es/net/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enumeration

Especifica el modo de símbolo Aztec.

```csharp
public enum AztecSymbolMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | `0` | Especifica la selección automática del mejor símbolo (Compacto o de rango completo) para Aztec. Este es el valor predeterminado. |
| Compact | `1` | Especifica el símbolo Compacto para Aztec. El símbolo Compacto de Aztec permite solo 1, 2, 3 o 4 capas. |
| FullRange | `2` | Especifica el símbolo de rango completo para Aztec. El símbolo de rango completo de Aztec permite de 1 a 32 capas. |
| Rune | `3` | Especifica el símbolo Rune para Aztec. Los Runes de Aztec son una serie de marcas pequeñas pero distintas legibles por máquina. Permite solo valores numéricos de 0 a 255. |

## Ejemplos

Este ejemplo muestra cómo cambiar el modo de símbolo Aztec y guardar una imagen BarCode.

```csharp
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

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


