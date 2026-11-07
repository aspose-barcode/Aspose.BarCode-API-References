---
title: "enum"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " enum. Code128バーコードのエンコーディングモード。C++のCode 128仕様。"
type: docs
weight: 5900
url: /ja/cpp/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enum


Code128 バーコードのエンコーディングモード。Code 128

仕様。

```cpp
enum class Code128EncodeMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| 自動 | 0 | コードテキストを古典的な ISO 15417 モードでエンコードします。このモードはすべての通常の場合に使用すべきです。 |
| CodeA | 1 | コードテキストを 128A コードセットのみでエンコードします。 |
| CodeB | 2 | コードテキストを 128B コードセットのみでエンコードします。 |
| CodeC | 4 | コードテキストを 128C コードセットのみでエンコードします。 |
| CodeAB | 3 | コードテキストを 128A と 128B のコードセットのみでエンコードします。 |
| CodeAC | 5 | コードテキストを 128A と 128C のコードセットのみでエンコードします。 |
| CodeBC | 6 | コードテキストを 128B と 128C のコードセットのみでエンコードします。 |

## 備考


このコードは、さまざまなエンコーディングでコード 128 を生成する方法を示しています
```cpp
[C#]
//ISO 15417 エンコーディングでコード 128 を生成します
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//コード 128 をコードセット A エンコーディングのみで生成します
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
