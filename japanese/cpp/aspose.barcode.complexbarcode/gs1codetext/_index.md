---
title: "Aspose::BarCode::ComplexBarcode::GS1Codetext クラス"
linktitle: "GS1Codetext"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::GS1Codetext クラス。エンコードおよびデコード用に、アプリケーション識別子要素の順序付けられたシーケンスとして GS1 コードテキストを表します。ソース順と繰り返しのアプリケーション識別子は保持されます。括弧表記は (AI)value(AI)value の形式です。値内のリテラル開き括弧 ''('' は ( と記述する必要があります。これは唯一サポートされているエスケープシーケンスです。値内の閉じ括弧 '')'' は C++ ではエスケープする必要はありません。"
type: docs
weight: 500
url: /ja/cpp/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class


GS1 コードテキストを、アプリケーション識別子要素の順序付けられたシーケンスとしてエンコードおよびデコードすることを表します。元の順序と繰り返しのアプリケーション識別子は保持されます。括弧表記は (AI)value(AI)value の形式です。値内のリテラル開き括弧 '(' は (; と記述する必要があります（これが唯一サポートされるエスケープシーケンスです）。値内の閉じ括弧 ')' はエスケープする必要はありません。

```cpp
class GS1Codetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Add](./add/)(System::String, System::String) | 検証済みの Application Identifier 要素を追加します。 |
| [get_BarcodeType](./get_barcodetype/)() const | この GS1 コードテキストをエンコードするために使用されるバーコードタイプを取得します。サポートされているタイプは GS1Aztec、GS1CodablockF、GS1Code128、GS1DataMatrix、GS1DotCode、GS1HanXin、GS1MicroPdf417、GS1QR、GS1 DataBar です。デフォルト値は GS1Code128 です。 |
| [get_Count](./get_count/)() | Application Identifier 要素の数を取得します。 |
| [get_Elements](./get_elements/)() | 元の順序ですべての要素のコピーを取得します。 |
| [GetAll](./getall/)(System::String) | ソース順でアプリケーション識別子のすべての値を取得します。 |
| [GetBarcodeType](./getbarcodetype/)() override | この GS1 コードテキストをエンコードするために使用されるバーコードタイプを取得します。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 括弧で囲まれた GS1 コードテキストを (AI)value(AI)value の形式で構築します。値内のリテラル開き括弧は ( とエスケープされます。 |
| [GetFirst](./getfirst/)(System::String) | アプリケーション識別子の最初の値を取得します。 |
| [GS1Codetext](./gs1codetext/)() | 空の GS1 コードテキストを初期化します。 |
| [idx_get](./idx_get/)(int32_t) | 順序付けられたシーケンス内の位置で要素を取得します。 |
| [InitFromString](./initfromstring/)(System::String) override | 括弧で囲まれた (AI)value(AI)value 形式の GS1 コードテキストからこのインスタンスを初期化します。提供されたコードテキストが正常に解析された後にのみ、既存の要素が置き換えられます。 |
| static [Parse](./parse/)(System::String) | 括弧で囲まれた (AI)value(AI)value 形式の GS1 要素文字列を解析します。値内のリテラル '(' は (; と記述する必要があります。他のエスケープシーケンスはサポートされておらず、')' はエスケープする必要がありません。 |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | この GS1 コードテキストをエンコードするために使用されるバーコードタイプを設定します。サポートされているタイプは GS1Aztec、GS1CodablockF、GS1Code128、GS1DataMatrix、GS1DotCode、GS1HanXin、GS1MicroPdf417、GS1QR、GS1 DataBar です。デフォルト値は GS1Code128 です。 |
| [ToString](./tostring/)() const override | 括弧で囲まれた GS1 表現を (AI)value(AI)value の形式で返します。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1Codetext\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | 括弧で囲まれた GS1 要素文字列を (AI)value(AI)value の形式で解析しようとし、構造化された検証エラーを返します。値の中のリテラル '(' は ( と記述する必要があり、他のエスケープシーケンスはサポートされず、')' はエスケープする必要がありません。 |
| static [Validate](./validate/)(System::String) | 括弧で囲まれた GS1 要素文字列を (AI)value(AI)value の形式で、オブジェクトを生成せずに検証します。値の中のリテラル '(' は ( と記述する必要があり、他のエスケープシーケンスはサポートされず、')' はエスケープする必要がありません。 |
## 関連項目

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
