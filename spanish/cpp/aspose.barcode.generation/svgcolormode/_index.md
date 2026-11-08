---
title: "enum"
linktitle: "SvgColorMode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " enum. Modos posibles para rellenar color en un archivo svg, RGB es predeterminado y compatible con SVG 1.1. RGBA, HSL, HSLA están permitidos en la norma SVG 2.0. Incluso en RGB la opacidad se establecerá mediante el parámetro \"fill-opacity\" en C++."
type: docs
weight: 8500
url: /es/cpp/aspose.barcode.generation/svgcolormode/
---
## SvgColorMode enum


Modos posibles para rellenar color en un archivo svg, RGB es el predeterminado y es compatible con SVG 1.1. RGBA, HSL, HSLA están permitidos en el estándar SVG 2.0. Incluso en RGB la opacidad se establecerá mediante el parámetro "fill-opacity".

```cpp
enum class SvgColorMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| RGB | 0 | Modo RGB, ejemplo: fill="#ff5511" fill-opacity="0.73". Modo predeterminado. |
| RGBA | 1 | Modo RGBA, ejemplo: fill="rgba(255, 85, 17, 0.73)" |
| HSL | 2 | Modo HSL, ejemplo: fill="hsl(17, 100%, 53%)" fill-opacity="0.73" |
| HSLA | 3 | Modo HSLA, ejemplo: fill="hsla(30, 50%, 70%, 0.8)" |

## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
