---
title: "enum"
linktitle: "AztecSymbolMode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " enum. C++ で Aztec シンボルモードを指定します。"
type: docs
weight: 5400
url: /ja/cpp/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enum


Aztec シンボルモードを指定します。

```cpp
enum class AztecSymbolMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| 自動 | 0 | Aztec 用に最適なシンボル（Compact または Full-range）を自動的に選択するように指定します。これがデフォルト値です。 |
| Compact | 1 | Aztec の Compact シンボルを指定します。Aztec Compact シンボルは 1、2、3、または 4 層のみ許可します。 |
| FullRange | 2 | Aztec の Full-range シンボルを指定します。Aztec Full-range シンボルは 1 から 32 層まで許可します。 |
| Rune | 3 | Aztec の Rune シンボルを指定します。Aztec Runes は小さくても区別できる機械可読マークのシリーズです。0 から 255 の数値のみ許可します。 |

## 備考


このサンプルは Aztec Symbol モードを変更し、[BarCode](../../aspose.barcode/) 画像を保存する方法を示しています。
```cpp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.CodeText = "125";
    generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune;
    generator.Save("test.png");
}
    [VB.NET]
    Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec)
        generator.CodeText = "125"
        generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune
        generator.Save("test.png")
    End Using
```

## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
