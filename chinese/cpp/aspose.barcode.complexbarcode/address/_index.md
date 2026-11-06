---
title: "Aspose::BarCode::ComplexBarcode::Address 类"
linktitle: "地址"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::Address 类。C++ 中的债权人或债务人的地址。"
type: docs
weight: 100
url: /zh/cpp/aspose.barcode.complexbarcode/address/
---
## Address class


[Address](./) of creditor or debtor.

```cpp
class Address : public System::IEquatable<System::SharedPtr<Address>>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [Address](./address/)() | 创建 [Address](./) 的实例 |
| [Clear](./clear/)() | 清除所有字段并将类型设置为 [AddressType::Undetermined](../addresstype/)。 |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 确定指定的对象是否等于当前对象。 |
| [Equals](./equals/)(System::SharedPtr\<Address\>) override | 确定指定的地址是否等于当前地址。 |
| [get_AddressLine1](./get_addressline1/)() const | 获取地址第一行。 |
| [get_AddressLine2](./get_addressline2/)() const | 获取地址第二行。 |
| [get_CountryCode](./get_countrycode/)() const | 获取两字母 ISO 国家代码。 |
| [get_HouseNo](./get_houseno/)() const | 获取门牌号。 |
| [get_Name](./get_name/)() const | 获取名称，可以是自然人的名和姓或法人的公司名称。 |
| [get_PostalCode](./get_postalcode/)() const | 获取邮政编码。 |
| [get_Street](./get_street/)() const | 获取街道。 |
| [get_Town](./get_town/)() const | 获取城镇或城市。 |
| [get_Type](./get_type/)() const | 获取地址类型。 |
| [GetHashCode](./gethashcode/)() const override | 获取此实例的哈希码。 |
| [set_AddressLine1](./set_addressline1/)(System::String) | 设置地址第一行。 |
| [set_AddressLine2](./set_addressline2/)(System::String) | 设置地址第二行。 |
| [set_CountryCode](./set_countrycode/)(System::String) | 设置两字母 ISO 国家代码。 |
| [set_HouseNo](./set_houseno/)(System::String) | 设置门牌号。 |
| [set_Name](./set_name/)(System::String) | 设置名称，可以是自然人的名和姓或法人的公司名称。 |
| [set_PostalCode](./set_postalcode/)(System::String) | 设置邮政编码。 |
| [set_Street](./set_street/)(System::String) | 设置街道。 |
| [set_Town](./set_town/)(System::String) | 设置城镇或城市。 |
## 备注


您可以设置街道、门牌号、邮政编码和城镇（类型为 *structured address*）或设置地址行 1 和 2（类型为 *combined address elements*）。一旦设置了任意这些字段，类型会自动设置。设置字段之前，地址类型为 *undetermined*。如果同时设置了两种类型的字段，地址类型将变为 *conflicting*。除非所有字段均为空，否则必须始终设置名称和国家代码。
## 另见

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
