---
title: "HslaColor"
linktitle: "HslaColor"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Klass för att representera HSLA-färg (Hue, Saturation, Lightness, Alpha)"
type: docs
weight: 520
url: /sv/nodejs/aspose.barcode/hslacolor/
---

## HslaColor class

Klass för att representera HSLA-färg (Hue, Saturation, Lightness, Alpha)

```js
new HslaColor(h, s, l, a)
```

Konstruktor för HslaColor

| Parameter | Beskrivning |
| --- | --- |
| h | Nyans [0, 360] |
| s | Mättnad [0, 100] |
| l | Ljusstyrka [0, 100] |
| a | Alfa (opacitet) [0.0f, 1.0f] |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [convertHslaToRgba(hslaColor)](#converthslatorgba) *(static)* | Använder https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB |

### convertHslaToRgba(hslaColor) (static) {#converthslatorgba}

Använder https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB

| Parameter | Beskrivning |
| --- | --- |
| hslaColor | HSLA-färg att konvertera |

**Returns:** string with RGBA values
