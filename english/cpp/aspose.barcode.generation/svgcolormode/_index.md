---
title:  enum
linktitle: SvgColorMode
second_title: Aspose.BarCode for C++ API Reference
description: ' enum. Possible modes for filling color in svg file, RGB is default and supported by SVG 1.1. RGBA, HSL, HSLA is allowed in SVG 2.0 standard. Even in RGB opacity will be set through "fill-opacity" parameter in C++.'
type: docs
weight: 8100
url: /cpp/aspose.barcode.generation/svgcolormode/
---
## SvgColorMode enum


Possible modes for filling color in svg file, RGB is default and supported by SVG 1.1. RGBA, HSL, HSLA is allowed in SVG 2.0 standard. Even in RGB opacity will be set through "fill-opacity" parameter

```cpp
enum class SvgColorMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| RGB | 0 | RGB mode, example: fill="#ff5511" fill-opacity="0.73". Default mode. |
| RGBA | 1 | RGBA mode, example: fill="rgba(255, 85, 17, 0.73)" |
| HSL | 2 | HSL mode, example: fill="hsl(17, 100%, 53%)" fill-opacity="0.73" |
| HSLA | 3 | HSLA mode, example: fill="hsla(30, 50%, 70%, 0.8)" |

## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
