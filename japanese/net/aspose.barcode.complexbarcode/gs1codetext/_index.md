---
title: "クラス GS1Codetext"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.ComplexBarcode.GS1Codetext クラス。アプリケーション識別子要素の順序付けられたシーケンスとしてエンコードおよびデコードするための GS1 コードテキストを表します。元の順序と繰り返しのアプリケーション識別子は保持されます。括弧表記は AIvalueAIvalue の形式です。値の中のリテラルな開き括弧は \\\\( と記述する必要があります。これは唯一サポートされているエスケープシーケンスです。値の中の閉じ括弧はエスケープする必要はありません。"
type: docs
weight: 530
url: /ja/net/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class

アプリケーション識別子要素の順序付けられたシーケンスとしてエンコードおよびデコードするための GS1 コードテキストを表します。元の順序と繰り返しのアプリケーション識別子は保持されます。括弧表記は (AI)value(AI)value の形式です。値の中のリテラルな開き括弧 '(' は \\( と記述する必要があります。これは唯一サポートされているエスケープシーケンスです。値の中の閉じ括弧 ')' はエスケープする必要はありません。

```csharp
public sealed class GS1Codetext : IComplexCodetext
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [GS1Codetext](gs1codetext/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/barcodetype/) { get; set; } | この GS1 コードテキストのエンコードに使用されるバーコードタイプを取得または設定します。サポートされているタイプは GS1Aztec、GS1CodablockF、GS1Code128、GS1DataMatrix、GS1DotCode、GS1HanXin、GS1MicroPdf417、GS1QR および GS1 DataBar タイプです。既定値は GS1Code128 です。 |
| [Count](../../aspose.barcode.complexbarcode/gs1codetext/count/) { get; } | Application Identifier 要素の数を取得します。 |
| [Elements](../../aspose.barcode.complexbarcode/gs1codetext/elements/) { get; } | ソース順序ですべての要素のコピーを取得します。 |
| [Item](../../aspose.barcode.complexbarcode/gs1codetext/item/) { get; } | 順序付けられたシーケンス内の位置で要素を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Parse](../../aspose.barcode.complexbarcode/gs1codetext/parse/)(string) | 括弧で囲まれた GS1 要素文字列 (AI)value(AI)value の形式を解析します。値の中のリテラルな '(' は \\( と記述する必要があります。他のエスケープシーケンスはサポートされておらず、')' はエスケープする必要はありません。 |
| [Add](../../aspose.barcode.complexbarcode/gs1codetext/add/)(string, string) | 検証済みの Application Identifier 要素を追加します。 |
| [GetAll](../../aspose.barcode.complexbarcode/gs1codetext/getall/)(string) | ソース順序で Application Identifier のすべての値を取得します。 |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/getbarcodetype/)() | この GS1 コードテキストのエンコードに使用されるバーコードタイプを取得します。 |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1codetext/getconstructedcodetext/)() | 括弧で囲まれた GS1 コードテキストを (AI)value(AI)value の形式で構築します。値の中のリテラルな開き括弧は \\( とエスケープされます。 |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1codetext/getfirst/)(string) | Application Identifier の最初の値を取得します。 |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1codetext/initfromstring/)(string) | このインスタンスを (AI)value(AI)value 形式の括弧付き GS1 コードテキストから初期化します。提供されたコードテキストが正常に解析された後にのみ、既存の要素が置き換えられます。 |
| override [ToString](../../aspose.barcode.complexbarcode/gs1codetext/tostring/)() | 括弧付き GS1 表現を (AI)value(AI)value の形式で返します。 |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1codetext/tryparse/)(string, out GS1Codetext, out GS1ValidationResult) | 括弧で囲まれた GS1 要素文字列 (AI)value(AI)value の形式を解析しようとし、構造化された検証エラーを返します。値の中のリテラルな '(' は \\( と記述する必要があります。他のエスケープシーケンスはサポートされておらず、')' はエスケープする必要はありません。 |
| static [Validate](../../aspose.barcode.complexbarcode/gs1codetext/validate/)(string) | オブジェクトを構築せずに、括弧で囲まれた GS1 要素文字列 (AI)value(AI)value の形式を検証します。値の中のリテラルな '(' は \\( と記述する必要があります。他のエスケープシーケンスはサポートされておらず、')' はエスケープする必要はありません。 |

### 関連項目

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


