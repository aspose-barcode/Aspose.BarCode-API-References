---
title: "enum"
linktitle: "SvgColorMode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " enum. Mögliche Modi zum Füllen von Farben in einer SVG-Datei, RGB ist Standard und wird von SVG 1.1 unterstützt. RGBA, HSL, HSLA sind im SVG 2.0-Standard erlaubt. Selbst bei RGB wird die Transparenz über den Parameter \"fill-opacity\" in C++ gesetzt."
type: docs
weight: 8500
url: /de/cpp/aspose.barcode.generation/svgcolormode/
---
## SvgColorMode enum


Mögliche Modi zum Füllen von Farben in SVG-Dateien, RGB ist Standard und wird von SVG 1.1 unterstützt. RGBA, HSL, HSLA sind im SVG 2.0-Standard erlaubt. Auch bei RGB wird die Deckkraft über den Parameter "fill-opacity" gesetzt.

```cpp
enum class SvgColorMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| RGB | 0 | RGB-Modus, Beispiel: fill="#ff5511" fill-opacity="0.73". Standardmodus. |
| RGBA | 1 | RGBA-Modus, Beispiel: fill="rgba(255, 85, 17, 0.73)" |
| HSL | 2 | HSL-Modus, Beispiel: fill="hsl(17, 100%, 53%)" fill-opacity="0.73" |
| HSLA | 3 | HSLA-Modus, Beispiel: fill="hsla(30, 50%, 70%, 0.8)" |

## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
