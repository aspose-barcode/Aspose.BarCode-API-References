---
title: "CMYKColor"
linktitle: "CMYKColor"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "CMYK 색상에 대한 클래스."
type: docs
weight: 180
url: /ko/nodejs/aspose.barcode/cmykcolor/
---

## CMYKColor class

CMYK 색상에 대한 클래스입니다. null 인스턴스는 CMYK가 사용되지 않으며 기본 RGB 색상이 사용됨을 의미합니다.

```js
new CMYKColor(c, m, y, k)
```

CMYK 값을 사용하여 CMYKColor 클래스의 새 인스턴스를 초기화합니다. CMYK 값은 0–100 범위여야 합니다.

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| c | 숫자 | – 시안 값 [0, 100] |
| m | 숫자 | – 마젠타 값 [0, 100] |
| y | 숫자 | – 옐로우 값 [0, 100] |
| k | 숫자 | – 블랙 값 [0, 100] |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [parseCMYK(str)](#parsecmyk) *(static)* | 형식이 "C_M_Y_K"인 CMYK 문자열을 CMYKColor 인스턴스로 구문 분석합니다. |
| [formatCMYK()](#formatcmyk) | 이 CMYKColor를 문자열 "C_M_Y_K"로 포맷하고, 각 내부 구성 요소(0–1)를 100배하고 반올림합니다. |
| [toString()](#tostring) | 선택 사항: 사람이 읽을 수 있는 표현. |

### parseCMYK(str) (static) {#parsecmyk}

형식이 "C_M_Y_K"인 CMYK 문자열을 CMYKColor 인스턴스로 구문 분석합니다.

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | string | – "30_100_0_30"와 같은 문자열 |

**Returns:** CMYKColor

### formatCMYK() {#formatcmyk}

이 CMYKColor를 문자열 "C_M_Y_K"로 포맷하고, 각 내부 구성 요소(0–1)를 100배하고 반올림합니다.

**Returns:** string — e.g. "30_100_0_30"

### toString() {#tostring}

선택 사항: 사람이 읽을 수 있는 표현.
