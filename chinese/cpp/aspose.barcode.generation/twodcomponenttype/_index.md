---
title: "枚举"
linktitle: "TwoDComponentType"
second_title: "Aspose.BarCode for C++ API 参考"
description: "枚举。2D 组件的类型，使用 C++。"
type: docs
weight: 8700
url: /zh/cpp/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enum


2D 组件的类型

```cpp
enum class TwoDComponentType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| 自动 | 0 | 自动选择 2D 组件的类型 |
| CC_A | 1 | CC-A 类型的 2D 组件。它是 MicroPDF417 的结构变体。 |
| CC_B | 2 | CC-B 类型的 2D 组件。它是 MicroPDF417 符号。 |
| CC_C | 3 | CC-C 类型的 2D 组件。它是 PDF417 符号。 |

## 备注


此示例展示了如何创建并保存 GS1 复合条码图像。请注意，1D 编码文本和 2D 编码文本由符号 '/' 分隔。
```cpp
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

## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
