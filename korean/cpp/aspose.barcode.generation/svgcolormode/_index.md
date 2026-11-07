---
title: "enum"
linktitle: "SvgColorMode"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " enum. svg 파일에서 색을 채우는 가능한 모드이며, RGB가 기본이며 SVG 1.1에서 지원됩니다. RGBA, HSL, HSLA는 SVG 2.0 표준에서 허용됩니다. RGB에서도 불투명도는 C++의 \"fill-opacity\" 매개변수를 통해 설정됩니다."
type: docs
weight: 8500
url: /ko/cpp/aspose.barcode.generation/svgcolormode/
---
## SvgColorMode enum


svg 파일에서 색을 채우는 가능한 모드이며, RGB가 기본이며 SVG 1.1에서 지원됩니다. RGBA, HSL, HSLA는 SVG 2.0 표준에서 허용됩니다. RGB에서도 불투명도는 "fill-opacity" 매개변수를 통해 설정됩니다.

```cpp
enum class SvgColorMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| RGB | 0 | RGB 모드, 예: fill="#ff5511" fill-opacity="0.73". 기본 모드. |
| RGBA | 1 | RGBA 모드, 예: fill="rgba(255, 85, 17, 0.73)" |
| HSL | 2 | HSL 모드, 예: fill="hsl(17, 100%, 53%)" fill-opacity="0.73" |
| HSLA | 3 | HSLA 모드, 예: fill="hsla(30, 50%, 70%, 0.8)" |

## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
