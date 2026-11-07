---
title: "enum"
linktitle: "SvgColorMode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " enum. Modalità possibili per riempire il colore in un file svg, RGB è predefinito e supportato da SVG 1.1. RGBA, HSL, HSLA sono consentiti nello standard SVG 2.0. Anche in RGB l'opacità verrà impostata tramite il parametro \"fill-opacity\" in C++."
type: docs
weight: 8500
url: /it/cpp/aspose.barcode.generation/svgcolormode/
---
## SvgColorMode enum


Modalità possibili per il riempimento del colore in un file svg, RGB è predefinito e supportato da SVG 1.1. RGBA, HSL, HSLA sono consentiti nello standard SVG 2.0. Anche in RGB l'opacità sarà impostata tramite il parametro \"fill-opacity\"

```cpp
enum class SvgColorMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| RGB | 0 | Modalità RGB, esempio: fill="#ff5511" fill-opacity="0.73". Modalità predefinita. |
| RGBA | 1 | Modalità RGBA, esempio: fill="rgba(255, 85, 17, 0.73)" |
| HSL | 2 | Modalità HSL, esempio: fill="hsl(17, 100%, 53%)" fill-opacity="0.73" |
| HSLA | 3 | Modalità HSLA, esempio: fill="hsla(30, 50%, 70%, 0.8)" |

## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
