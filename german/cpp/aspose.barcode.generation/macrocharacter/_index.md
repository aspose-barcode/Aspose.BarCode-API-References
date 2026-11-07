---
title: "enum"
linktitle: "MacroCharacter"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Enum. Die Makrozeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Codierung zu erhalten. Das 05‑Makrozeichen wird in \"[)>\\u001E05\\u001D\" als Header der dekodierten Daten und \"\\u001E\\u0004\" als Trailer der dekodierten Daten übersetzt. Das 06‑Makrozeichen wird in \"[)>\\u001E06\\u001D\" als Header der dekodierten Daten und \"\\u001E\\u0004\" als Trailer der dekodierten Daten in C++ übersetzt."
type: docs
weight: 7300
url: /de/cpp/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enum


Die Werte der Makrozeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Codierung zu erreichen. Das Makrozeichen 05 wird zu "[)>\u001E05\u001D" als dekodierter Datenkopf und "\u001E\u0004" als dekodierter Datentrailer übersetzt. Das Makrozeichen 06 wird zu "[)>\u001E06\u001D" als dekodierter Datenkopf und "\u001E\u0004" als dekodierter Datentrailer übersetzt.

```cpp
enum class MacroCharacter
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Keine | 0 | Keine Makrozeichen werden zu den Strichcode-Daten hinzugefügt. |
| Macro05 | 5 | Das 05‑Makrozeichen wird an erster Stelle zu den Strichcode-Daten hinzugefügt. Das GS1‑Datenkennzeichen ISO‑15434‑Zeichen wird in "[)>\u001E05\u001D" als Header der dekodierten Daten und "\u001E\u0004" als Trailer der dekodierten Daten übersetzt. |
| Macro06 | 6 | Das 06‑Makrozeichen wird an erster Stelle zu den Strichcode-Daten hinzugefügt. Das ASC‑MH10‑Datenkennzeichen ISO‑15434‑Zeichen wird in "[)>\u001E06\u001D" als Header der dekodierten Daten und "\u001E\u0004" als Trailer der dekodierten Daten übersetzt. |

## Hinweise


Diese Beispiele zeigen, wie Makrozeichen in MicroPdf417 und DataMatrix codiert werden.
```cpp
[C#]
//Um eine automatisch identifizierte GS1‑Nachricht wie "(10)123ABC(10)123ABC" im ISO‑15434‑Format zu erzeugen, benötigen Sie:
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);

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

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
