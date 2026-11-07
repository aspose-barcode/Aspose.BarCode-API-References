---
title: "enum"
linktitle: "SvgColorMode"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " enum. Mogelijke modi voor het vullen van kleur in een svg-bestand, RGB is standaard en wordt ondersteund door SVG 1.1. RGBA, HSL, HSLA zijn toegestaan in de SVG 2.0-standaard. Zelfs bij RGB wordt de opacity ingesteld via de \"fill-opacity\" parameter in C++."
type: docs
weight: 8500
url: /nl/cpp/aspose.barcode.generation/svgcolormode/
---
## SvgColorMode enum


Mogelijke modi voor het vullen van kleur in een svg‑bestand, RGB is standaard en wordt ondersteund door SVG 1.1. RGBA, HSL, HSLA zijn toegestaan in de SVG 2.0‑standaard. Zelfs bij RGB wordt de dekking ingesteld via de parameter "fill-opacity".

```cpp
enum class SvgColorMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| RGB | 0 | RGB-modus, voorbeeld: fill=\"#ff5511\" fill-opacity=\"0.73\". Standaardmodus. |
| RGBA | 1 | RGBA-modus, voorbeeld: fill=\"rgba(255, 85, 17, 0.73)\" |
| HSL | 2 | HSL-modus, voorbeeld: fill=\"hsl(17, 100%, 53%)\" fill-opacity=\"0.73\" |
| HSLA | 3 | HSLA-modus, voorbeeld: fill=\"hsla(30, 50%, 70%, 0.8)\" |

## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
