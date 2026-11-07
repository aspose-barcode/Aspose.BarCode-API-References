---
title: "メソッド"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。圧縮されていないGS1デジタルリンクURIの解析を試み、C++で構造化された検証エラーを返します。"
type: docs
weight: 2000
url: /ja/cpp/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink::TryParse method


圧縮されていない GS1 デジタルリンク URI の解析を試み、構造化された検証エラーを返します。

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1DigitalLink::TryParse(System::String value, System::SharedPtr<GS1DigitalLink> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | System::String | 解析するGS1デジタルリンクURIです。 |
| result | System::SharedPtr\<GS1DigitalLink\>\& | このメソッドが true を返す場合、解析されたGS1デジタルリンクが含まれます。そうでない場合は null です。 |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | 検証結果を含みます。*value* が null の場合は null です。 |

### ReturnValue

解析が成功した場合は true、そうでない場合は false です。

## 関連項目

* Class [GS1DigitalLink](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
