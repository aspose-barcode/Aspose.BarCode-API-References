---
title: "Pdf417Parameters.MacroCharacters"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Pdf417Parameters eigenschap. Macro‑karakters 05 en 06 worden gebruikt om een compactere codering te verkrijgen in speciale modi. Alleen bruikbaar met MicroPdf417 en codeert 916‑ en 917‑MicroPdf417‑modi. Standaardwaarde MacroCharacters.None"
type: docs
weight: 90
url: /nl/net/aspose.barcode.generation/pdf417parameters/macrocharacters/
---
## Pdf417Parameters.MacroCharacters property

Macro-tekens 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi. Kan alleen worden gebruikt met MicroPdf417 en codeert 916 en 917 MicroPdf417-modi. Standaardwaarde: MacroCharacters.None.

```csharp
public MacroCharacter MacroCharacters { get; set; }
```

## Voorbeelden

Deze voorbeelden laten zien hoe Macro‑karakters te coderen in MicroPdf417

```csharp
[C#]
//Encodeert MicroPdf417 met 05 Macro de tekenreeks: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Encodeert MicroPdf417 met 06 Macro de tekenreeks: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### Zie ook

* enum [MacroCharacter](../../macrocharacter/)
* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


