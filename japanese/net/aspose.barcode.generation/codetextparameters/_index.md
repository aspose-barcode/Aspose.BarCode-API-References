---
title: CodetextParameters
second_title: Aspose.BarCode for.NETAPIリファレンス
description: コードテキスト パラメータ
type: docs
weight: 840
url: /ja/net/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class

コードテキスト パラメータ。

```csharp
public class CodetextParameters
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Alignment](../../aspose.barcode.generation/codetextparameters/alignment/) { get; set; } | コード テキストの配置を取得または設定します。 デフォルト値: StringAlignment.Center. |
| [Color](../../aspose.barcode.generation/codetextparameters/color/) { get; set; } | 表示する CodeText の色を指定します。 デフォルト値: Color.Black. |
| [Font](../../aspose.barcode.generation/codetextparameters/font/) { get; } | 表示する CodeText のフォントを指定します。 デフォルト値: Arial 5pt レギュラー。 FontMode が FontMode.Auto に設定されている場合は無視されます。 |
| [FontMode](../../aspose.barcode.generation/codetextparameters/fontmode/) { get; set; } | FontMode を指定します。 FontMode が Auto に設定されている場合、フォント サイズは xDimension 値に基づいて自動的に計算されます。 特に AutoSizeMode.Nearest または AutoSizeMode.Interpolation. で FontMode.Auto を使用することをお勧めします。 デフォルト値: FontMode.Auto. |
| [Location](../../aspose.barcode.generation/codetextparameters/location/) { get; set; } | 表示する CodeText の場所を指定します。CodeLocation.None に設定すると、CodeText が非表示になります。 デフォルト値: 1D バーコードの場合は CodeLocation.Below、2D バーコードの場合は CodeLocation.None. |
| [NoWrap](../../aspose.barcode.generation/codetextparameters/nowrap/) { get; set; } | テキスト内のワード ラップ (改行) を指定します。 デフォルト値: false. |
| [Space](../../aspose.barcode.generation/codetextparameters/space/) { get; set; } | CodeText と BarCode の間のスペース[`Unit`](../unit/)value. デフォルト値: 2pt. EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon. では無視されます。 |
| [TwoDDisplayText](../../aspose.barcode.generation/codetextparameters/twoddisplaytext/) { get; set; } | 2D バーコードの codetext の代わりに表示されるテキスト。 用途: Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/codetextparameters/tostring/)() | これの人間が読める文字列表現を返します`CodetextParameters`. |

### 関連項目

* 名前空間 [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* 組み立て [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
