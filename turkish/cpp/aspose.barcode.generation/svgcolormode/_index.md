---
title: "enum"
linktitle: "SvgColorMode"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " enum. SVG dosyasında renk doldurma için olası modlar, RGB varsayılan olup SVG 1.1 tarafından desteklenir. RGBA, HSL, HSLA SVG 2.0 standardında izin verilir. RGB'de bile opaklık C++'ta \"fill-opacity\" parametresi ile ayarlanır."
type: docs
weight: 8500
url: /tr/cpp/aspose.barcode.generation/svgcolormode/
---
## SvgColorMode enum


svg dosyasında renk doldurma için olası modlar, RGB varsayılan olup SVG 1.1 tarafından desteklenir. RGBA, HSL, HSLA SVG 2.0 standardında izin verilir. RGB'de bile opaklık \"fill-opacity\" parametresiyle ayarlanır.

```cpp
enum class SvgColorMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| RGB | 0 | RGB modu, örnek: fill=\"#ff5511\" fill-opacity=\"0.73\". Varsayılan mod. |
| RGBA | 1 | RGBA modu, örnek: fill=\"rgba(255, 85, 17, 0.73)\" |
| HSL | 2 | HSL modu, örnek: fill=\"hsl(17, 100%, 53%)\" fill-opacity=\"0.73\" |
| HSLA | 3 | HSLA modu, örnek: fill=\"hsla(30, 50%, 70%, 0.8)\" |

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
