---
title: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

HIBC LIC の二次データおよび追加データを保存するクラス。

SecondaryAndAdditionalData 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| SecondaryAndAdditionalData() | SecondaryAndAdditionalData クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| expiry_date_format | 有効期限の日付形式を識別します。 |
| expiry_date | 有効期限の日付を識別します。ExpiryDateFormat が None に設定されていない場合に使用されます。 |
| lot_number | ロットまたはバッチ番号を識別します。ロット/バッチ番号は最大18文字の英数字文字列である必要があります。 |
| serial_number | シリアル番号を識別します。シリアル番号は最大18文字の英数字文字列である必要があります。 |
| date_of_manufacture | 製造日を識別します。<br/>            製造日はこのフィールドを使用しない場合、DateTime.MinValue に設定できます。<br/>            デフォルト値: DateTime.MinValue |
| quantity | 数量を識別します。0から500までの整数値である必要があります。 <br/>            フィールドを使用しない場合、数量を -1 に設定できます。<br/>            デフォルト値: -1 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| parse_from_string(secondary_data_codetext) | HIBC LIC 仕様に従い、文字列形式から二次および追加の補足データをインスタンス化します。 |

### 関連項目

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

