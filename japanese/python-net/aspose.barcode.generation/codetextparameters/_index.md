---
title: "CodetextParameters"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode.generation/codetextparameters/
---

## CodetextParameters class

Codetext パラメータ。

CodetextParameters 型は次のメンバーを公開します:
## プロパティ
| 名前 | 説明 |
| :- | :- |
| two_d_display_text | 2D バーコードでコードテキストの代わりに表示されるテキストです。<br/>            使用対象: Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode |
| font_mode | FontMode を指定します。FontMode が Auto に設定されている場合、フォントサイズは xDimension の値に基づいて自動的に計算されます。<br/>            特に AutoSizeMode.Nearest または AutoSizeMode.Interpolation で FontMode.Auto を使用することを推奨します。<br/>            デフォルト値: FontMode.Auto. |
| font | 表示される CodeText のフォントを指定します。<br/>            デフォルト値: Arial 5pt regular。<br/>            FontMode が FontMode.Auto に設定されている場合は無視されます。 |
| space | [Unit](/barcode/python-net/aspose.barcode.generation/unit/) の値で CodeText とバーコードの間のスペース。<br/>            デフォルト値: 2pt。<br/>            EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon では無視されます。 |
| 配置 | コードテキストの配置を取得または設定します。<br/>            デフォルト値: StringAlignment.Center. |
| 色 | 表示される CodeText の色を指定します。<br/>            デフォルト値: Color.Black. |
| 位置 | 表示される CodeText の位置を指定します。CodeLocation.None に設定すると CodeText が非表示になります。<br/>            デフォルト値: 1D バーコードの場合は CodeLocation.Below、2D バーコードの場合は CodeLocation.None。 |
| no_wrap | テキスト内の単語ラップ（改行）を指定します。<br/>            デフォルト値: false. |

### 関連項目

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

