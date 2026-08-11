---
title: "CMYKColor"
linktitle: "CMYKColor"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Class for CMYK color."
type: docs
weight: 180
url: /nodejs/aspose.barcode/cmykcolor/
---

## CMYKColor class

Class for CMYK color. A null instance means CMYK is not used, and default RGB color is in use.

```js
new CMYKColor(c, m, y, k)
```

Initializes a new instance of the CMYKColor class from CMYK values. CMYK values are expected in the range 0–100.

| Parameter | Type | Description |
| --- | --- | --- |
| c | number | – Cyan value [0, 100] |
| m | number | – Magenta value [0, 100] |
| y | number | – Yellow value [0, 100] |
| k | number | – Black value [0, 100] |

## Methods

| Name | Description |
| --- | --- |
| [parseCMYK(str)](#parsecmyk) *(static)* | Parse a CMYK string of the form "C_M_Y_K" into a CMYKColor instance. |
| [formatCMYK()](#formatcmyk) | Format this CMYKColor into a string "C_M_Y_K", multiplying each internal component (0–1) by 100 and rounding. |
| [toString()](#tostring) | Optional: a human-readable representation. |

### parseCMYK(str) (static) {#parsecmyk}

Parse a CMYK string of the form "C_M_Y_K" into a CMYKColor instance.

| Parameter | Type | Description |
| --- | --- | --- |
| str | string | – a string like "30_100_0_30" |

**Returns:** CMYKColor

### formatCMYK() {#formatcmyk}

Format this CMYKColor into a string "C_M_Y_K", multiplying each internal component (0–1) by 100 and rounding.

**Returns:** string — e.g. "30_100_0_30"

### toString() {#tostring}

Optional: a human-readable representation.
