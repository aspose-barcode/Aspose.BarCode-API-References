---
title: "クラス GS1DigitalLink"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.ComplexBarcode.GS1DigitalLink クラス。GS1 Digital Link のコードテキストを、Application Identifier 要素の順序付けられたシーケンスとしてエンコードおよびデコードすることを表します。ソース順序と繰り返しの Application Identifier は保持されます。構築されたコードテキストは圧縮されていない GS1 Digital Link URI です。解析時には NonGS1 のクエリパラメータと URI フラグメントは無視されます。"
type: docs
weight: 540
url: /ja/net/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class

GS1 Digital Link のコードテキストを、Application Identifier 要素の順序付けられたシーケンスとしてエンコードおよびデコードすることを表します。ソース順序と繰り返しの Application Identifier は保持されます。構築されたコードテキストは圧縮されていない GS1 Digital Link URI です。解析時には Non-GS1 のクエリパラメータと URI フラグメントは無視されます。

```csharp
public sealed class GS1DigitalLink : IComplexCodetext
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [GS1DigitalLink](gs1digitallink/#constructor)(string) | 指定された URI ステムで空の GS1 Digital Link を初期化します。プライマリキーは、プライマリキー候補が正確に1つ存在する場合に自動的に選択されます。 |
| [GS1DigitalLink](gs1digitallink/#constructor_1)(string, string) | 指定された URI ステムとプライマリキーで空の GS1 Digital Link を初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/barcodetype/) { get; set; } | この GS1 Digital Link のエンコードに使用されるバーコードタイプを取得または設定します。サポートされているタイプは QR、DataMatrix、Aztec、Pdf417、MicroPdf417、DotCode、HanXin、CodablockF、Code128 です。デフォルト値は QR です。 |
| [Count](../../aspose.barcode.complexbarcode/gs1digitallink/count/) { get; } | Application Identifier 要素の数を取得します。 |
| [Elements](../../aspose.barcode.complexbarcode/gs1digitallink/elements/) { get; } | ソース順序ですべての要素のコピーを取得します。 |
| [Item](../../aspose.barcode.complexbarcode/gs1digitallink/item/) { get; } | 順序付けられたシーケンス内の位置で要素を取得します。 |
| [PrimaryApplicationIdentifier](../../aspose.barcode.complexbarcode/gs1digitallink/primaryapplicationidentifier/) { get; } | Digital Link のプライマリキーとして使用される Application Identifier を取得します。null は、URI が構築される際にプライマリキーが自動的に選択されることを意味します。 |
| [UriStem](../../aspose.barcode.complexbarcode/gs1digitallink/uristem/) { get; } | GS1 プライマリキーのパスセグメントの前にある絶対 URI プレフィックスを取得します。ステムにはクエリ文字列やフラグメントは含まれません。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create)(string, GS1Codetext) | GS1 コードテキストからすべての要素をコピーし、唯一利用可能なプライマリキーを選択して GS1 Digital Link を作成します。 |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create_1)(string, GS1Codetext, string) | GS1 コードテキストからすべての要素をコピーし、指定されたプライマリキーを使用して GS1 Digital Link を作成します。 |
| static [Parse](../../aspose.barcode.complexbarcode/gs1digitallink/parse/)(string) | 圧縮されていない GS1 Digital Link URI を解析します。 |
| [Add](../../aspose.barcode.complexbarcode/gs1digitallink/add/)(string, string) | 検証済みの Application Identifier 要素を追加します。 |
| [GetAll](../../aspose.barcode.complexbarcode/gs1digitallink/getall/)(string) | ソース順序で Application Identifier のすべての値を取得します。 |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/getbarcodetype/)() | この GS1 Digital Link のエンコードに使用されるバーコードタイプを取得します。 |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1digitallink/getconstructedcodetext/)() | 圧縮されていない GS1 Digital Link URI を構築します。 |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1digitallink/getfirst/)(string) | Application Identifier の最初の値を取得します。 |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1digitallink/initfromstring/)(string) | 圧縮されていない GS1 Digital Link URI からこのインスタンスを初期化します。提供された URI が正常に解析された後にのみ、既存の状態が置き換えられます。選択されたバーコードタイプは保持されます。 |
| [ToGS1Codetext](../../aspose.barcode.complexbarcode/gs1digitallink/togs1codetext/)() | 現在の GS1 要素を含む独立した GS1 コードテキストを作成します。URI のみの情報は含まれません。 |
| override [ToString](../../aspose.barcode.complexbarcode/gs1digitallink/tostring/)() | 圧縮されていない GS1 Digital Link URI を返します。 |
| [ToUriString](../../aspose.barcode.complexbarcode/gs1digitallink/touristring/)() | 現在のオブジェクト状態を圧縮されていない GS1 Digital Link URI としてフォーマットします。 |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1digitallink/tryparse/)(string, out GS1DigitalLink, out GS1ValidationResult) | 圧縮されていない GS1 Digital Link URI の解析を試み、構造化された検証エラーを返します。 |
| static [Validate](../../aspose.barcode.complexbarcode/gs1digitallink/validate/)(string) | オブジェクトを構築せずに、圧縮されていない GS1 Digital Link URI を検証します。 |

### 関連項目

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


