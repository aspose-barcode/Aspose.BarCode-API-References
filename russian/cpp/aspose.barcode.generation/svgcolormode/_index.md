---
title: "enum"
linktitle: "SvgColorMode"
second_title: "Aspose.BarCode для C++ справочник API"
description: " enum. Возможные режимы заполнения цвета в SVG‑файле, RGB является значением по умолчанию и поддерживается SVG 1.1. RGBA, HSL, HSLA допускаются в стандарте SVG 2.0. Даже в RGB непрозрачность будет задаваться параметром \"fill-opacity\" в C++."
type: docs
weight: 8500
url: /ru/cpp/aspose.barcode.generation/svgcolormode/
---
## SvgColorMode enum


Возможные режимы заполнения цвета в файле svg, RGB является значением по умолчанию и поддерживается SVG 1.1. RGBA, HSL, HSLA допускаются в стандарте SVG 2.0. Даже в RGB непрозрачность задаётся параметром "fill-opacity".

```cpp
enum class SvgColorMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| RGB | 0 | Режим RGB, пример: fill="#ff5511" fill-opacity="0.73". Режим по умолчанию. |
| RGBA | 1 | Режим RGBA, пример: fill="rgba(255, 85, 17, 0.73)" |
| HSL | 2 | Режим HSL, пример: fill="hsl(17, 100%, 53%)" fill-opacity="0.73" |
| HSLA | 3 | Режим HSLA, пример: fill="hsla(30, 50%, 70%, 0.8)" |

## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
