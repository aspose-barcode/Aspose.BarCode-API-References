---
title: "类 Unit"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.Unit 类。指定不同单位（像素、英寸等）中的尺寸值"
type: docs
weight: 1740
url: /zh/net/aspose.barcode.generation/unit/
---
## Unit class

指定不同单位（像素、英寸等）中的尺寸值。

```csharp
public sealed class Unit
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Document](../../aspose.barcode.generation/unit/document/) { get; set; } | 获取或设置文档单位中的尺寸值。 |
| [Inches](../../aspose.barcode.generation/unit/inches/) { get; set; } | 获取或设置英寸中的尺寸值。 |
| [Millimeters](../../aspose.barcode.generation/unit/millimeters/) { get; set; } | 获取或设置毫米中的尺寸值。 |
| [Pixels](../../aspose.barcode.generation/unit/pixels/) { get; set; } | 获取或设置像素中的尺寸值。 |
| [Point](../../aspose.barcode.generation/unit/point/) { get; set; } | 获取或设置点单位中的尺寸值。 |
| [Resolution](../../aspose.barcode.generation/unit/resolution/) { get; } | 分辨率 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.barcode.generation/unit/equals/)(object) | 确定此实例和指定对象（该对象也必须是 `Unit` 对象）是否具有相同的值。 |
| override [GetHashCode](../../aspose.barcode.generation/unit/gethashcode/)() | 返回此对象的哈希码。 |
| override [ToString](../../aspose.barcode.generation/unit/tostring/)() | 返回此 `Unit` 的人类可读字符串表示。 |

## 示例

此示例展示如何创建并保存条形码图像。

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


