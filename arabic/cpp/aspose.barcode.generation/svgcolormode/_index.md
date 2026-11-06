---
title: "enum"
linktitle: "SvgColorMode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " enum. أوضاع محتملة لملء اللون في ملف svg، RGB هو الافتراضي ومدعوم من SVG 1.1. RGBA و HSL و HSLA مسموح بها في معيار SVG 2.0. حتى في RGB سيتم ضبط الشفافية عبر معامل \"fill-opacity\" في C++."
type: docs
weight: 8500
url: /ar/cpp/aspose.barcode.generation/svgcolormode/
---
## SvgColorMode enum


الوضعيات الممكنة لملء اللون في ملف svg، RGB هو الافتراضي ومدعوم من SVG 1.1. RGBA و HSL و HSLA مسموح بها في معيار SVG 2.0. حتى في RGB سيتم ضبط الشفافية عبر المعامل "fill-opacity".

```cpp
enum class SvgColorMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| RGB | 0 | وضع RGB، مثال: fill="#ff5511" fill-opacity="0.73". الوضع الافتراضي. |
| RGBA | 1 | وضع RGBA، مثال: fill="rgba(255, 85, 17, 0.73)" |
| HSL | 2 | وضع HSL، مثال: fill="hsl(17, 100%, 53%)" fill-opacity="0.73" |
| HSLA | 3 | وضع HSLA، مثال: fill="hsla(30, 50%, 70%, 0.8)" |

## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
