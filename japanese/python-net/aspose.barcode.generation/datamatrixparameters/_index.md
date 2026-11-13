---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

DataMatrix パラメータ。

DataMatrixParameters 型は次のメンバーを公開します：
## プロパティ
| 名前 | 説明 |
| :- | :- |
| ecc_type | Datamatrix の ECC タイプを取得または設定します。<br/>            デフォルト値: DataMatrixEccType.Ecc200. |
| version | Datamatrix のシンボルサイズを取得または設定します。<br/>            デフォルト値: Version.Auto. |
| encode_mode | Datamatrix バーコードのエンコードモードです。<br/>            デフォルト値: EncodeMode.Auto. |
| structured_append_barcode_id | Datamatrix バーコードの Structured Append モード用のバーコード ID。<br/>            デフォルト値: 0 |
| structured_append_barcodes_count | Datamatrix バーコードの Structured Append モード用のバーコード数。<br/>            デフォルト値: 0 |
| structured_append_file_id | Datamatrix バーコードの Structured Append モード用のファイル ID。<br/>            デフォルト値: 0 |
| is_reader_programming | リーダーにシンボル内のデータをリーダー初期化用のプログラミングとして解釈させるために使用します。<br/>            デフォルト値: false |
| macro_characters | マクロ文字 05 と 06 の値は、特別モードでよりコンパクトなエンコードを取得するために使用されます。<br/>            DataMatrixEccType.Ecc200 または DataMatrixEccType.EccAuto と併用できるのみです。<br/>            EncodeTypes.GS1DataMatrix では使用できません<br/>            デフォルト値: MacroCharacters.None. |
| aspect_ratio | 2D バーコードモジュールの高さ/幅比率。 |
| eci_encoding | ECI エンコーディングを取得または設定します。EncodeMode が Auto の場合に使用されます。<br/>            デフォルト値: ISO-8859-1 |

### 関連項目

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

