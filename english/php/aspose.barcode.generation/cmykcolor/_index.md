---
title: "CMYKColor"
linktitle: "CMYKColor"
second_title: "Aspose.BarCode for PHP via Java"
description: "Class for CMYK color. A null instance means CMYK is not used, and default RGB color is in use."
type: docs
weight: 10
url: /php/aspose.barcode.generation/cmykcolor/
---

## CMYKColor class

**Namespace:** `Aspose.Barcode.Generation`


Class for CMYK color. A null instance means CMYK is not used, and default RGB color is in use.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) | Initializes a new instance of the CMYKColor class from CMYK values. CMYK values are expected in the range 0–100. |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [formatCMYK](#formatcmyk) | No | Format this CMYKColor into a string "C_M_Y_K", multiplying each internal component (0–1) by 100 and rounding. |
| [parseCMYK](#parsecmyk) | Yes | Parse a CMYK string of the form "C_M_Y_K" into a CMYKColor instance. |

### CMYKColor__construct(int $c, int $m, int $y, int $k) {#constructor}

Initializes a new instance of the CMYKColor class from CMYK values. CMYK values are expected in the range 0–100.

| Parameter | Type | Description |
| --- | --- | --- |
| `$c` | `int` |  |
| `$m` | `int` |  |
| `$y` | `int` |  |
| `$k` | `int` |  |

### formatCMYKformatCMYK() {#formatcmyk}

Format this CMYKColor into a string "C_M_Y_K", multiplying each internal component (0–1) by 100 and rounding.

**Returns:** string e.g. "30_100_0_30"

### parseCMYKparseCMYK(string $str) (static) {#parsecmyk}

Parse a CMYK string of the form "C_M_Y_K" into a CMYKColor instance.

| Parameter | Type | Description |
| --- | --- | --- |
| `$str` | `string` |  |

**Returns:** CMYKColor

