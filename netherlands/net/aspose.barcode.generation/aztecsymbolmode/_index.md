---
title: "Enum AztecSymbolMode"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.AztecSymbolMode enum. Specificeert de Aztec-symboolmodus"
type: docs
weight: 970
url: /nl/net/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enumeration

Specificeert de Aztec-symboolmodus.

```csharp
public enum AztecSymbolMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | `0` | Specificeert om automatisch het beste symbool (Compact of Full-range) voor Aztec te kiezen. Dit is de standaardwaarde. |
| Compact | `1` | Specificeert het Compact-symbool voor Aztec. Het Compact-symbool van Aztec staat alleen 1, 2, 3 of 4 lagen toe. |
| FullRange | `2` | Specificeert het Full-range-symbool voor Aztec. Het Full-range-symbool van Aztec staat van 1 tot 32 lagen toe. |
| Rune | `3` | Specificeert het Rune-symbool voor Aztec. Aztec Runes zijn een reeks kleine maar onderscheidende machinaal leesbare tekens. Het staat alleen numerieke waarden van 0 tot 255 toe. |

## Voorbeelden

Dit voorbeeld toont hoe u de Aztec-symboolmodus wijzigt en een BarCode-afbeelding opslaat.

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

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


