---
title: Enum MacroCharacter
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.MacroCharacter enum. Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. 05 Macro craracter is translated to u001E05u001D as decoded data header and u001Eu0004 as decoded data trailer. 06 Macro craracter is translated to u001E06u001D as decoded data header and u001Eu0004 as decoded data trailer
type: docs
weight: 1330
url: /net/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enumeration

Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. 05 Macro craracter is translated to "[)&gt;\u001E05\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. 06 Macro craracter is translated to "[)&gt;\u001E06\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer.

```csharp
public enum MacroCharacter
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | None of Macro Characters are added to barcode data |
| Macro05 | `5` | 05 Macro craracter is added to barcode data in first position. GS1 Data Identifier ISO 15434 Character is translated to "[)&gt;\u001E05\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. |
| Macro06 | `6` | 06 Macro craracter is added to barcode data in first position. ASC MH10 Data Identifier ISO 15434 Character is translated to "[)&gt;\u001E06\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. |

## Examples

hese samples show how to encode Macro Characters in MicroPdf417 and DataMatrix

```csharp
[C#]
//to generate autoidentified GS1 message like this "(10)123ABC(10)123ABC" in ISO 15434 format you need:
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);
    
//Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Encodes MicroPdf417 with 06 Macro the string: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


