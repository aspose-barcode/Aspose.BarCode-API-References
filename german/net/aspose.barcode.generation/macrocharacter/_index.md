---
title: "Enum MacroCharacter"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.MacroCharacter Enum. Makrozeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erreichen. Das Makrozeichen 05 wird zu u001E05u001D als dekodierter Datenkopf und u001Eu0004 als dekodierter Datentrailer übersetzt. Das Makrozeichen 06 wird zu u001E06u001D als dekodierter Datenkopf und u001Eu0004 als dekodierter Datentrailer übersetzt."
type: docs
weight: 1450
url: /de/net/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enumeration

Makrozeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erreichen. Das Makrozeichen 05 wird zu "[)&gt;\u001E05\u001D" als dekodierter Datenkopf und "\u001E\u0004" als dekodierter Datentrailer übersetzt. Das Makrozeichen 06 wird zu "[)&gt;\u001E06\u001D" als dekodierter Datenkopf und "\u001E\u0004" als dekodierter Datentrailer übersetzt.

```csharp
public enum MacroCharacter
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Keines der Makrozeichen wird zu den Barcode-Daten hinzugefügt. |
| Macro05 | `5` | Das Makrozeichen 05 wird an erster Stelle zu den Barcode-Daten hinzugefügt. Das GS1-Datenkennzeichen ISO‑15434‑Zeichen wird zu "[)&gt;\u001E05\u001D" als dekodierter Datenkopf und "\u001E\u0004" als dekodierter Datentrailer übersetzt. |
| Macro06 | `6` | Das Makrozeichen 06 wird an erster Stelle zu den Barcode-Daten hinzugefügt. Das ASC‑MH10‑Datenkennzeichen ISO‑15434‑Zeichen wird zu "[)&gt;\u001E06\u001D" als dekodierter Datenkopf und "\u001E\u0004" als dekodierter Datentrailer übersetzt. |

## Beispiele

Diese Beispiele zeigen, wie man Makrozeichen in MicroPdf417 und DataMatrix kodiert.

```csharp
[C#]
//Um eine automatisch identifizierte GS1-Nachricht wie "(10)123ABC(10)123ABC" im ISO‑15434‑Format zu erzeugen, benötigen Sie:
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

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


