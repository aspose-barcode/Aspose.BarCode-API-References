---
title: "类 FontUnit"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.FontUnit 类。定义文本的特定格式，包括字体大小和样式属性，其中大小在 Unit 值属性中。"
type: docs
weight: 1320
url: /zh/net/aspose.barcode.generation/fontunit/
---
## FontUnit class

定义文本的特定格式，包括字体、大小和样式属性，其中大小在 Unit 值属性中。

```csharp
public sealed class FontUnit
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [FamilyName](../../aspose.barcode.generation/fontunit/familyname/) { get; set; } | 获取或设置此 Font 的字体名称。 |
| [Size](../../aspose.barcode.generation/fontunit/size/) { get; } | 获取或设置此 FontUnit 在 Unit 值中的大小。 |
| [Style](../../aspose.barcode.generation/fontunit/style/) { get; set; } | 获取或设置此 FontUnit 的样式信息。 |

## 示例

此示例展示如何创建并保存条形码图像。

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


