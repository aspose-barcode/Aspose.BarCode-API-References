---
title: "メソッド"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " method. 括弧付きGS1要素文字列を (AI)value(AI)value の形式で解析し、構造化された検証エラーを返します。 値の中のリテラル '(' は ( と記述しなければなりません。他のエスケープシーケンスはサポートされず、')' は C++ でエスケープする必要はありません。"
type: docs
weight: 1600
url: /ja/cpp/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext::TryParse method


括弧で囲まれた GS1 要素文字列を (AI)value(AI)value の形式で解析しようとし、構造化された検証エラーを返します。値の中のリテラル '(' は ( と記述する必要があり、他のエスケープシーケンスはサポートされず、')' はエスケープする必要がありません。

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1Codetext::TryParse(System::String value, System::SharedPtr<GS1Codetext> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | System::String | 括弧付きGS1要素文字列を解析するための文字列。 |
| result | System::SharedPtr\<GS1Codetext\>\& | このメソッドが true を返す場合、解析されたGS1コードテキストが含まれます。そうでない場合は null です。 |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | 検証結果を含みます。*value* が null の場合は null です。 |

### ReturnValue

解析が成功した場合は true、そうでない場合は false です。

## 関連項目

* Class [GS1Codetext](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
