---
title: "enum"
linktitle: "MacroCharacter"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " enum. Macro Characters 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi. 05 Macro‑karakter wordt vertaald naar \"[)>\\u001E05\\u001D\" als gedecodeerde gegevensheader en \"\\u001E\\u0004\" als gedecodeerde gegevenstrailer. 06 Macro‑karakter wordt vertaald naar \"[)>\\u001E06\\u001D\" als gedecodeerde gegevensheader en \"\\u001E\\u0004\" als gedecodeerde gegevenstrailer in C++."
type: docs
weight: 7300
url: /nl/cpp/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enum


Macro‑tekens 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi. Macro‑teken 05 wordt vertaald naar "[)>\u001E05\u001D" als gedecodeerde gegevensheader en "\u001E\u0004" als gedecodeerde gegevenstrailer. Macro‑teken 06 wordt vertaald naar "[)>\u001E06\u001D" als gedecodeerde gegevensheader en "\u001E\u0004" als gedecodeerde gegevenstrailer.

```cpp
enum class MacroCharacter
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Geen | 0 | Geen van de Macro Characters worden toegevoegd aan de barcode‑gegevens. |
| Macro05 | 5 | 05 Macro‑karakter wordt toegevoegd aan de barcode‑gegevens op de eerste positie. GS1 Data Identifier ISO 15434‑teken wordt vertaald naar "[)>\u001E05\u001D" als gedecodeerde gegevensheader en "\u001E\u0004" als gedecodeerde gegevenstrailer. |
| Macro06 | 6 | 06 Macro‑karakter wordt toegevoegd aan de barcode‑gegevens op de eerste positie. ASC MH10 Data Identifier ISO 15434‑teken wordt vertaald naar "[)>\u001E06\u001D" als gedecodeerde gegevensheader en "\u001E\u0004" als gedecodeerde gegevenstrailer. |

## Opmerkingen


Deze voorbeelden laten zien hoe Macro Characters te coderen in MicroPdf417 en DataMatrix
```cpp
[C#]
//Om een automatisch geïdentificeerd GS1‑bericht te genereren zoals "(10)123ABC(10)123ABC" in ISO‑15434‑formaat, heb je nodig:
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Codeert MicroPdf417 met 05 Macro de tekenreeks: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Codeert MicroPdf417 met 06 Macro de tekenreeks: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
