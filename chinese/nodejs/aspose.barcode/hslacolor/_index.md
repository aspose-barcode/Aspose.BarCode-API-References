---
title: "HslaColor"
linktitle: "HslaColor"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于表示 HSLA 颜色（色相、饱和度、亮度、透明度）的类。"
type: docs
weight: 520
url: /zh/nodejs/aspose.barcode/hslacolor/
---

## HslaColor class

用于表示 HSLA 颜色（色相、饱和度、亮度、透明度）的类。

```js
new HslaColor(h, s, l, a)
```

HslaColor 的构造函数

| 参数 | 描述 |
| --- | --- |
| h | 色相 [0, 360] |
| s | 饱和度 [0, 100] |
| l | 亮度 [0, 100] |
| a | Alpha（不透明度）[0.0f, 1.0f] |

## 方法

| 名称 | 描述 |
| --- | --- |
| [convertHslaToRgba(hslaColor)](#converthslatorgba) *(static)* | 使用 https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB |

### convertHslaToRgba(hslaColor) (static) {#converthslatorgba}

使用 https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB

| 参数 | 描述 |
| --- | --- |
| hslaColor | 要转换的 HSLA 颜色 |

**Returns:** string with RGBA values
