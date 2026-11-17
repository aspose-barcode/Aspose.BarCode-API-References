---
title: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType 类"
linktitle: "SingleDecodeType"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType 类。单解码类型。请参阅解码类型以在 C++ 中获取实例。"
type: docs
weight: 3200
url: /zh/cpp/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class


单一解码类型。请参阅解码类型以获取实例。

```cpp
class SingleDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                         public System::IEquatable<System::SharedPtr<SingleDecodeType>>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | 返回一个值，指示此实例是否包含在指定的列表中。 |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | 返回一个值，指示此实例是否等于指定的 [SingleDecodeType](./) 值。 |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | 返回一个值，指示指定的 [MultiDecodeType](../multidecodetype/) 集合是否仅包含此解码类型。 |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 返回一个值，指示此实例是否等于指定的 [SingleDecodeType](./) 值。 |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | 返回一个值，指示此实例是否等于指定的 [BaseDecodeType](../basedecodetype/) 值。 |
| [get_TypeIndex](./get_typeindex/)() const | 获取解码类型的索引 |
| [get_TypeName](./get_typename/)() const | 获取解码类型的名称 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [GetString](./getstring/)() | 将 [SingleDecodeType](./) 的实例转换为等效的字符串表示形式。字符串格式为："Index:-1; Name:None"。 |
| static [GetString](./getstring/)(System::SharedPtr\<SingleDecodeType\>) | 将 [SingleDecodeType](./) 的实例转换为等效的字符串表示形式。字符串格式为："Index:-1; Name:None"。 |
| static [Parse](./parse/)(System::String) | 将 [SingleDecodeType](./) 名称的字符串表示转换为其实例。 |
| [ToString](./tostring/)() const override | 以字符串形式返回给定的 [SingleDecodeType](./) 的名称。 |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | 将 [SingleDecodeType](./) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | 将 [MultiDecodeType](../multidecodetype/) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | 在确定具体类型后，将 [BaseDecodeType](../basedecodetype/) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
## 备注


此示例展示如何获取单解码类型的实例。
```cpp
[C#]
SingleDecodeType singleType = DecodeType.QR

[VB.NET]
Dim singleType As SingleDecodeType
singleType = DecodeType.QR
```

## 另见

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
