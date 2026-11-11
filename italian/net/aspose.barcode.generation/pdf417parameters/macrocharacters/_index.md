---
title: "Pdf417Parameters.MacroCharacters"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Pdf417Parameters proprietà. I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Può essere usato solo con MicroPdf417 e codifica le modalità 916 e 917 di MicroPdf417. Valore predefinito MacroCharacters.None"
type: docs
weight: 90
url: /it/net/aspose.barcode.generation/pdf417parameters/macrocharacters/
---
## Pdf417Parameters.MacroCharacters property

I valori dei Caratteri Macro 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Può essere usato solo con MicroPdf417 e codifica le modalità 916 e 917 di MicroPdf417. Valore predefinito: MacroCharacters.None.

```csharp
public MacroCharacter MacroCharacters { get; set; }
```

## Esempi

Questi esempi mostrano come codificare i Macro Characters in MicroPdf417

```csharp
[C#]
//Codifica MicroPdf417 con Macro 05 la stringa: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Codifica MicroPdf417 con Macro 06 la stringa: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### Vedi anche

* enum [MacroCharacter](../../macrocharacter/)
* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


