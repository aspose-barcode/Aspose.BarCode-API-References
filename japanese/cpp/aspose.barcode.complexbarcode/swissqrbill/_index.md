---
title: "Aspose::BarCode::ComplexBarcode::SwissQRBill class"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::SwissQRBill クラス。C++ の SwissQR 請求書データ。"
type: docs
weight: 2700
url: /ja/cpp/aspose.barcode.complexbarcode/swissqrbill/
---
## SwissQRBill class


SwissQR請求書データ

```cpp
class SwissQRBill : public System::IEquatable<System::SharedPtr<SwissQRBill>>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [CreateAndSetCreditorReference](./createandsetcreditorreference/)(System::String) | 生の文字列に "RF" をプレフィックスし、97 でのモジュロチェックサムを付加して、ISO11649 の債権者参照を作成および設定します。 |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 指定されたオブジェクトが現在のオブジェクトと等しいかどうかを判断します。 |
| [Equals](./equals/)(System::SharedPtr\<SwissQRBill\>) override | 指定された請求書が現在の請求書と等しいかどうかを判定します。 |
| [get_Account](./get_account/)() const | 債権者の口座番号を取得します。 |
| [get_AlternativeSchemes](./get_alternativeschemes/)() const | 代替支払スキームを取得または設定します。 |
| [get_Amount](./get_amount/)() const | 支払金額を取得します。 |
| [get_BillInformation](./get_billinformation/)() const | 追加の構造化請求情報を取得します。 |
| [get_Creditor](./get_creditor/)() const | 債権者の住所を取得します。 |
| [get_Currency](./get_currency/)() const | 支払通貨を取得します。 |
| [get_Debtor](./get_debtor/)() const | 債務者の住所を取得します。 |
| [get_Reference](./get_reference/)() const | 債権者の支払参照を取得します。 |
| [get_UnstructuredMessage](./get_unstructuredmessage/)() const | 追加の非構造化メッセージを取得します。 |
| [get_Version](./get_version/)() const | SwissQR 請求書標準のバージョンを取得します。 |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを取得します。 |
| [set_Account](./set_account/)(System::String) | 債権者の口座番号を設定します。 |
| [set_AlternativeSchemes](./set_alternativeschemes/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<AlternativeScheme\>>>) | 代替支払スキームを取得または設定します。 |
| [set_Amount](./set_amount/)(System::Decimal) | 支払金額を設定します。 |
| [set_BillInformation](./set_billinformation/)(System::String) | 追加の構造化請求情報を設定します。 |
| [set_Creditor](./set_creditor/)(System::SharedPtr\<Address\>) | 債権者の住所を設定します。 |
| [set_Currency](./set_currency/)(System::String) | 支払通貨を設定します。 |
| [set_Debtor](./set_debtor/)(System::SharedPtr\<Address\>) | 債務者の住所を設定します。 |
| [set_Reference](./set_reference/)(System::String) | 債権者の支払参照を設定します。 |
| [set_UnstructuredMessage](./set_unstructuredmessage/)(System::String) | 追加の非構造化メッセージを設定します。 |
| [set_Version](./set_version/)(SwissQRBill::QrBillStandardVersion) | SwissQR 請求書標準のバージョンを設定します。 |
## Typedefs

| 型定義 | 説明 |
| --- | --- |
| [QrBillStandardVersion](./qrbillstandardversion/) | SwissQR 請求書標準バージョン |
## 関連項目

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
