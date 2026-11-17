---
title: "Aspose::BarCode::ComplexBarcode::PrimaryData class"
linktitle: "PrimaryData"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::PrimaryData class. 用于在 C++ 中存储 HIBC LIC 主数据的类。"
type: docs
weight: 2500
url: /zh/cpp/aspose.barcode.complexbarcode/primarydata/
---
## PrimaryData class


用于存储 HIBC LIC 主数据的类。

```cpp
class PrimaryData : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 返回一个值，指示此实例是否等于指定的 [PrimaryData](./) 值。 |
| [get_LabelerIdentificationCode](./get_labeleridentificationcode/)() const | 标识标签商标识代码的日期。标签商标识代码必须是 4 个字符的字母数字字符串，且首字符必须为字母。 |
| [get_ProductOrCatalogNumber](./get_productorcatalognumber/)() const | 标识产品或目录编号。产品或目录编号必须是最长 18 个字符的字母数字字符串。 |
| [get_UnitOfMeasureID](./get_unitofmeasureid/)() const | 标识计量单位 ID。计量单位 ID 必须是 0 到 9 的整数值。 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [ParseFromString](./parsefromstring/)(System::String) | 根据 HIBC LIC 规范从字符串格式实例化主数据。 |
| [PrimaryData](./primarydata/)() |  |
| [set_LabelerIdentificationCode](./set_labeleridentificationcode/)(System::String) | 标识标签商标识代码的日期。标签商标识代码必须是 4 个字符的字母数字字符串，且首字符必须为字母。 |
| [set_ProductOrCatalogNumber](./set_productorcatalognumber/)(System::String) | 标识产品或目录编号。产品或目录编号必须是最长 18 个字符的字母数字字符串。 |
| [set_UnitOfMeasureID](./set_unitofmeasureid/)(int32_t) | 标识计量单位 ID。计量单位 ID 必须是 0 到 9 的整数值。 |
| [ToString](./tostring/)() const override | 根据 HIBC LIC 规范将数据转换为字符串格式。 |
## 另见

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
