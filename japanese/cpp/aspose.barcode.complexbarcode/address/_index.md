---
title: "Aspose::BarCode::ComplexBarcode::Address クラス"
linktitle: "住所"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::Address クラス。C++ における債権者または債務者の住所。"
type: docs
weight: 100
url: /ja/cpp/aspose.barcode.complexbarcode/address/
---
## Address class


[Address](./) of creditor or debtor.

```cpp
class Address : public System::IEquatable<System::SharedPtr<Address>>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Address](./address/)() | [Address](./) のインスタンスを作成します。 |
| [Clear](./clear/)() | すべてのフィールドをクリアし、タイプを [AddressType::Undetermined](../addresstype/) に設定します。 |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 指定されたオブジェクトが現在のオブジェクトと等しいかどうかを判断します。 |
| [Equals](./equals/)(System::SharedPtr\<Address\>) override | 指定された住所が現在の住所と等しいかどうかを判定します。 |
| [get_AddressLine1](./get_addressline1/)() const | 住所行 1 を取得します。 |
| [get_AddressLine2](./get_addressline2/)() const | 住所行 2 を取得します。 |
| [get_CountryCode](./get_countrycode/)() const | 2 文字の ISO 国コードを取得します。 |
| [get_HouseNo](./get_houseno/)() const | 番地を取得します。 |
| [get_Name](./get_name/)() const | 名前を取得します。自然人の場合は姓と名、法人の場合は会社名です。 |
| [get_PostalCode](./get_postalcode/)() const | 郵便番号を取得します。 |
| [get_Street](./get_street/)() const | 通り名を取得します。 |
| [get_Town](./get_town/)() const | 町または市を取得します。 |
| [get_Type](./get_type/)() const | 住所タイプを取得します。 |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを取得します。 |
| [set_AddressLine1](./set_addressline1/)(System::String) | 住所行 1 を設定します。 |
| [set_AddressLine2](./set_addressline2/)(System::String) | 住所行 2 を設定します。 |
| [set_CountryCode](./set_countrycode/)(System::String) | 2 文字の ISO 国コードを設定します。 |
| [set_HouseNo](./set_houseno/)(System::String) | 番地を設定します。 |
| [set_Name](./set_name/)(System::String) | 名前を設定します。自然人の場合は姓と名、法人の場合は会社名です。 |
| [set_PostalCode](./set_postalcode/)(System::String) | 郵便番号を設定します。 |
| [set_Street](./set_street/)(System::String) | 通りを設定します。 |
| [set_Town](./set_town/)(System::String) | 町または市を設定します。 |
## 備考


通り、番地、郵便番号、町を設定するか（タイプ *structured address*）、住所行1と2を設定するか（タイプ *combined address elements*）のいずれかを行うことができます。いずれかのフィールドが設定されると、タイプは自動的に設定されます。フィールドを設定する前は、住所タイプは *undetermined* です。両方のタイプのフィールドが設定されると、住所タイプは *conflicting* になります。すべてのフィールドが空でない限り、名前と国コードは常に設定する必要があります。
## 関連項目

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
