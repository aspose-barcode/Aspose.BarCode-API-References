---
title: "Перечисление SvgColorMode"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Перечисление Aspose.BarCode.Generation.SvgColorMode. Возможные режимы заполнения цвета в файле svg: RGB по умолчанию и поддерживается в SVG 1.1. RGBA, HSL, HSLA допускаются в стандарте SVG 2.0. Даже в RGB непрозрачность будет задаваться параметром fillopacity."
type: docs
weight: 1690
url: /ru/net/aspose.barcode.generation/svgcolormode/
---
## SvgColorMode enumeration

Возможные режимы заполнения цвета в файле svg, по умолчанию RGB, поддерживается SVG 1.1. RGBA, HSL, HSLA разрешены в стандарте SVG 2.0. Даже в RGB непрозрачность будет задаваться параметром "fill-opacity".

```csharp
public enum SvgColorMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| RGB | `0` | RGB режим, пример: fill="#ff5511" fill-opacity="0.73". Режим по умолчанию. |
| RGBA | `1` | RGBA режим, пример: fill="rgba(255, 85, 17, 0.73)" |
| HSL | `2` | HSL режим, пример: fill="hsl(17, 100%, 53%)" fill-opacity="0.73" |
| HSLA | `3` | HSLA режим, пример: fill="hsla(30, 50%, 70%, 0.8)" |

### См. также

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


