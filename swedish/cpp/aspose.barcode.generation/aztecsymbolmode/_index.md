---
title: "enum"
linktitle: "AztecSymbolMode"
second_title: "Aspose.BarCode for C++ API-referens"
description: " enum. Anger Aztec-symbolläget i C++."
type: docs
weight: 5400
url: /sv/cpp/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enum


Anger Aztec-symbolläget.

```cpp
enum class AztecSymbolMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | 0 | Anger att automatiskt välja den bästa symbolen (Compact eller Full-range) för Aztec. Detta är standardvärdet. |
| Compact | 1 | Anger den kompakta symbolen för Aztec. Aztec Compact-symbol tillåter endast 1, 2, 3 eller 4 lager. |
| FullRange | 2 | Anger Full-range-symbolen för Aztec. Aztec Full-range-symbol tillåter från 1 till 32 lager. |
| Rune | 3 | Anger Rune-symbolen för Aztec. Aztec Runes är en serie av små men distinkta maskinläsbara märken. Den tillåter endast numeriska värden från 0 till 255. |

## Anmärkningar


Detta exempel visar hur man ändrar Aztec Symbol-läget och sparar en [BarCode](../../aspose.barcode/) bild.
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

## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
