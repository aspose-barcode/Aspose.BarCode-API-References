---
title: "Énumération MacroCharacter"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Énumération Aspose.BarCode.Generation.MacroCharacter. Les caractères macro 05 et 06 sont utilisés pour obtenir un encodage plus compact dans les modes spéciaux. Le caractère macro 05 est traduit en u001E05u001D comme en-tête de données décodées et u001Eu0004 comme pied de données décodées. Le caractère macro 06 est traduit en u001E06u001D comme en-tête de données décodées et u001Eu0004 comme pied de données décodées."
type: docs
weight: 1450
url: /fr/net/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enumeration

Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans les modes spéciaux. Le caractère macro 05 est traduit en "[)\u003e\u001e05\u001d" comme en-tête de données décodées et "\u001e\u0004" comme suffixe de données décodées. Le caractère macro 06 est traduit en "[)\u003e\u001e06\u001d" comme en-tête de données décodées et "\u001e\u0004" comme suffixe de données décodées.

```csharp
public enum MacroCharacter
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Aucun des caractères macro n'est ajouté aux données du code-barres |
| Macro05 | `5` | Le caractère macro 05 est ajouté aux données du code-barres en première position. Le caractère d'identifiant de données GS1 ISO 15434 est traduit en "[)&gt;\u001E05\u001D" comme en-tête de données décodées et "\u001E\u0004" comme pied de données décodées. |
| Macro06 | `6` | Le caractère macro 06 est ajouté aux données du code-barres en première position. Le caractère d'identifiant de données ASC MH10 ISO 15434 est traduit en "[)&gt;\u001E06\u001D" comme en-tête de données décodées et "\u001E\u0004" comme pied de données décodées. |

## Exemples

Ces exemples montrent comment encoder les caractères macro dans MicroPdf417 et DataMatrix

```csharp
[C#]
//Pour générer un message GS1 auto-identifié comme celui-ci "(10)123ABC(10)123ABC" au format ISO 15434, vous devez :
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);
    
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

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


