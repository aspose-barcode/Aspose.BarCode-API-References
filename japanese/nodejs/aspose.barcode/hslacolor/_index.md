---
title: "HslaColor"
linktitle: "HslaColor"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "HSLA カラー（色相、彩度、明度、アルファ）を表すクラス"
type: docs
weight: 520
url: /ja/nodejs/aspose.barcode/hslacolor/
---

## HslaColor class

HSLA カラー（色相、彩度、明度、アルファ）を表すクラス

```js
new HslaColor(h, s, l, a)
```

HslaColor のコンストラクタ

| パラメータ | 説明 |
| --- | --- |
| h | 色相 [0, 360] |
| s | 彩度 [0, 100] |
| l | 明度 [0, 100] |
| a | アルファ (不透明度) [0.0f, 1.0f] |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [convertHslaToRgba(hslaColor)](#converthslatorgba) *(static)* | 使用します https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB |

### convertHslaToRgba(hslaColor) (static) {#converthslatorgba}

使用します https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB

| パラメータ | 説明 |
| --- | --- |
| hslaColor | 変換する HSLA カラー |

**Returns:** string with RGBA values
