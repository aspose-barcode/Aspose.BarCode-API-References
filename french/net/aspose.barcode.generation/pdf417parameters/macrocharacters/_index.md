---
title: "Pdf417Parameters.MacroCharacters"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété Pdf417Parameters. Les valeurs Macro Characters 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. Peut être utilisé uniquement avec MicroPdf417 et encode les modes 916 et 917 MicroPdf417. Valeur par défaut MacroCharacters.None"
type: docs
weight: 90
url: /fr/net/aspose.barcode.generation/pdf417parameters/macrocharacters/
---
## Pdf417Parameters.MacroCharacters property

Les valeurs des caractères Macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. Elles ne peuvent être utilisées qu'avec MicroPdf417 et encodent les modes MicroPdf417 916 et 917. Valeur par défaut : MacroCharacters.None.

```csharp
public MacroCharacter MacroCharacters { get; set; }
```

## Exemples

Ces exemples montrent comment encoder les Macro Characters dans MicroPdf417

```csharp
[C#]
//Encode MicroPdf417 avec le macro 05 la chaîne : "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Encode MicroPdf417 avec le macro 06 la chaîne : "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### Voir aussi

* enum [MacroCharacter](../../macrocharacter/)
* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


