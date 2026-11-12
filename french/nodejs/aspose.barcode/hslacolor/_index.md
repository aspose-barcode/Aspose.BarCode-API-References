---
title: "HslaColor"
linktitle: "HslaColor"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Classe représentant la couleur HSLA (Teinte, Saturation, Luminosité, Alpha)"
type: docs
weight: 520
url: /fr/nodejs/aspose.barcode/hslacolor/
---

## HslaColor class

Classe représentant la couleur HSLA (Teinte, Saturation, Luminosité, Alpha)

```js
new HslaColor(h, s, l, a)
```

Constructeur pour HslaColor

| Paramètre | Description |
| --- | --- |
| h | Teinte [0, 360] |
| s | Saturation [0, 100] |
| l | Luminosité [0, 100] |
| a | Alpha (opacité) [0.0f, 1.0f] |

## Méthodes

| Nom | Description |
| --- | --- |
| [convertHslaToRgba(hslaColor)](#converthslatorgba) *(static)* | Utilise https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB |

### convertHslaToRgba(hslaColor) (static) {#converthslatorgba}

Utilise https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB

| Paramètre | Description |
| --- | --- |
| hslaColor | Couleur HSLA à convertir |

**Returns:** string with RGBA values
