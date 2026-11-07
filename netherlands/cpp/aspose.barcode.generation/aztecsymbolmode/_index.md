---
title: "enum"
linktitle: "AztecSymbolMode"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " enum. Specificeert de Aztec-symboolmodus in C++."
type: docs
weight: 5400
url: /nl/cpp/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enum


Specificeert de Aztec-symboolmodus.

```cpp
enum class AztecSymbolMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | 0 | Specificeert om automatisch het beste symbool (Compact of Full-range) voor Aztec te kiezen. Dit is de standaardwaarde. |
| Compact | 1 | Specificeert het Compact-symbool voor Aztec. Het Aztec Compact-symbool staat alleen 1, 2, 3 of 4 lagen toe. |
| FullRange | 2 | Specificeert het Full-range-symbool voor Aztec. Het Aztec Full-range-symbool staat van 1 tot 32 lagen toe. |
| Rune | 3 | Specificeert het Rune-symbool voor Aztec. Aztec Runes zijn een reeks kleine maar onderscheidende machinaal leesbare tekens. Het staat alleen numerieke waarden van 0 tot 255 toe. |

## Opmerkingen


Dit voorbeeld toont hoe u de Aztec Symbol-modus kunt wijzigen en een [BarCode](../../aspose.barcode/) afbeelding kunt opslaan.
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

## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
