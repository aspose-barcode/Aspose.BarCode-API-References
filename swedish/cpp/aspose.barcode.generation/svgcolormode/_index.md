---
title: "enum"
linktitle: "SvgColorMode"
second_title: "Aspose.BarCode for C++ API-referens"
description: " enum. Möjliga lägen för färgfyllning i svg-fil, RGB är standard och stöds av SVG 1.1. RGBA, HSL, HSLA är tillåtna i SVG 2.0-standarden. Även i RGB kommer opacitet att sättas via parametern \"fill-opacity\" i C++."
type: docs
weight: 8500
url: /sv/cpp/aspose.barcode.generation/svgcolormode/
---
## SvgColorMode enum


Möjliga lägen för färgfyllning i svg-fil, RGB är standard och stöds av SVG 1.1. RGBA, HSL, HSLA är tillåtna i SVG 2.0-standarden. Även i RGB sätts opacitet via parametern "fill-opacity".

```cpp
enum class SvgColorMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| RGB | 0 | RGB-läge, exempel: fill="#ff5511" fill-opacity="0.73". Standardläge. |
| RGBA | 1 | RGBA-läge, exempel: fill="rgba(255, 85, 17, 0.73)" |
| HSL | 2 | HSL-läge, exempel: fill="hsl(17, 100%, 53%)" fill-opacity="0.73" |
| HSLA | 3 | HSLA-läge, exempel: fill="hsla(30, 50%, 70%, 0.8)" |

## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
