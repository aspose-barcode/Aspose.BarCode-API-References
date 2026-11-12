---
title: "HslaColor"
linktitle: "HslaColor"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Clase para representar el color HSLA (Hue, Saturation, Lightness, Alpha)"
type: docs
weight: 520
url: /es/nodejs/aspose.barcode/hslacolor/
---

## HslaColor class

Clase para representar el color HSLA (Hue, Saturation, Lightness, Alpha)

```js
new HslaColor(h, s, l, a)
```

Constructor para HslaColor

| Parámetro | Descripción |
| --- | --- |
| h | Matiz [0, 360] |
| s | Saturación [0, 100] |
| l | Luminosidad [0, 100] |
| a | Alfa (opacidad) [0.0f, 1.0f] |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [convertHslaToRgba(hslaColor)](#converthslatorgba) *(static)* | Utiliza https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB |

### convertHslaToRgba(hslaColor) (static) {#converthslatorgba}

Utiliza https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB

| Parámetro | Descripción |
| --- | --- |
| hslaColor | Color HSLA a convertir |

**Returns:** string with RGBA values
