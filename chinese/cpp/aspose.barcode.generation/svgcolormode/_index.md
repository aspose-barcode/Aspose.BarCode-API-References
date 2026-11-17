---
title: "枚举"
linktitle: "SvgColorMode"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 枚举。svg 文件中填充颜色的可能模式，RGB 为默认并受 SVG 1.1 支持。RGBA、HSL、HSLA 在 SVG 2.0 标准中被允许。即使是 RGB，透明度也将在 C++ 中通过 \"fill-opacity\" 参数设置。"
type: docs
weight: 8500
url: /zh/cpp/aspose.barcode.generation/svgcolormode/
---
## SvgColorMode enum


svg 文件中填充颜色的可能模式，RGB 为默认并受 SVG 1.1 支持。RGBA、HSL、HSLA 在 SVG 2.0 标准中被允许。即使在 RGB 中，不透明度也将通过 "fill-opacity" 参数设置。

```cpp
enum class SvgColorMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| RGB | 0 | RGB 模式，示例：fill=\"#ff5511\" fill-opacity=\"0.73\"。默认模式。 |
| RGBA | 1 | RGBA 模式，示例：fill=\"rgba(255, 85, 17, 0.73)\" |
| HSL | 2 | HSL 模式，示例：fill=\"hsl(17, 100%, 53%)\" fill-opacity=\"0.73\" |
| HSLA | 3 | HSLA 模式，示例：fill=\"hsla(30, 50%, 70%, 0.8)\" |

## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
