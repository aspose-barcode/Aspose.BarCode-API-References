---
title: "AztecParameters"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode.generation/aztecparameters/
---

## AztecParameters class

Aztec パラメータ。

AztecParameters 型は次のメンバーを公開します:
## プロパティ
| 名前 | 説明 |
| :- | :- |
| encode_mode | Aztec エンコードモードを取得または設定します。 <br/>            デフォルト値: Auto. |
| eci_encoding | ECI エンコーディングを取得または設定します。AztecEncodeMode が Auto の場合に使用されます。<br/>            デフォルト値: ISO-8859-1 |
| structured_append_barcode_id | Aztec バーコードの Structured Append モード用のバーコード ID。バーコード ID は 1 からバーコード数までの範囲である必要があります。<br/>            デフォルト値: 0 |
| structured_append_barcodes_count | Aztec バーコードの Structured Append モードのバーコード数。バーコード数は 1 から 26 の範囲である必要があります。<br/>            デフォルト値: 0 |
| structured_append_file_id | Aztec バーコードの Structured Append モードのファイル ID（オプションフィールド）。ファイル ID にスペースを含めてはいけません。<br/>            デフォルト値: 空文字列 |
| error_level | Aztec タイプのバーコードの誤り訂正レベル。<br/>            値は 5 から 95 の間である必要があります。 |
| symbol_mode | Aztec Symbol モードを取得または設定します。<br/>            デフォルト値: AztecSymbolMode.Auto. |
| layers_count | Aztec シンボルのレイヤー数を取得または設定します。レイヤー数は Compact モードの場合 1 から 3、Full Range モードの場合 1 から 32 の範囲である必要があります。<br/>            デフォルト値: 0（自動）。 |
| is_reader_initialization | リーダーにシンボル内に含まれるデータをリーダー初期化用のプログラミングとして解釈させるために使用されます。<br/>             |
| aspect_ratio | 2D バーコードモジュールの高さ/幅比率。 |

### 関連項目

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

