---
title: "Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings クラス"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings クラス。AustraliaPost のデコードパラメータです。AustraliaPost シンボロジーの認識データに影響を与えるパラメータを含みます（C++）。"
type: docs
weight: 200
url: /ja/cpp/aspose.barcode.barcoderecognition/australiapostsettings/
---
## AustraliaPostSettings class


AustraliaPost デコードパラメーター。AustraliaPost シンボルの認識データに影響を与えるパラメーターを含みます。

```cpp
class AustraliaPostSettings : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_CustomerInformationDecoder](./get_customerinformationdecoder/)() const | AustraliaPost シンボロジーで使用される顧客情報フィールドのデコード用パブリックインターフェイスです。 |
| [get_CustomerInformationInterpretingType](./get_customerinformationinterpretingtype/)() const | AustralianPost の顧客情報の解釈タイプを取得します。 [BarCode.Default](../checksumvalidation/) は [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/) です。 |
| [get_IgnoreEndingFillingPatternsForCTable](./get_ignoreendingfillingpatternsforctable/)() const | デコード時に CTable 方法として顧客情報フィールドの最後のフィリングパターンを無視するよう AustraliaPost デコーダに強制するフラグです。CTable エンコーディング方式はエンコードテーブルにギャップがなく、フィリングパターンのシーケンス "333" は文字 "z" としてデコードされます。 |
| [set_CustomerInformationDecoder](./set_customerinformationdecoder/)(System::SharedPtr\<AustraliaPostCustomerInformationDecoder\>) | AustraliaPost シンボロジーで使用される顧客情報フィールドのデコード用パブリックインターフェイスです。 |
| [set_CustomerInformationInterpretingType](./set_customerinformationinterpretingtype/)(Aspose::BarCode::CustomerInformationInterpretingType) | AustralianPost の顧客情報の解釈タイプを設定します。 [BarCode.Default](../checksumvalidation/) は [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/) です。 |
| [set_IgnoreEndingFillingPatternsForCTable](./set_ignoreendingfillingpatternsforctable/)(bool) | デコード時に CTable 方法として顧客情報フィールドの最後のフィリングパターンを無視するよう AustraliaPost デコーダに強制するフラグです。CTable エンコーディング方式はエンコードテーブルにギャップがなく、フィリングパターンのシーケンス "333" は文字 "z" としてデコードされます。 |
## 関連項目

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
