---
title: "枚举 TwoDComponentType"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.TwoDComponentType 枚举。2D 组件的类型"
type: docs
weight: 1730
url: /zh/net/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enumeration

2D 组件的类型

```csharp
public enum TwoDComponentType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | `0` | 自动选择 2D 组件类型 |
| CC_A | `1` | CC-A 类型的 2D 组件。它是 MicroPDF417 的结构变体 |
| CC_B | `2` | CC-B 类型的 2D 组件。它是 MicroPDF417 符号。 |
| CC_C | `3` | CC-C 类型的 2D 组件。它是 PDF417 符号。 |

## 示例

此示例展示了如何创建并保存 GS1 复合条形码图像。请注意，1D 编码文本和 2D 编码文本由符号 '/' 分隔。

```csharp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
{
    generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
    generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
    
    // 2D 组件的宽高比
    generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
        
    // 1D 和 2D 组件的 X 维度
    generator.Parameters.Barcode.XDimension.Pixels = 3;
        
    // 1D 组件的高度
    generator.Parameters.Barcode.BarHeight.Pixels = 100;
    
    generator.Save("test.png");
}
```

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


