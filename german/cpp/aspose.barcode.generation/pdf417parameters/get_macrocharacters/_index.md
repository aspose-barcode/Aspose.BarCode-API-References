---
title: "Methode"
linktitle: "get_MacroCharacters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Methode. Macro Characters 05‑ und 06‑Werte werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erhalten. Kann nur mit MicroPdf417 verwendet werden und kodiert die Modi 916 und 917 von MicroPdf417. Standardwert: MacroCharacters.None in C++."
type: docs
weight: 3900
url: /de/cpp/aspose.barcode.generation/pdf417parameters/get_macrocharacters/
---
## Pdf417Parameters::get_MacroCharacters method


Macro Characters 05‑ und 06‑Werte werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erhalten. Kann nur mit MicroPdf417 verwendet werden und kodiert die Modi 916 und 917 von MicroPdf417. Standardwert: [MacroCharacters.None](../../barcodeclassifications/).

```cpp
MacroCharacter Aspose::BarCode::Generation::Pdf417Parameters::get_MacroCharacters() const
```

## Hinweise


Diese Beispiele zeigen, wie Macro Characters in MicroPdf417 kodiert werden.
```cpp
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

## Siehe auch

* Enum [MacroCharacter](../../macrocharacter/)
* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
