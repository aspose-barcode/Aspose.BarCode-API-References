---
title: BaseDecodeType
second_title: Aspose.BarCode for .NET API 参考
description: MultyDecodeType 和 SingleDecodeType 的基类
type: docs
weight: 120
url: /zh/net/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class

MultyDecodeType 和 SingleDecodeType 的基类。

```csharp
public abstract class BaseDecodeType : IEquatable<BaseDecodeType>
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| abstract [ContainsAny](../../aspose.barcode.barcoderecognition/basedecodetype/containsany)(params BaseDecodeType[]) | 确定任何给定的解码类型是否包含在 中 |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals#equals)(BaseDecodeType) | 返回一个值，指示此实例是否等于指定的[`BaseDecodeType`](../basedecodetype)值. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals#equals_1)(MultyDecodeType) | 返回一个值，指示此实例是否等于指定的[`MultyDecodeType`](../multydecodetype)值. |
| override [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals#equals_3)(object) | 返回一个值，指示此实例是否等于指定的[`BaseDecodeType`](../basedecodetype)值. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals#equals_2)(SingleDecodeType) | 返回一个值，指示此实例是否等于指定的[`SingleDecodeType`](../singledecodetype)值. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/basedecodetype/gethashcode)() | 返回此实例的哈希码。 |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse#tryparse)(string, out BaseDecodeType) | 在确定具体类型后，将 BaseDecodeType 的字符串表示形式转换为其实例。 返回值指示转换是成功还是失败。 |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse#tryparse_1)(string, out MultyDecodeType) | 将 MultyDecodeType 的字符串表示形式转换为其实例。 返回值指示转换是成功还是失败。 |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse#tryparse_2)(string, out SingleDecodeType) | 将 SingleDecodeType 的字符串表示形式转换为其实例。 返回值指示转换是成功还是失败。 |

### 例子

此示例展示了如何将 BaseDecodeType 与 SingleDecodeType 和 MultyDecodeType 一起使用

```csharp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultyDecodeType(DecodeType.Code128, DecodeType.Code39Standard, DecodeType.Code39Extended);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultyDecodeType(DecodeType.Code128, DecodeType.Code39Standard, DecodeType.Code39Extended)
```

### 也可以看看

* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* 部件 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
