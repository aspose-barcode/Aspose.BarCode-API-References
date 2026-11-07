---
title: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink class"
linktitle: "GS1DigitalLink"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink クラス。GS1 Digital Link のコードテキストをエンコードおよびデコードするための、Application Identifier 要素の順序付けられたシーケンスとして表します。元の順序と繰り返しの Application Identifier は保持されます。構築されたコードテキストは圧縮されていない GS1 Digital Link URI です。C++ で解析する際、非 GS1 のクエリパラメータおよび URI フラグメントは無視されます。"
type: docs
weight: 600
url: /ja/cpp/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class


GS1 Digital Link コードテキストを、アプリケーション識別子要素の順序付けられたシーケンスとしてエンコードおよびデコードすることを表します。元の順序と繰り返しのアプリケーション識別子は保持されます。構築されたコードテキストは圧縮されていない GS1 Digital Link URI です。解析時に非 GS1 のクエリパラメータおよび URI フラグメントは無視されます。

```cpp
class GS1DigitalLink : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Add](./add/)(System::String, System::String) | 検証済みの Application Identifier 要素を追加します。 |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>) | GS1 コードテキストからすべての要素をコピーし、唯一利用可能なプライマリキーを選択して GS1 Digital Link を作成します。 |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>, System::String) | GS1 コードテキストからすべての要素をコピーし、指定されたプライマリキーを使用して GS1 Digital Link を作成します。 |
| [get_BarcodeType](./get_barcodetype/)() const | この GS1 Digital Link をエンコードするために使用されるバーコードタイプを取得します。サポートされているタイプは QR、DataMatrix、Aztec、Pdf417、MicroPdf417、DotCode、HanXin、CodablockF、Code128 です。デフォルト値は QR です。 |
| [get_Count](./get_count/)() | Application Identifier 要素の数を取得します。 |
| [get_Elements](./get_elements/)() | 元の順序ですべての要素のコピーを取得します。 |
| [get_PrimaryApplicationIdentifier](./get_primaryapplicationidentifier/)() const | Digital Link のプライマリキーとして使用される Application Identifier を取得します。null は、URI が構築される際にプライマリキーが自動的に選択されることを意味します。 |
| [get_UriStem](./get_uristem/)() const | GS1 プライマリキーのパスセグメントの前にある絶対 URI プレフィックスを取得します。ステムにはクエリ文字列やフラグメントは含まれません。 |
| [GetAll](./getall/)(System::String) | ソース順でアプリケーション識別子のすべての値を取得します。 |
| [GetBarcodeType](./getbarcodetype/)() override | この GS1 デジタルリンクをエンコードするために使用されるバーコードタイプを取得します。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 圧縮されていない GS1 デジタルリンク URI を構築します。 |
| [GetFirst](./getfirst/)(System::String) | アプリケーション識別子の最初の値を取得します。 |
| [GS1DigitalLink](./gs1digitallink/)(System::String) | 指定された URI ステムで空の GS1 デジタルリンクを初期化します。プライマリキーは、プライマリキー候補が正確に1つ存在する場合に自動的に選択されます。 |
| [GS1DigitalLink](./gs1digitallink/)(System::String, System::String) | 指定された URI ステムとプライマリキーで空の GS1 デジタルリンクを初期化します。 |
| [idx_get](./idx_get/)(int32_t) | 順序付けられたシーケンス内の位置で要素を取得します。 |
| [InitFromString](./initfromstring/)(System::String) override | 圧縮されていない GS1 デジタルリンク URI からこのインスタンスを初期化します。既存の状態は、提供された URI が正常に解析された後にのみ置き換えられます。選択されたバーコードタイプは保持されます。 |
| static [Parse](./parse/)(System::String) | 圧縮されていない GS1 デジタルリンク URI を解析します。 |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | この GS1 デジタルリンクをエンコードするために使用されるバーコードタイプを設定します。サポートされているタイプは QR、DataMatrix、Aztec、Pdf417、MicroPdf417、DotCode、HanXin、CodablockF、Code128 です。デフォルト値は QR です。 |
| [ToGS1Codetext](./togs1codetext/)() | 現在の GS1 要素を含む独立した GS1 コードテキストを作成します。URI のみの情報は含まれません。 |
| [ToString](./tostring/)() const override | 圧縮されていない GS1 デジタルリンク URI を返します。 |
| [ToUriString](./touristring/)() | 現在のオブジェクト状態を圧縮されていない GS1 デジタルリンク URI としてフォーマットします。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1DigitalLink\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | 圧縮されていない GS1 デジタルリンク URI の解析を試み、構造化された検証エラーを返します。 |
| static [Validate](./validate/)(System::String) | オブジェクトを構築せずに圧縮されていない GS1 デジタルリンク URI を検証します。 |
## 関連項目

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
