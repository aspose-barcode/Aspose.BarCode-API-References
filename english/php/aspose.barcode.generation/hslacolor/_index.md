---
title: "HslaColor"
linktitle: "HslaColor"
second_title: "Aspose.BarCode for PHP via Java"
description: "Class for representing HSLA color (Hue, Saturation, Lightness, Alpha)"
type: docs
weight: 10
url: /php/aspose.barcode.generation/hslacolor/
---

## HslaColor class

**Namespace:** `Aspose.Barcode.Generation`


Class for representing HSLA color (Hue, Saturation, Lightness, Alpha)


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) | Constructor for HslaColor |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [convertHslaToRgba](#converthslatorgba) | Yes | Uses https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB |

### HslaColor__construct(int $h, int $s, int $l, float $a) {#constructor}

Constructor for HslaColor

| Parameter | Type | Description |
| --- | --- | --- |
| `$h` | `int` | Hue [0, 360] |
| `$s` | `int` | Saturation [0, 100] |
| `$l` | `int` | Lightness [0, 100] |
| `$a` | `float` | Alpha (opacity) [0.0f, 1.0f] |

### convertHslaToRgbaconvertHslaToRgba(HslaColor $hslaColor) (static) {#converthslatorgba}

Uses https://en.wikipedia.org/wiki/HSL_and_HSV#HSL_to_RGB

| Parameter | Type | Description |
| --- | --- | --- |
| `$hslaColor` | `HslaColor` | HSLA color to convert |

**Returns:** string with RGBA values

