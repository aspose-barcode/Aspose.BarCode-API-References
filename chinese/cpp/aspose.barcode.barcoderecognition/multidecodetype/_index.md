---
title: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType 类"
linktitle: "MultiDecodeType"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType 类。C++ 中的复合解码类型。"
type: docs
weight: 2600
url: /zh/cpp/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class


复合解码类型。

```cpp
class MultiDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                        public System::IEquatable<System::SharedPtr<MultiDecodeType>>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<SingleDecodeType\>) | 向 [MultiDecodeType](./) 添加另一个 [SingleDecodeType](../singledecodetype/)。 |
| [ContainsAll](./containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | 检查此是否包含所有条码类型。 |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | 是否包含任何类型 |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | 返回一个值，指示此实例是否等于指定的 [MultiDecodeType](./) 值。 |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | 返回一个值，指示此解码类型集合是否仅包含指定的 [SingleDecodeType](../singledecodetype/) 值。 |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 返回一个值，指示此实例是否等于指定的 [MultiDecodeType](./) 值。 |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | 返回一个值，指示此实例是否等于指定的 [BaseDecodeType](../basedecodetype/) 值。 |
| [Exclude](./exclude/)(System::SharedPtr\<SingleDecodeType\>) | 从 [MultiDecodeType](./) 中排除 [SingleDecodeType](../singledecodetype/)，并返回新的 [MultiDecodeType](./) 实例。 |
| [get_GetSingleTypesCount](./get_getsingletypescount/)() | 返回单个类型的数量。 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [GetSingleTypes](./getsingletypes/)() | 表示单个类型的列表。 |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | 初始化 [MultiDecodeType](./) 类的新实例。 |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | 初始化 [MultiDecodeType](./) 类的新实例。 |
| [ToString](./tostring/)() const override | 重写的方法，将 [MultiDecodeType](./) 表示为字符串。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | 将 [MultiDecodeType](./) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | 将 [SingleDecodeType](../singledecodetype/) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | 在确定具体类型后，将 [BaseDecodeType](../basedecodetype/) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
## 备注


此示例展示了如何创建复合的 MultiDecode 类型，将 [SingleDecodeType](../singledecodetype/) 与 MultiDecode 类型组合在一起。
```cpp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

## 另见

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
