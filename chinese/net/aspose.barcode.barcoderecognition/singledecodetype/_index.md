---
title: "类 SingleDecodeType"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.SingleDecodeType 类。单一解码类型。请参阅解码类型以获取实例"
type: docs
weight: 390
url: /zh/net/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class

单一解码类型。请参阅解码类型以获取实例。

```csharp
public sealed class SingleDecodeType : BaseDecodeType, IEquatable<SingleDecodeType>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [TypeIndex](../../aspose.barcode.barcoderecognition/singledecodetype/typeindex/) { get; } | 获取解码类型的索引 |
| [TypeName](../../aspose.barcode.barcoderecognition/singledecodetype/typename/) { get; } | 获取解码类型的名称 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Parse](../../aspose.barcode.barcoderecognition/singledecodetype/parse/)(string) | 将 SingleDecodeType 名称的字符串表示转换为其实例。 |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/singledecodetype/containsany/)(params BaseDecodeType[]) | 返回一个值，指示此实例是否包含在指定的列表中。 |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | 返回一个值，指示此实例是否等于指定的 [`BaseDecodeType`](../basedecodetype/) 值。 |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_1)(MultiDecodeType) | 返回一个值，指示指定的 [`MultiDecodeType`](../multidecodetype/) 集合是否仅包含此解码类型。 |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_3)(object) | 返回一个值，指示此实例是否等于指定的 `SingleDecodeType` 值。 |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_2)(SingleDecodeType) | 返回一个值，指示此实例是否等于指定的 `SingleDecodeType` 值。 |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/singledecodetype/gethashcode/)() | 返回此实例的哈希码。 |
| [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)() | 将 SingleDecodeType 实例转换为等效的字符串表示。字符串格式为：\"Index:-1; Name:None\"。 |
| override [ToString](../../aspose.barcode.barcoderecognition/singledecodetype/tostring/)() | 返回给定 SingleDecodeType 的名称字符串。 |
| static [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)(SingleDecodeType) | 将 SingleDecodeType 实例转换为等效的字符串表示。字符串格式为：\"Index:-1; Name:None\"。 |

## 示例

此示例展示如何获取单一解码类型的实例。

```csharp
[C#]
SingleDecodeType singleType = DecodeType.QR 
 
[VB.NET]
Dim singleType As SingleDecodeType 
singleType = DecodeType.QR
```

### 另见

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


