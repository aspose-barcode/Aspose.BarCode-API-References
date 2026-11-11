---
title: "Enum MacroCharacter"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.MacroCharacter enum. Macro‑karakters 05 en 06 worden gebruikt om een compactere codering te verkrijgen in speciale modi. Macro‑karakter 05 wordt vertaald naar u001E05u001D als gedecodeerde gegevensheader en u001Eu0004 als gedecodeerde gegevenstrailer. Macro‑karakter 06 wordt vertaald naar u001E06u001D als gedecodeerde gegevensheader en u001Eu0004 als gedecodeerde gegevenstrailer."
type: docs
weight: 1450
url: /nl/net/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enumeration

Macro‑tekens 05 en 06 worden gebruikt om een compactere codering te verkrijgen in speciale modi. Macro‑teken 05 wordt vertaald naar "[)&gt;\u001E05\u001D" als gedecodeerde gegevenskop en "\u001E\u0004" als gedecodeerde gegevenstailer. Macro‑teken 06 wordt vertaald naar "[)&gt;\u001E06\u001D" als gedecodeerde gegevenskop en "\u001E\u0004" als gedecodeerde gegevenstailer.

```csharp
public enum MacroCharacter
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | `0` | Geen van de macro‑karakters worden toegevoegd aan de barcode‑gegevens. |
| Macro05 | `5` | Macro‑karakter 05 wordt toegevoegd aan de barcode‑gegevens op de eerste positie. GS1‑gegevensidentificator ISO 15434‑teken wordt vertaald naar "[)&gt;\u001E05\u001D" als gedecodeerde gegevensheader en "\u001E\u0004" als gedecodeerde gegevenstrailer. |
| Macro06 | `6` | Macro‑karakter 06 wordt toegevoegd aan de barcode‑gegevens op de eerste positie. ASC MH10‑gegevensidentificator ISO 15434‑teken wordt vertaald naar "[)&gt;\u001E06\u001D" als gedecodeerde gegevensheader en "\u001E\u0004" als gedecodeerde gegevenstrailer. |

## Voorbeelden

Deze voorbeelden tonen hoe macro‑karakters te coderen in MicroPdf417 en DataMatrix

```csharp
[C#]
//Om een automatisch geïdentificeerd GS1‑bericht zoals "(10)123ABC(10)123ABC" in ISO 15434‑formaat te genereren, heb je nodig:
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);
    
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

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


