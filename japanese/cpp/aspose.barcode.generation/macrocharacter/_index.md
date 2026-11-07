---
title: "enum"
linktitle: "MacroCharacter"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "列挙型。マクロ文字 05 と 06 の値は、特殊モードでよりコンパクトなエンコーディングを取得するために使用されます。05 マクロ文字はデコードされたデータヘッダーとして \\\"[)>\\\\u001E05\\\\u001D\\\" に、デコードされたデータトレーラーとして \\\"\\\\u001E\\\\u0004\\\" に変換されます。06 マクロ文字はデコードされたデータヘッダーとして \\\"[)>\\\\u001E06\\\\u001D\\\" に、デコードされたデータトレーラーとして \\\"\\\\u001E\\\\u0004\\\" に変換され、C++ で使用されます。"
type: docs
weight: 7300
url: /ja/cpp/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enum


マクロ文字 05 と 06 の値は、特別モードでよりコンパクトなエンコードを取得するために使用されます。05 マクロ文字はデコードデータヘッダーとして "[)>\u001E05\u001D" に、デコードデータトレーラーとして "\u001E\u0004" に変換されます。06 マクロ文字はデコードデータヘッダーとして "[)>\u001E06\u001D" に、デコードデータトレーラーとして "\u001E\u0004" に変換されます。

```cpp
enum class MacroCharacter
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| なし | 0 | マクロ文字はバーコードデータに追加されません |
| Macro05 | 5 | 05 マクロ文字はバーコードデータの最初の位置に追加されます。GS1 データ識別子 ISO 15434 文字はデコードされたデータヘッダーとして \"[)>\\u001E05\\u001D\" に、デコードされたデータトレーラーとして \"\\u001E\\u0004\" に変換されます。 |
| Macro06 | 6 | 06 マクロ文字はバーコードデータの最初の位置に追加されます。ASC MH10 データ識別子 ISO 15434 文字はデコードされたデータヘッダーとして \"[)>\\u001E06\\u001D\" に、デコードされたデータトレーラーとして \"\\u001E\\u0004\" に変換されます。 |

## 備考


これらのサンプルは MicroPdf417 と DataMatrix でマクロ文字をエンコードする方法を示します
```cpp
[C#]
//ISO 15434 形式で \"(10)123ABC(10)123ABC\" のような自動識別 GS1 メッセージを生成するには、次が必要です:
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);

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

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
