---
title: "类 BaseDecodeType"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.BaseDecodeType 类。 MultiDecodeType 和 SingleDecodeType 的基类"
type: docs
weight: 130
url: /zh/net/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class

MultiDecodeType 和 SingleDecodeType 的基类。

```csharp
public abstract class BaseDecodeType : IEquatable<BaseDecodeType>
```

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [ContainsAny](../../aspose.barcode.barcoderecognition/basedecodetype/containsany/)(params BaseDecodeType[]) | 确定给定的解码类型中是否包含任何一个 |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals)(BaseDecodeType) | 返回一个值，指示此实例是否等于指定的 `BaseDecodeType` 值。 |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_1)(MultiDecodeType) | 返回一个值，指示此实例是否等于指定的 [`MultiDecodeType`](../multidecodetype/) 值。 |
| override [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_3)(object) | 返回一个值，指示此实例是否等于指定的 `BaseDecodeType` 值。 |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_2)(SingleDecodeType) | 返回一个值，指示此实例是否等于指定的 [`SingleDecodeType`](../singledecodetype/) 值。 |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/basedecodetype/gethashcode/)() | 返回此实例的哈希码。 |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse)(string, out BaseDecodeType) | 将 BaseDecodeType 的字符串表示转换为其实例，并确定具体类型。返回值指示转换是成功还是失败。 |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_1)(string, out MultiDecodeType) | 将 MultiDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_2)(string, out SingleDecodeType) | 将 SingleDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |

## 示例

此示例展示了如何将 BaseDecodeType 与 SingleDecodeType 和 MultiDecodeType 一起使用

```csharp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

### 另见

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


