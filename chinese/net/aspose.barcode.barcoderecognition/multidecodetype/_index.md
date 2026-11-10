---
title: "类 MultiDecodeType"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.MultiDecodeType 类。复合解码类型"
type: docs
weight: 320
url: /zh/net/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class

复合解码类型

```csharp
public class MultiDecodeType : BaseDecodeType, IEquatable<MultiDecodeType>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MultiDecodeType](multidecodetype/#constructor)(params BaseDecodeType[]) | 初始化 `MultiDecodeType` 类的新实例。 |
| [MultiDecodeType](multidecodetype/#constructor_1)(params SingleDecodeType[]) | 初始化 `MultiDecodeType` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypescount/) { get; } | 返回若干单一类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multidecodetype/add/)(SingleDecodeType) | 向 MultiDecodeType 添加一个额外的 [`SingleDecodeType`](../singledecodetype/)。 |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multidecodetype/containsall/)(params BaseDecodeType[]) | 检查此是否包含所有条码类型。 |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multidecodetype/containsany/)(params BaseDecodeType[]) | 是否包含任何类型 |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | 返回一个值，指示此实例是否等于指定的 [`BaseDecodeType`](../basedecodetype/) 值。 |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_1)(MultiDecodeType) | 返回一个值，指示此实例是否等于指定的 `MultiDecodeType` 值。 |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_3)(object) | 返回一个值，指示此实例是否等于指定的 `MultiDecodeType` 值。 |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_2)(SingleDecodeType) | 返回一个值，指示此解码类型集合是否仅包含指定的 [`SingleDecodeType`](../singledecodetype/) 值。 |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | 从 MultiDecodeType 中排除 [`SingleDecodeType`](../singledecodetype/)，并返回新的 MultiDecodeType 实例。 |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | 返回此实例的哈希码。 |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | 表示单一类型的列表。 |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | 重写的方法，将 MultiDecodeType 表示为字符串。 |
| static [TryParse](../../aspose.barcode.barcoderecognition/multidecodetype/tryparse/)(string, out MultiDecodeType) | 将 MultiDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |

## 示例

此示例展示了如何创建复合的 MultiDecode 类型，这些类型结合了 SingleDecodeType 和 MultiDecode 类型。

```csharp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType 
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

### 另见

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


