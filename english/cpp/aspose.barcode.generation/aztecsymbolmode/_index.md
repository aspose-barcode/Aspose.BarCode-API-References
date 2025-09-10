---
title: Aspose::BarCode::Generation::AztecSymbolMode enum
linktitle: AztecSymbolMode
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::AztecSymbolMode enum. Specifies the Aztec symbol mode in C++.'
type: docs
weight: 4600
url: /cpp/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enum


Specifies the Aztec symbol mode.

```cpp
enum class AztecSymbolMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | 0 | Specifies to automatically pick up the best symbol (Compact or Full-range) for Aztec. This is default value. |
| Compact | 1 | Specifies the Compact symbol for Aztec. Aztec Compact symbol permits only 1, 2, 3 or 4 layers. |
| FullRange | 2 | Specifies the Full-range symbol for Aztec. Aztec Full-range symbol permits from 1 to 32 layers. |
| Rune | 3 | Specifies the Rune symbol for Aztec. Aztec Runes are a series of small but distinct machine-readable marks. It permits only number value from 0 to 255. |

## Remarks


This sample shows how to change Aztec Symbol mode and save a [BarCode](../../aspose.barcode/) image. 
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

## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
