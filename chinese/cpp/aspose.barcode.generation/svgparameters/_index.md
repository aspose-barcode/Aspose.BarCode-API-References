---
title: "Aspose::BarCode::Generation::SvgParameters class"
linktitle: "SvgParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::SvgParameters class. C++ 中的 SVG 参数。"
type: docs
weight: 4800
url: /zh/cpp/aspose.barcode.generation/svgparameters/
---
## SvgParameters class


SVG 参数。

```cpp
class SvgParameters : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_IsExplicitSizeInPixels](./get_isexplicitsizeinpixels/)() const | SVG 图像是否包含像素单位的显式尺寸（推荐）。默认值：true。 |
| [get_IsTextDrawnInTextElement](./get_istextdrawnintextelement/)() const | SVG 图像是否将文本作为文本元素而非路径（推荐）。默认值：true。 |
| [get_SvgColorMode](./get_svgcolormode/)() const | svg 文件中填充颜色的可能模式，RGB 为默认并受 SVG 1.1 支持。RGBA、HSL、HSLA 在 SVG 2.0 标准中被允许。即使在 RGB 中，不透明度也将通过 "fill-opacity" 参数设置。 |
| [set_IsExplicitSizeInPixels](./set_isexplicitsizeinpixels/)(bool) | SVG 图像是否包含像素单位的显式尺寸（推荐）。默认值：true。 |
| [set_IsTextDrawnInTextElement](./set_istextdrawnintextelement/)(bool) | SVG 图像是否将文本作为文本元素而非路径（推荐）。默认值：true。 |
| [set_SvgColorMode](./set_svgcolormode/)(Aspose::BarCode::Generation::SvgColorMode) | svg 文件中填充颜色的可能模式，RGB 为默认并受 SVG 1.1 支持。RGBA、HSL、HSLA 在 SVG 2.0 标准中被允许。即使在 RGB 中，不透明度也将通过 "fill-opacity" 参数设置。 |
## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
