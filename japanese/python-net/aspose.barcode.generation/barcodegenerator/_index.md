---
title: "BarcodeGenerator"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode.generation/barcodegenerator/
---

## BarcodeGenerator class

バックエンドのバーコード画像生成のための BarcodeGenerator。

BarcodeGenerator 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| BarcodeGenerator(type) | BarcodeGenerator クラスの新しいインスタンスを初期化します |
| BarcodeGenerator(type, code_text) | BarcodeGenerator クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| parameters | 生成パラメータ。 |
| barcode_type | バーコードシンボロジーのタイプ。 |
| code_text | エンコードするテキスト。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| set_code_text(code_bytes) | コードテキストをバイト列として設定します。 |
| set_code_text(code_text, encoding) |  |
| set_code_text(code_text, encoding, insert_bom) |  |
| save(stream, format) | バーコード画像を特定の形式でストリームに保存します。 |
| save(filename, format) | バーコード画像を特定の形式で特定のファイルに保存します。 |
| save(filename) | バーコード画像を特定の形式で特定のファイルに保存します。 |
| export_to_xml(xml_file) | 指定された XML ファイルに BarCode プロパティをエクスポートします |
| export_to_xml(xml) | 指定された XML ストリームに BarCode プロパティをエクスポートします |
| import_from_xml(xml_file) | 指定された XML ファイルから BarCode プロパティをインポートし、BarcodeGenerator インスタンスを作成します。 |
| import_from_xml(xml) | 指定された XML ストリームから BarCode プロパティをインポートし、BarcodeGenerator インスタンスを作成します。 |
| generate_bar_code_image() | 現在の設定でバーコード画像を生成します。 |

### 関連項目

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

