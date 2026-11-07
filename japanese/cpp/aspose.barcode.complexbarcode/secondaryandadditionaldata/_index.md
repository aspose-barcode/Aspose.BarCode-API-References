---
title: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class. C++ で HIBC LIC の二次および追加データを保存するためのクラス。"
type: docs
weight: 2600
url: /ja/cpp/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class


HIBC LICの二次データおよび追加データを格納するクラスです。

```cpp
class SecondaryAndAdditionalData : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | このインスタンスが指定された [SecondaryAndAdditionalData](./) の値と等しいかどうかを示す値を返します。 |
| [get_DateOfManufacture](./get_dateofmanufacture/)() const | 製造日を識別します。製造日はこのフィールドを使用しないようにするために DateTime.MinValue に設定できます。既定値: DateTime.MinValue |
| [get_ExpiryDate](./get_expirydate/)() const | 有効期限日を識別します。ExpiryDateFormat が None に設定されていない場合に使用されます。 |
| [get_ExpiryDateFormat](./get_expirydateformat/)() const | 有効期限日形式を識別します。 |
| [get_LotNumber](./get_lotnumber/)() const | ロットまたはバッチ番号を識別します。ロット/バッチ番号は最大18文字の英数字文字列である必要があります。 |
| [get_Quantity](./get_quantity/)() const | 数量を識別します。0 から 500 の整数値である必要があります。数量はこのフィールドを使用しないようにするために -1 に設定できます。既定値: -1 |
| [get_SerialNumber](./get_serialnumber/)() const | シリアル番号を識別します。シリアル番号は最大18文字の英数字文字列である必要があります。 |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [ParseFromString](./parsefromstring/)(System::String) | HIBC LIC 仕様に従って文字列形式から二次および追加の補足データをインスタンス化します。 |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/)() |  |
| [set_DateOfManufacture](./set_dateofmanufacture/)(System::DateTime) | 製造日を識別します。製造日はこのフィールドを使用しないようにするために DateTime.MinValue に設定できます。既定値: DateTime.MinValue |
| [set_ExpiryDate](./set_expirydate/)(System::DateTime) | 有効期限日を識別します。ExpiryDateFormat が None に設定されていない場合に使用されます。 |
| [set_ExpiryDateFormat](./set_expirydateformat/)(HIBCLICDateFormat) | 有効期限日形式を識別します。 |
| [set_LotNumber](./set_lotnumber/)(System::String) | ロットまたはバッチ番号を識別します。ロット/バッチ番号は最大18文字の英数字文字列である必要があります。 |
| [set_Quantity](./set_quantity/)(int32_t) | 数量を識別します。0 から 500 の整数値である必要があります。数量はこのフィールドを使用しないようにするために -1 に設定できます。既定値: -1 |
| [set_SerialNumber](./set_serialnumber/)(System::String) | シリアル番号を識別します。シリアル番号は最大18文字の英数字文字列である必要があります。 |
| [ToString](./tostring/)() const override | HIBC LIC 仕様に従ってデータを文字列形式に変換します。 |
## 関連項目

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
