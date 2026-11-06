---
title: "method"
linktitle: "set_GS1CompositeBar"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。GS1 Composite Bar 参数在 C++ 中。"
type: docs
weight: 2600
url: /zh/cpp/aspose.barcode.generation/barcodeparameters/set_gs1compositebar/
---
## BarcodeParameters::set_GS1CompositeBar method


GS1 复合条参数。

```cpp
void Aspose::BarCode::Generation::BarcodeParameters::set_GS1CompositeBar(System::SharedPtr<GS1CompositeBarParameters> value)
```

## 备注


此示例展示了如何创建并保存 GS1 Composite Bar 图像。请注意，1D 编码文本和 2D 编码文本由符号 '|' 分隔。
```cpp
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

## 另见

* Class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* Class [BarcodeParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
