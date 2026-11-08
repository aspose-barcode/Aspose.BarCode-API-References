---
title: "enum"
linktitle: "MacroCharacter"
second_title: "Aspose.BarCode for C++ API-referens"
description: " enum. Makrotecken 05 och 06 används för att få en mer kompakt kodning i speciella lägen. 05 Makrotecken översätts till \"[)>\\u001E05\\u001D\" som avkodad datatopp och \"\\u001E\\u0004\" som avkodad databotten. 06 Makrotecken översätts till \"[)>\\u001E06\\u001D\" som avkodad datatopp och \"\\u001E\\u0004\" som avkodad databotten i C++."
type: docs
weight: 7300
url: /sv/cpp/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enum


Macro-tecken 05 och 06 används för att få en mer kompakt kodning i speciallägen. 05 Macro-tecken översätts till "[)>\u001E05\u001D" som avkodad dataheader och "\u001E\u0004" som avkodad dataslutt. 06 Macro-tecken översätts till "[)>\u001E06\u001D" som avkodad dataheader och "\u001E\u0004" som avkodad dataslutt.

```cpp
enum class MacroCharacter
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Ingen | 0 | Inga makrotecken läggs till streckkodsdatan |
| Macro05 | 5 | 05 Makrotecken läggs till streckkodsdatan i första positionen. GS1 Data Identifier ISO 15434-tecken översätts till "[)>\u001E05\u001D" som avkodad datatopp och "\u001E\u0004" som avkodad databotten. |
| Macro06 | 6 | 06 Makrotecken läggs till streckkodsdatan i första positionen. ASC MH10 Data Identifier ISO 15434-tecken översätts till "[)>\u001E06\u001D" som avkodad datatopp och "\u001E\u0004" som avkodad databotten. |

## Anmärkningar


Dessa exempel visar hur man kodar makrotecken i MicroPdf417 och DataMatrix
```cpp
[C#]
//För att generera ett automatiskt identifierat GS1-meddelande som detta "(10)123ABC(10)123ABC" i ISO 15434-format krävs:
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Kodar MicroPdf417 med 05 Makro strängen: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Kodar MicroPdf417 med 06 Makro strängen: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
