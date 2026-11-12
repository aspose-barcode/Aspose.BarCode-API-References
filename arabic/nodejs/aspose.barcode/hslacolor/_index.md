---
title: "HslaColor"
linktitle: "HslaColor"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "فئة لتمثيل لون HSLA (الدرجة، التشبع، الإضاءة، الشفافية)"
type: docs
weight: 520
url: /ar/nodejs/aspose.barcode/hslacolor/
---

## HslaColor class

فئة لتمثيل لون HSLA (الدرجة، التشبع، الإضاءة، الشفافية)

```js
new HslaColor(h, s, l, a)
```

منشئ لـ HslaColor

| معامل | الوصف |
| --- | --- |
| h | درجة اللون [0, 360] |
| s | التشبع [0, 100] |
| l | الإضاءة [0, 100] |
| a | ألفا (الشفافية) [0.0f, 1.0f] |

## طرق

| اسم | الوصف |
| --- | --- |
| [convertHslaToRgba(hslaColor)](#converthslatorgba) *(static)* | يستخدم https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB |

### convertHslaToRgba(hslaColor) (static) {#converthslatorgba}

يستخدم https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB

| معامل | الوصف |
| --- | --- |
| hslaColor | لون HSLA للتحويل |

**Returns:** string with RGBA values
