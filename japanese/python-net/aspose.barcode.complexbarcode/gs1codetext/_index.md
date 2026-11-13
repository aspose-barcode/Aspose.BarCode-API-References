---
title: "GS1Codetext"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode.complexbarcode/gs1codetext/
---

## GS1Codetext class

GS1 コードテキストをエンコードおよびデコードするための、順序付けられた<br/>            アプリケーション識別子要素のシーケンスを表します。元の順序と繰り返しのアプリケーション識別子は保持されます。括弧表記は (AI)value(AI)value の形式です。<br/>            値内のリテラル開き括弧 '(' は \(; と記述する必要があります。これは唯一サポートされているエスケープシーケンスです。値内の閉じ括弧 ')' はエスケープする必要はありません。

GS1Codetext 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| GS1Codetext() | GS1Codetext クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| barcode_type | この GS1 コードテキストをエンコードするために使用されるバーコードタイプを取得または設定します。<br/>            サポートされているタイプは GS1Aztec、GS1CodablockF、GS1Code128、GS1DataMatrix、<br/>            GS1DotCode、GS1HanXin、GS1MicroPdf417、GS1QR および GS1 DataBar タイプです。<br/>            デフォルト値は GS1Code128 です。 |
| カウント | アプリケーション識別子要素の数を取得します。 |
| 要素 | 元の順序ですべての要素のコピーを取得します。 |
## Indexer
| 名前 | 説明 |
| :- | :- |
| [index] | 順序付けられたシーケンス内の位置で要素を取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| get_first(application_identifier) | Application Identifier の最初の値を取得します。 |
| get_all(application_identifier) | Application Identifier のすべての値を元の順序で取得します。 |
| add(application_identifier, value) | 検証済みの Application Identifier 要素を追加します。 |
| validate(value) | オブジェクトを構築せずに、形式 (AI)value(AI)value の括弧付き GS1 要素文字列を検証します。<br/>            値内のリテラル '(' は \( と記述する必要があります。その他のエスケープシーケンスはサポートされず、')' はエスケープする必要がありません。 |
| parse(value) | 形式 (AI)value(AI)value の括弧付き GS1 要素文字列を解析します。値内のリテラル<br/>            '(' は \( と記述する必要があります。その他のエスケープシーケンスはサポートされず、<br/>            ')' はエスケープする必要がありません。 |
| try_parse(value, result, validation_result) | 形式 (AI)value(AI)value の括弧付き GS1 要素文字列の解析を試み、構造化された検証エラーを返します。<br/>            値内のリテラル '(' は<br/>            \( と記述する必要があります。その他のエスケープシーケンスはサポートされず、')' はエスケープする必要がありません。 |
| get_constructed_codetext() | 形式 (AI)value(AI)value の括弧付き GS1 コードテキストを構築します。<br/>            値内のリテラル開き括弧は \( とエスケープされます。 |
| init_from_string(constructed_codetext) | 形式 (AI)value(AI)value の括弧付き GS1 コードテキストからこのインスタンスを初期化します。<br/>            提供されたコードテキストが正常に解析された後にのみ、既存の要素が置き換えられます。 |
| get_barcode_type() | この GS1 コードテキストをエンコードするために使用されるバーコードタイプを取得します。 |

### 関連項目

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

