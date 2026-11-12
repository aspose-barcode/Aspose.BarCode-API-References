---
title: "CMYKColor"
linktitle: "CMYKColor"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "CMYK 颜色的类。"
type: docs
weight: 180
url: /zh/nodejs/aspose.barcode/cmykcolor/
---

## CMYKColor class

用于 CMYK 颜色的类。空实例表示不使用 CMYK，使用默认的 RGB 颜色。

```js
new CMYKColor(c, m, y, k)
```

使用 CMYK 值初始化 CMYKColor 类的新实例。CMYK 值的范围应为 0–100。

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | 数字 | – 青色值 [0, 100] |
| m | 数字 | – 品红值 [0, 100] |
| y | 数字 | – 黄色值 [0, 100] |
| k | 数字 | – 黑色值 [0, 100] |

## 方法

| 名称 | 描述 |
| --- | --- |
| [parseCMYK(str)](#parsecmyk) *(static)* | 解析形式为 "C_M_Y_K" 的 CMYK 字符串为 CMYKColor 实例。 |
| [formatCMYK()](#formatcmyk) | 将此 CMYKColor 格式化为字符串 "C_M_Y_K"，将每个内部组件（0–1）乘以 100 并四舍五入。 |
| [toString()](#tostring) | 可选：人类可读的表示。 |

### parseCMYK(str) (static) {#parsecmyk}

解析形式为 "C_M_Y_K" 的 CMYK 字符串为 CMYKColor 实例。

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | string | – 类似 "30_100_0_30" 的字符串 |

**Returns:** CMYKColor

### formatCMYK() {#formatcmyk}

将此 CMYKColor 格式化为字符串 "C_M_Y_K"，将每个内部组件（0–1）乘以 100 并四舍五入。

**Returns:** string — e.g. "30_100_0_30"

### toString() {#tostring}

可选：人类可读的表示。
