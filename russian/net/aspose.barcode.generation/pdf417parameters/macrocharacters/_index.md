---
title: "Pdf417Parameters.MacroCharacters"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Свойство Pdf417Parameters. Значения Macro Characters 05 и 06 используются для получения более компактного кодирования в специальных режимах. Может использоваться только с MicroPdf417 и кодирует режимы 916 и 917 MicroPdf417. Значение по умолчанию MacroCharacters.None"
type: docs
weight: 90
url: /ru/net/aspose.barcode.generation/pdf417parameters/macrocharacters/
---
## Pdf417Parameters.MacroCharacters property

Значения Macro Characters 05 и 06 используются для получения более компактного кодирования в специальных режимах. Может использоваться только с MicroPdf417 и кодирует режимы MicroPdf417 916 и 917. Значение по умолчанию: MacroCharacters.None.

```csharp
public MacroCharacter MacroCharacters { get; set; }
```

## Примеры

Эти примеры показывают, как кодировать Macro Characters в MicroPdf417

```csharp
[C#]
//Кодирует MicroPdf417 с макросом 05 строку: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Кодирует MicroPdf417 с макросом 06 строку: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### См. также

* enum [MacroCharacter](../../macrocharacter/)
* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


