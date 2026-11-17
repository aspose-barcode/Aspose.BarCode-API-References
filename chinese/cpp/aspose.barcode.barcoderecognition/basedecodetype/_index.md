---
title: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType 类"
linktitle: "BaseDecodeType"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType 类。C++ 中 MultiDecodeType 和 SingleDecodeType 的基类。"
type: docs
weight: 900
url: /zh/cpp/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class


用于 [MultiDecodeType](../multidecodetype/) 和 [SingleDecodeType](../singledecodetype/) 的基类。

```cpp
class BaseDecodeType : public virtual System::IEquatable<System::SharedPtr<BaseDecodeType>>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | 确定给定的任意解码类型是否包含在 |
| virtual [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) | 返回一个值，指示此实例是否等于指定的 [SingleDecodeType](../singledecodetype/) 值。 |
| virtual [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) | 返回一个值，指示此实例是否等于指定的 [MultiDecodeType](../multidecodetype/) 值。 |
| [Equals](./equals/)(System::SharedPtr\<BaseDecodeType\>) override | 返回一个值，指示此实例是否等于指定的 [BaseDecodeType](./) 值。 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | 将 [SingleDecodeType](../singledecodetype/) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | 将 [MultiDecodeType](../multidecodetype/) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | 在确定具体类型后，将 [BaseDecodeType](./) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
## 备注


此示例展示了如何将 [BaseDecodeType](./) 与 [SingleDecodeType](../singledecodetype/) 和 [MultiDecodeType](../multidecodetype/) 一起使用
```cpp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

## 另见

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
