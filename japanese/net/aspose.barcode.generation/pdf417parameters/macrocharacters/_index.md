---
title: "Pdf417Parameters.MacroCharacters"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Pdf417Parameters プロパティ。マクロ文字 05 と 06 の値は、特別なモードでよりコンパクトなエンコードを実現するために使用されます。MicroPdf417 と併用でき、916 と 917 の MicroPdf417 モードをエンコードします。既定値 MacroCharacters.None"
type: docs
weight: 90
url: /ja/net/aspose.barcode.generation/pdf417parameters/macrocharacters/
---
## Pdf417Parameters.MacroCharacters property

Macro Characters の 05 と 06 の値は、特別なモードでよりコンパクトなエンコーディングを得るために使用されます。MicroPdf417 でのみ使用でき、916 および 917 MicroPdf417 モードをエンコードします。デフォルト値: MacroCharacters.None。

```csharp
public MacroCharacter MacroCharacters { get; set; }
```

## 例

これらのサンプルは、MicroPdf417 でマクロ文字をエンコードする方法を示しています。

```csharp
[C#]
//MicroPdf417 を 05 マクロでエンコードします。文字列: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//MicroPdf417 を 06 マクロでエンコードし、文字列 "[)>\u001E06\u001Dabcde1234\u001E\u0004" を使用します
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### 関連項目

* enum [MacroCharacter](../../macrocharacter/)
* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


