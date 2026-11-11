---
title: "列挙体 Code128EncodeMode"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.Generation.Code128EncodeMode 列挙体。Code128 バーコードのエンコーディングモード。Code 128 仕様。"
type: docs
weight: 1120
url: /ja/net/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enumeration

Code128 バーコードのエンコーディングモード。[Code 128](https://en.wikipedia.org/wiki/Code_128) 仕様。

```csharp
public enum Code128EncodeMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Auto | `0` | コードテキストをクラシック ISO 15417 モードでエンコードします。このモードはすべての通常の場合に使用すべきです。 |
| CodeA | `1` | コードテキストを 128A コードセットのみでエンコードします。 |
| CodeB | `2` | コードテキストを 128B コードセットのみでエンコードします。 |
| CodeC | `4` | コードテキストを 128C コードセットのみでエンコードします。 |
| CodeAB | `3` | コードテキストを 128A と 128B のコードセットのみでエンコードします。 |
| CodeAC | `5` | コードテキストを 128A と 128C のコードセットのみでエンコードします。 |
| CodeBC | `6` | コードテキストを 128B と 128C のコードセットのみでエンコードします。 |

## 例

このコードは、異なるエンコーディングでコード 128 を生成する方法を示しています。

```csharp
[C#]
//ISO 15417 エンコーディングでコード 128 を生成します。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//コード 128 をコードセット A エンコーディングのみで生成します。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

### 関連項目

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


