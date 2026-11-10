---
title: "Pdf417Parameters.MacroCharacters"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Pdf417Parameters-Eigenschaft. Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erreichen. Kann nur mit MicroPdf417 verwendet werden und kodiert die Modi 916 und 917 von MicroPdf417. Standardwert: MacroCharacters.None."
type: docs
weight: 90
url: /de/net/aspose.barcode.generation/pdf417parameters/macrocharacters/
---
## Pdf417Parameters.MacroCharacters property

Macro‑Zeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erhalten. Können nur mit MicroPdf417 verwendet werden und kodieren die Modi 916 und 917 von MicroPdf417. Standardwert: MacroCharacters.None.

```csharp
public MacroCharacter MacroCharacters { get; set; }
```

## Beispiele

Diese Beispiele zeigen, wie Makro‑Zeichen in MicroPdf417 kodiert werden.

```csharp
[C#]
//Kodiert MicroPdf417 mit 05‑Makro die Zeichenkette: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Kodiert MicroPdf417 mit 06‑Makro die Zeichenkette: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### Siehe auch

* enum [MacroCharacter](../../macrocharacter/)
* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


