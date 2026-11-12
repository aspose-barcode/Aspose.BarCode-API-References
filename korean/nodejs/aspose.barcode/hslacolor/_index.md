---
title: "HslaColor"
linktitle: "HslaColor"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "HSLA 색상(색조, 채도, 밝기, 알파)를 나타내는 클래스"
type: docs
weight: 520
url: /ko/nodejs/aspose.barcode/hslacolor/
---

## HslaColor class

HSLA 색상(색조, 채도, 밝기, 알파)를 나타내는 클래스

```js
new HslaColor(h, s, l, a)
```

HslaColor의 생성자

| 매개변수 | 설명 |
| --- | --- |
| h | 색조 [0, 360] |
| s | 채도 [0, 100] |
| l | 명도 [0, 100] |
| a | 알파(불투명도) [0.0f, 1.0f] |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [convertHslaToRgba(hslaColor)](#converthslatorgba) *(static)* | 사용합니다 https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB |

### convertHslaToRgba(hslaColor) (static) {#converthslatorgba}

사용합니다 https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB

| 매개변수 | 설명 |
| --- | --- |
| hslaColor | 변환할 HSLA 색상 |

**Returns:** string with RGBA values
