---
title: "CodetextParameters"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode for Python via Java"
description: "Codetext parameters."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/codetextparameters/
---

## CodetextParameters class

**Module:** `aspose_barcode.generation.codetext_parameters`


Codetext parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__str__](#__str__) | `str` | No | Returns a string representation of the CodetextParameters instance. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [alignment](#alignment) | `TextAlignment` | Gets the alignment of the code text. Default value: TextAlignment.CENTER. |
| [color](#color) | `Tuple[int, int, int]` | Specify the displaying CodeText's Color, representation of an RGB tuple. Default value (0,0,0). |
| [font](#font) | `Optional[FontUnit]` | Specify the displaying CodeText's font. Default value: Arial 5pt regular. Ignored if FontMode is set to FontMode.AUTO. |
| [font_mode](#font_mode) | `FontMode` | Specify FontMode. If FontMode is set to Auto, font size will be calculated automatically based on xDimension value. It is recommended to use FontMode.AUTO especially in AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. Default value: FontMode.AUTO. |
| [location](#location) | `CodeLocation` | Specify the displaying CodeText Location, set to CodeLocation.NONE to hide CodeText. Default value: CodeLocation.NONE. |
| [no_wrap](#no_wrap) | `bool` | Specify word wraps (line breaks) within text. |
| [space](#space) | `Optional[Unit]` | Space between the CodeText and the BarCode in Unit value. Default value: 2pt. Ignored for EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [two_d_display_text](#two_d_display_text) | `Optional[str]` | Text that will be displayed instead of codetext in 2D barcodes. Used for: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |

### CodetextParameters Constructor {#constructor}

```python
__init__(self, _java_class)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `_java_class` | `` |  |

### CodetextParameters.__str__ {#__str__}

```python
__str__(self) -> str
```

Returns a string representation of the CodetextParameters instance.

**Return Type:** `str` — A string that represents this CodetextParameters.

### CodetextParameters.alignment {#alignment}

**Type:** `TextAlignment`

Gets the alignment of the code text. Default value: TextAlignment.CENTER.

Sets the alignment of the code text. Default value: TextAlignment.CENTER.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `TextAlignment` |  |

### CodetextParameters.color {#color}

**Type:** `Tuple[int, int, int]`

Specify the displaying CodeText's Color, representation of an RGB tuple. Default value (0,0,0).

Specify the displaying CodeText's Color, representation of an RGB tuple. Default value (0,0,0).

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Tuple[int, int, int]` |  |

### CodetextParameters.font {#font}

**Type:** `Optional[FontUnit]`

Specify the displaying CodeText's font. Default value: Arial 5pt regular. Ignored if FontMode is set to FontMode.AUTO.

Specify the displaying CodeText's font. Default value: Arial 5pt regular. Ignored if FontMode is set to FontMode.AUTO.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `FontUnit` |  |

### CodetextParameters.font_mode {#font_mode}

**Type:** `FontMode`

Specify FontMode. If FontMode is set to Auto, font size will be calculated automatically based on xDimension value. It is recommended to use FontMode.AUTO especially in AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. Default value: FontMode.AUTO.

Specify FontMode. If FontMode is set to Auto, font size will be calculated automatically based on xDimension value. It is recommended to use FontMode.AUTO especially in AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. Default value: FontMode.AUTO.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `FontMode` |  |

### CodetextParameters.location {#location}

**Type:** `CodeLocation`

Specify the displaying CodeText Location, set to CodeLocation.NONE to hide CodeText. Default value: CodeLocation.NONE.

Specify the displaying CodeText Location, set to CodeLocation.NONE to hide CodeText. Default value: CodeLocation.NONE.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `CodeLocation` |  |

### CodetextParameters.no_wrap {#no_wrap}

**Type:** `bool`

Specify word wraps (line breaks) within text.

**Returns:** bool

Specify word wraps (line breaks) within text.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `bool` |  |

### CodetextParameters.space {#space}

**Type:** `Optional[Unit]`

Space between the CodeText and the BarCode in Unit value. Default value: 2pt. Ignored for EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

Space between the CodeText and the BarCode in Unit value. Default value: 2pt. Ignored for EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Unit` |  |

### CodetextParameters.two_d_display_text {#two_d_display_text}

**Type:** `Optional[str]`

Text that will be displayed instead of codetext in 2D barcodes. Used for: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

Text that will be displayed instead of codetext in 2D barcodes. Used for: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

