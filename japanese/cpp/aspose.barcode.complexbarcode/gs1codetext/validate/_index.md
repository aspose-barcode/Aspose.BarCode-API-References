---
title: "メソッド"
linktitle: "Validate"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "メソッド。オブジェクトを構築せずに、形式 (AI)value(AI)value の括弧付き GS1 要素文字列を検証します。値内のリテラル ''('' は (; と記述する必要があります。他のエスケープシーケンスはサポートされず、'')'' は C++ でエスケープする必要はありません。"
type: docs
weight: 1400
url: /ja/cpp/aspose.barcode.complexbarcode/gs1codetext/validate/
---
## GS1Codetext::Validate method


括弧で囲まれた GS1 要素文字列を (AI)value(AI)value の形式で、オブジェクトを生成せずに検証します。値の中のリテラル '(' は ( と記述する必要があり、他のエスケープシーケンスはサポートされず、')' はエスケープする必要がありません。

```cpp
static System::SharedPtr<Common::GS1ValidationResult> Aspose::BarCode::ComplexBarcode::GS1Codetext::Validate(System::String value)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | System::String | 検証対象の括弧付き GS1 要素文字列。 |

### ReturnValue

構造化された検証結果。

## 関連項目

* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
