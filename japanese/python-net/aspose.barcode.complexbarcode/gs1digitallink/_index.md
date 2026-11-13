---
title: "GS1DigitalLink"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode.complexbarcode/gs1digitallink/
---

## GS1DigitalLink class

GS1 Digital Link コードテキストをエンコードおよびデコードするための、順序付けられた<br/>            アプリケーション識別子要素のシーケンスを表します。元の順序と繰り返しのアプリケーション識別子は保持されます。<br/>            作成されたコードテキストは圧縮されていない GS1 Digital Link URI です。<br/>            解析時に非 GS1 のクエリパラメータや URI フラグメントは無視されます。

GS1DigitalLink 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| GS1DigitalLink(uri_stem) | GS1DigitalLink クラスの新しいインスタンスを初期化します |
| GS1DigitalLink(uri_stem, primary_application_identifier) | GS1DigitalLink クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| uri_stem | GS1 のプライマリキー パス セグメントの前の絶対 URI プレフィックスを取得します。<br/>            ステムにはクエリ文字列やフラグメントが含まれません。 |
| primary_application_identifier | Digital Link のプライマリキーとして使用されるアプリケーション識別子を取得します。<br/>            null は、URI が構築されるときにプライマリキーが自動的に選択されることを意味します。 |
| barcode_type | この GS1 Digital Link をエンコードするために使用されるバーコードタイプを取得または設定します。<br/>            サポートされているタイプは QR、DataMatrix、Aztec、Pdf417、MicroPdf417、DotCode、HanXin、CodablockF、Code128 です。<br/>            デフォルト値は QR です。 |
| カウント | アプリケーション識別子要素の数を取得します。 |
| 要素 | 元の順序ですべての要素のコピーを取得します。 |
## Indexer
| 名前 | 説明 |
| :- | :- |
| [index] | 順序付けられたシーケンス内の位置で要素を取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| create(uri_stem, codetext) | GS1 codetext からすべての要素をコピーし、唯一利用可能なプライマリキーを選択して<br/>            GS1 Digital Link を作成します。 |
| create(uri_stem, codetext, primary_application_identifier) | GS1 codetext からすべての要素をコピーし、唯一利用可能なプライマリキーを選択して<br/>            GS1 Digital Link を作成します。 |
| get_first(application_identifier) | Application Identifier の最初の値を取得します。 |
| get_all(application_identifier) | Application Identifier のすべての値を元の順序で取得します。 |
| add(application_identifier, value) | 検証済みの Application Identifier 要素を追加します。 |
| validate(value) | オブジェクトを構築せずに、圧縮されていない GS1 Digital Link URI を検証します。 |
| parse(value) | 圧縮されていない GS1 Digital Link URI を解析します。 |
| try_parse(value, result, validation_result) | 圧縮されていない GS1 Digital Link URI の解析を試み、構造化された検証エラーを返します。 |
| to_gs1_codetext() | 現在の GS1 要素を含む独立した GS1 codetext を作成します。<br/>            URI のみの情報は含まれません。 |
| to_uri_string() | 現在のオブジェクト状態を圧縮されていない GS1 Digital Link URI としてフォーマットします。 |
| get_constructed_codetext() | 圧縮されていない GS1 Digital Link URI を構築します。 |
| init_from_string(constructed_codetext) | 圧縮されていない GS1 Digital Link URI からこのインスタンスを初期化します。<br/>            供給された URI が正常に解析された後にのみ、既存の状態が置き換えられます。<br/>            選択されたバーコードタイプは保持されます。 |
| get_barcode_type() | この GS1 Digital Link をエンコードするために使用されるバーコードタイプを取得します。 |

### 関連項目

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

