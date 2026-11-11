---
title: "Pdf417Parameters.MacroCharacters"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Pdf417Parameters egenskap. Macro Characters 05 och 06 värden används för att få en mer kompakt kodning i speciella lägen. Kan endast användas med MicroPdf417 och kodar 916 och 917 MicroPdf417-lägen. Standardvärde MacroCharacters.None"
type: docs
weight: 90
url: /sv/net/aspose.barcode.generation/pdf417parameters/macrocharacters/
---
## Pdf417Parameters.MacroCharacters property

Macro Characters 05 och 06 värden används för att erhålla en mer kompakt kodning i speciella lägen. Kan endast användas med MicroPdf417 och kodar 916 och 917 MicroPdf417-lägen. Standardvärde: MacroCharacters.None.

```csharp
public MacroCharacter MacroCharacters { get; set; }
```

## Exempel

Dessa exempel visar hur man kodar Macro Characters i MicroPdf417

```csharp
[C#]
//Kodar MicroPdf417 med 05 Macro strängen: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Kodar MicroPdf417 med 06 Macro strängen: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### Se även

* enum [MacroCharacter](../../macrocharacter/)
* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


