---
title: "Pdf417Parameters.MacroCharacters"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Pdf417Parameters 属性。宏字符 05 和 06 的取值用于在特殊模式下实现更紧凑的编码。仅可与 MicroPdf417 一起使用，并对 916 和 917 MicroPdf417 模式进行编码。默认值为 MacroCharacters.None。"
type: docs
weight: 90
url: /zh/net/aspose.barcode.generation/pdf417parameters/macrocharacters/
---
## Pdf417Parameters.MacroCharacters property

宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 MicroPdf417 一起使用，并对 916 和 917 MicroPdf417 模式进行编码。默认值：MacroCharacters.None。

```csharp
public MacroCharacter MacroCharacters { get; set; }
```

## 示例

以下示例展示了如何在 MicroPdf417 中编码宏字符。

```csharp
[C#]
//使用 05 宏对 MicroPdf417 进行编码，字符串为："[)>\\u001E05\\u001Dabcde1234\\u001E\\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//使用 06 宏对 MicroPdf417 进行编码，字符串为："[)>\\u001E06\\u001Dabcde1234\\u001E\\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### 另见

* enum [MacroCharacter](../../macrocharacter/)
* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


