---
title: "method"
linktitle: "set_MacroCharacters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " method. I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Può essere usato solo con MicroPdf417 e codifica le modalità MicroPdf417 916 e 917 Valore predefinito: MacroCharacters.None in C++."
type: docs
weight: 4000
url: /it/cpp/aspose.barcode.generation/pdf417parameters/set_macrocharacters/
---
## Pdf417Parameters::set_MacroCharacters method


I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Può essere usato solo con MicroPdf417 e codifica le modalità MicroPdf417 916 e 917 Valore predefinito: [MacroCharacters.None](../../barcodeclassifications/).

```cpp
void Aspose::BarCode::Generation::Pdf417Parameters::set_MacroCharacters(MacroCharacter value)
```

## Osservazioni


Questi esempi mostrano come codificare i Macro Characters in MicroPdf417
```cpp
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

## Vedi anche

* Enum [MacroCharacter](../../macrocharacter/)
* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
