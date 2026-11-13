---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode.complexbarcode/mailmarkcodetext/
---

## MailmarkCodetext class

4 状態 Royal Mailmark コードに埋め込まれたテキストをエンコードおよびデコードするクラス。

MailmarkCodetext 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| MailmarkCodetext() | MailmarkCodetext クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| format | "0" – Null または Test<br/>            "1" – 文字<br/>            "2" – 大文字 |
| version_id | 現在 "1" – Mailmark バーコード用 (0 と 2 から 9 と A から Z は将来の使用のために予備) |
| klass | "0" - Null または Test<br/>            "1" - 1C（小売）<br/>            "2" - 2C（小売）<br/>            "3" - 3C（小売）<br/>            "4" - Premium（RetailPublishing Mail）（将来の使用のための予備）<br/>            "5" - Deferred（小売）<br/>            "6" - Air（小売）（将来の使用のための予備）<br/>            "7" - Surface（小売）（将来の使用のための予備）<br/>            "8" - Premium（ネットワークアクセス）<br/>            "9" - Standard（ネットワークアクセス） |
| supply_chain_id | Barcode C の最大値は 99、Barcode L の最大値は 999999 です。 |
| item_id | 最大値は 99999999 です。 |
| destination_post_code_and_dps | PC と DP は PAF 形式に準拠する必要があります。<br/>            国際的な "XY11     " を示す 9 文字の文字列（末尾のスペース 5 個に注意）またはパターン<br/>            の文字列で国内の仕分けコードを示します。<br/>            国内の仕分けコードは、外側郵便番号、内側郵便番号、そして配達ポイントサフィックスで構成されます。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| get_constructed_codetext() | Mailmark データからコードテキストを構築します。 |
| init_from_string(constructed_codetext) | 構築されたコードテキストから Mailmark データを初期化します。 |
| get_barcode_type() | バーコードのタイプを取得します。 |

### 関連項目

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

