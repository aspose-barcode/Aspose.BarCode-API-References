---
title: "类 SymbologyEncodeType"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.SymbologyEncodeType 类。符号编码类型。参见 EncodeTypes 获取实例"
type: docs
weight: 1710
url: /zh/net/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class

符号编码类型。请参阅 EncodeTypes 获取实例。

```csharp
public class SymbologyEncodeType : BaseEncodeType
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Classification](../../aspose.barcode.generation/baseencodetype/classification/) { get; } | 获取此符号系统的分类。 |
| [TypeIndex](../../aspose.barcode.generation/baseencodetype/typeindex/) { get; } | 获取编码类型的索引 |
| [TypeName](../../aspose.barcode.generation/baseencodetype/typename/) { get; } | 获取编码类型的名称 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(BaseEncodeType) | 返回一个值，指示此实例是否等于指定的 [`BaseEncodeType`](../baseencodetype/) 值。 |
| override [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(object) | 返回一个值，指示此实例是否等于指定的 [`BaseEncodeType`](../baseencodetype/) 值。 |
| override [GetHashCode](../../aspose.barcode.generation/baseencodetype/gethashcode/)() | 返回此实例的哈希码。 |
| [GetString](../../aspose.barcode.generation/baseencodetype/getstring/)() | 将 BaseEncodeType 的实例转换为等效的字符串表示。字符串格式为："Index:0; Name:Codabar"。 |
| override [ToString](../../aspose.barcode.generation/baseencodetype/tostring/)() | 返回给定 BaseEncodeType 的名称字符串。 |

## 示例

此示例展示如何获取 SymbologyEncodeType 类的实例。

```csharp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR 
 
[VB.NET]
Dim symbologyType As SymbologyEncodeType 
symbologyType = EncodeTypes.QR
```

### 另见

* class [BaseEncodeType](../baseencodetype/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


