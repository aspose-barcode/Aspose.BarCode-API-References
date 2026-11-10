---
title: "BarcodeParameters.GS1CompositeBar"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BarcodeParameters 属性。GS1 Composite Bar 参数"
type: docs
weight: 180
url: /zh/net/aspose.barcode.generation/barcodeparameters/gs1compositebar/
---
## BarcodeParameters.GS1CompositeBar property

GS1 复合条参数。

```csharp
public GS1CompositeBarParameters GS1CompositeBar { get; set; }
```

## 示例

此示例展示了如何创建并保存 GS1 Composite Bar 图像。请注意，1D codetext 和 2D codetext 由符号 '&#x7C;' 分隔

```csharp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
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

* class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* class [BarcodeParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


