---
title: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class. 用于在 C++ 中存储 HIBC LIC 次要和附加数据的类。"
type: docs
weight: 2600
url: /zh/cpp/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class


用于存储 HIBC LIC 次要和附加数据的类。

```cpp
class SecondaryAndAdditionalData : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 返回一个值，指示此实例是否等于指定的 [SecondaryAndAdditionalData](./) 值。 |
| [get_DateOfManufacture](./get_dateofmanufacture/)() const | 标识生产日期。可以将生产日期设置为 DateTime.MinValue 以不使用此字段。默认值：DateTime.MinValue |
| [get_ExpiryDate](./get_expirydate/)() const | 标识有效期。若 ExpiryDateFormat 未设置为 None，则会使用此字段。 |
| [get_ExpiryDateFormat](./get_expirydateformat/)() const | 标识有效期格式。 |
| [get_LotNumber](./get_lotnumber/)() const | 标识批次或批号。批次/批号必须是最长为 18 个字符的字母数字字符串。 |
| [get_Quantity](./get_quantity/)() const | 标识数量，必须是 0 到 500 的整数。可以将数量设置为 -1 以不使用此字段。默认值：-1 |
| [get_SerialNumber](./get_serialnumber/)() const | 标识序列号。序列号必须是最长为 18 个字符的字母数字字符串。 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [ParseFromString](./parsefromstring/)(System::String) | 根据 HIBC LIC 规范，从字符串格式实例化次要和附加补充数据。 |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/)() |  |
| [set_DateOfManufacture](./set_dateofmanufacture/)(System::DateTime) | 标识生产日期。可以将生产日期设置为 DateTime.MinValue 以不使用此字段。默认值：DateTime.MinValue |
| [set_ExpiryDate](./set_expirydate/)(System::DateTime) | 标识有效期。若 ExpiryDateFormat 未设置为 None，则会使用此字段。 |
| [set_ExpiryDateFormat](./set_expirydateformat/)(HIBCLICDateFormat) | 标识有效期格式。 |
| [set_LotNumber](./set_lotnumber/)(System::String) | 标识批次或批号。批次/批号必须是最长为 18 个字符的字母数字字符串。 |
| [set_Quantity](./set_quantity/)(int32_t) | 标识数量，必须是 0 到 500 的整数。可以将数量设置为 -1 以不使用此字段。默认值：-1 |
| [set_SerialNumber](./set_serialnumber/)(System::String) | 标识序列号。序列号必须是最长为 18 个字符的字母数字字符串。 |
| [ToString](./tostring/)() const override | 根据 HIBC LIC 规范将数据转换为字符串格式。 |
## 另见

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
