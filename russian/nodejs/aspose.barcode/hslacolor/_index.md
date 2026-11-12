---
title: "HslaColor"
linktitle: "HslaColor"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Класс для представления цвета HSLA (Hue, Saturation, Lightness, Alpha)"
type: docs
weight: 520
url: /ru/nodejs/aspose.barcode/hslacolor/
---

## HslaColor class

Класс для представления цвета HSLA (Hue, Saturation, Lightness, Alpha)

```js
new HslaColor(h, s, l, a)
```

Конструктор для HslaColor

| Параметр | Описание |
| --- | --- |
| h | Оттенок [0, 360] |
| s | Насыщенность [0, 100] |
| l | Светлота [0, 100] |
| a | Alpha (непрозрачность) [0.0f, 1.0f] |

## Методы

| Имя | Описание |
| --- | --- |
| [convertHslaToRgba(hslaColor)](#converthslatorgba) *(static)* | Использует https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB |

### convertHslaToRgba(hslaColor) (static) {#converthslatorgba}

Использует https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB

| Параметр | Описание |
| --- | --- |
| hslaColor | HSLA цвет для преобразования |

**Returns:** string with RGBA values
