---
title: "Aspose::BarCode::Generation::SymbologyEncodeType 类"
linktitle: "SymbologyEncodeType"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::SymbologyEncodeType 类。符号编码类型。请参阅 EncodeTypes 以在 C++ 中获取实例。"
type: docs
weight: 4900
url: /zh/cpp/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class


符号编码类型。请参阅 [EncodeTypes](../encodetypes/) 以获取实例。

```cpp
class SymbologyEncodeType : public Aspose::BarCode::Generation::BaseEncodeType
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [Equals](../baseencodetype/equals/)(System::SharedPtr\<BaseEncodeType\>) override | 返回一个值，指示此实例是否等于指定的 [BaseEncodeType](../baseencodetype/) 值。 |
| [get_Classification](../baseencodetype/get_classification/)() const | 获取此符号的分类。 |
| [get_TypeIndex](../baseencodetype/get_typeindex/)() const | 获取编码类型的索引 |
| [get_TypeName](../baseencodetype/get_typename/)() const | 获取编码类型的名称 |
| [GetHashCode](../baseencodetype/gethashcode/)() const override | 返回此实例的哈希码。 |
| [GetString](../baseencodetype/getstring/)() | 将 [BaseEncodeType](../baseencodetype/) 的实例转换为等效的字符串表示。字符串格式为："Index:0; Name:Codabar"。 |
| static [GetString](../baseencodetype/getstring/)(System::SharedPtr\<BaseEncodeType\>) | 将 [BaseEncodeType](../baseencodetype/) 的实例转换为等效的字符串表示。字符串格式为："Index:-1; Name:None"。 |
| static [Parse](../baseencodetype/parse/)(System::String) | 将 [BaseEncodeType](../baseencodetype/) 名称的字符串表示转换为其实例。 |
| [ToString](../baseencodetype/tostring/)() const override | 返回给定的 [BaseEncodeType](../baseencodetype/) 的名称字符串。 |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | 将 [BaseEncodeType](../baseencodetype/) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | 将 [BaseEncodeType](../baseencodetype/) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
## 备注


此示例展示了如何获取 [SymbologyEncodeType](./) 类的实例。
```cpp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR

[VB.NET]
Dim symbologyType As SymbologyEncodeType
symbologyType = EncodeTypes.QR
```

## 另见

* Class [BaseEncodeType](../baseencodetype/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
