---
title: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Royal Mail 2D Mailmark コードに埋め込まれたテキストをエンコードおよびデコードするクラス。

Mailmark2DCodetext 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| Mailmark2DCodetext() | Mailmark2DCodetext クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| upu_country_id | UPU カントリー ID を識別します。最大長さ: 4 文字。 |
| information_type_id | 各製品タイプの Royal Mail Mailmark バーコードペイロードを識別します。 |
| version_id | 各 Information Type ID に関連するバーコードバージョンを識別します。 |
| klass | アイテムのクラスを識別します。 |
| supply_chain_id | メール送信に関与する顧客のユニークなグループを識別します。<br/>            最大値: 9999999. |
| item_id | サプライチェーン ID 内のユニークなアイテムを識別します。<br/>            すべての Mailmark バーコードは ID を保持する必要があります<br/>            これにより少なくとも 90 日間ユニークに識別できます。<br/>            最大値: 99999999. |
| destination_post_code_and_dps | 配達先住所の郵便番号（DPS 含む）を含みます。<br/>            内陸の場合、郵便番号/DP は以下の文字数を含みます。<br/>            エリア (1 または 2 文字) 区 (1 または 2 文字)<br/>            セクター (1 文字) ユニット (2 文字) DPS (2 文字)。<br/>            郵便番号と DPS は有効な PAF® 形式に準拠している必要があります。 |
| rts_flag | 要求されている Return to Sender サービスのレベルを示すフラグです。 |
| return_to_sender_post_code | Return to Sender の郵便コードを含みますが、DPS は含みません。<br/>            DPS のない PC は PAF® 形式に準拠している必要があります。 |
| customer_content | 顧客が使用できるオプションのスペースです。 |
| customer_content_encode_mode | Datamatrix バーコードのエンコードモードです。<br/>            デフォルト値: EncodeMode.C40. |
| data_matrix_type | 2D Mailmark タイプは Data Matrix バーコードのサイズを定義します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| get_constructed_codetext() | Mailmark データからコードテキストを構築します。 |
| init_from_string(constructed_codetext) | 構築されたコードテキストから Mailmark データを初期化します。 |
| get_barcode_type() | バーコードのタイプを取得します。 |

### 関連項目

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

