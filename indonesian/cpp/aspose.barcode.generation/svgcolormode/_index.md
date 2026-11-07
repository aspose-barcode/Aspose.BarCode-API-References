---
title: "enum"
linktitle: "SvgColorMode"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " enum. Mode yang mungkin untuk mengisi warna dalam file svg, RGB adalah default dan didukung oleh SVG 1.1. RGBA, HSL, HSLA diizinkan dalam standar SVG 2.0. Bahkan dalam RGB opasitas akan diatur melalui parameter \"fill-opacity\" dalam C++."
type: docs
weight: 8500
url: /id/cpp/aspose.barcode.generation/svgcolormode/
---
## SvgColorMode enum


Mode yang memungkinkan untuk mengisi warna dalam file svg, RGB adalah default dan didukung oleh SVG 1.1. RGBA, HSL, HSLA diizinkan dalam standar SVG 2.0. Bahkan dalam RGB opasitas akan diatur melalui parameter "fill-opacity".

```cpp
enum class SvgColorMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| RGB | 0 | Mode RGB, contoh: fill="#ff5511" fill-opacity="0.73". Mode default. |
| RGBA | 1 | Mode RGBA, contoh: fill="rgba(255, 85, 17, 0.73)" |
| HSL | 2 | Mode HSL, contoh: fill="hsl(17, 100%, 53%)" fill-opacity="0.73" |
| HSLA | 3 | Mode HSLA, contoh: fill="hsla(30, 50%, 70%, 0.8)" |

## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
