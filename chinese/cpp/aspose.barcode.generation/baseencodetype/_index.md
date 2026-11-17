---
title: "Aspose::BarCode::Generation::BaseEncodeType class"
linktitle: "BaseEncodeType"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::BaseEncodeType 类。C++ 中 SymbologyEncodeType 的基类。"
type: docs
weight: 600
url: /zh/cpp/aspose.barcode.generation/baseencodetype/
---
## BaseEncodeType class


用于 [SymbologyEncodeType](../symbologyencodetype/) 的基类。

```cpp
class BaseEncodeType : public System::IEquatable<System::SharedPtr<BaseEncodeType>>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<BaseEncodeType\>) override | 返回一个值，指示此实例是否等于指定的 [BaseEncodeType](./) 值。 |
| [get_Classification](./get_classification/)() const | 获取此符号的分类。 |
| [get_TypeIndex](./get_typeindex/)() const | 获取编码类型的索引 |
| [get_TypeName](./get_typename/)() const | 获取编码类型的名称 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [GetString](./getstring/)() | 将 [BaseEncodeType](./) 的实例转换为等效的字符串表示。字符串格式为："Index:0; Name:Codabar"。 |
| static [GetString](./getstring/)(System::SharedPtr\<BaseEncodeType\>) | 将 [BaseEncodeType](./) 的实例转换为等效的字符串表示。字符串格式为："Index:-1; Name:None"。 |
| static [Parse](./parse/)(System::String) | 将 [BaseEncodeType](./) 名称的字符串表示转换为其实例。 |
| [ToString](./tostring/)() const override | 以字符串形式返回给定的 [BaseEncodeType](./) 的名称。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | 将 [BaseEncodeType](./) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | 将 [BaseEncodeType](./) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
