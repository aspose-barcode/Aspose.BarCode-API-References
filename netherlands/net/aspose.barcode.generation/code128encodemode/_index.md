---
title: "Enum Code128EncodeMode"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.Code128EncodeMode enum. Coderingmodus voor Code128-barcode. Code 128-specificatie"
type: docs
weight: 1120
url: /nl/net/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enumeration

Coderingsmodus voor Code128-barcode. [Code 128](https://en.wikipedia.org/wiki/Code_128) specificatie.

```csharp
public enum Code128EncodeMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | `0` | Codeer de codetekst in de klassieke ISO 15417-modus. Deze modus moet in alle gewone gevallen worden gebruikt. |
| CodeA | `1` | Codeer de codetekst alleen in de 128A-codeset. |
| CodeB | `2` | Codeer de codetekst alleen in de 128B-codeset. |
| CodeC | `4` | Codeer de codetekst alleen in de 128C-codeset. |
| CodeAB | `3` | Codeer de codetekst alleen in de 128A- en 128B-codesets. |
| CodeAC | `5` | Codeer de codetekst alleen in de 128A- en 128C-codesets. |
| CodeBC | `6` | Codeer de codetekst alleen in de 128B- en 128C-codesets. |

## Voorbeelden

Deze code toont hoe code 128 met verschillende coderingen te genereren

```csharp
[C#]
//Genereer code 128 met ISO 15417-codering
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Genereer code 128 alleen met Codeset A-codering
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


