---
title: "USADriveIdCodetext"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

USA 運転免許証 PDF417 コードに埋め込まれたテキストをエンコードおよびデコードするクラス。

USADriveIdCodetext 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| USADriveIdCodetext() | USADriveIdCodetext クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| issuer_identification_number | この番号は発行管轄を一意に識別し、ISO<br/>            発行機関（AAMVA）に問い合わせることで取得できます。完全な6桁のIINをエンコードする必要があります。 |
| aamva_version_number | AAMVA バージョン番号 00-99 |
| jurisdiction_version_number | 管轄バージョン番号 00-99 |
| number_of_entries | サブファイルの数 00-99 |
| subfile_designator | 以下のサブファイル、タイプ、オフセット、長さに関する情報が含まれています。 <br/>            重要: タイプのみを設定すると、オフセットと長さは自動的に設定されます。 |
| mandatory_elements | カードの必須要素（フィールド） |
| optional_elements | カードのオプション要素（フィールド） |
| jurisdiction_specific_subfile | 管轄固有フィールド |
## メソッド
| 名前 | 説明 |
| :- | :- |
| get_constructed_codetext() | USA DL データからコードテキストを構築する |
| init_from_string(constructed_codetext) | コードテキストから USA DL オブジェクトを初期化する |
| get_barcode_type() | USA DL のバーコードタイプ（Pdf417）を返します |
| save_to_xml(stream) | XML に保存します |

### 関連項目

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

