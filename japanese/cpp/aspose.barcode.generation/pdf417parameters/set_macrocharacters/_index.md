---
title: "メソッド"
linktitle: "set_MacroCharacters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。Macro Characters 05 と 06 の値は、特別なモードでよりコンパクトなエンコードを実現するために使用されます。MicroPdf417 でのみ使用でき、916 および 917 の MicroPdf417 モードをエンコードします。デフォルト値: MacroCharacters.None in C++."
type: docs
weight: 4000
url: /ja/cpp/aspose.barcode.generation/pdf417parameters/set_macrocharacters/
---
## Pdf417Parameters::set_MacroCharacters method


Macro Characters 05 と 06 の値は、特別なモードでよりコンパクトなエンコードを実現するために使用されます。MicroPdf417 でのみ使用でき、916 および 917 の MicroPdf417 モードをエンコードします。デフォルト値: [MacroCharacters.None](../../barcodeclassifications/)。

```cpp
void Aspose::BarCode::Generation::Pdf417Parameters::set_MacroCharacters(MacroCharacter value)
```

## 備考


これらのサンプルは、MicroPdf417 で Macro Characters をエンコードする方法を示しています
```cpp
[C#]
//05 マクロを使用して MicroPdf417 をエンコードする文字列: \"[)>\\u001E05\\u001Dabcde1234\\u001E\\u0004\"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//06 マクロを使用して MicroPdf417 をエンコードする文字列: \"[)>\\u001E06\\u001Dabcde1234\\u001E\\u0004\"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## 関連項目

* Enum [MacroCharacter](../../macrocharacter/)
* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
