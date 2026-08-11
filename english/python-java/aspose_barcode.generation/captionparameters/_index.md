---
title: "CaptionParameters"
linktitle: "CaptionParameters"
second_title: "Aspose.BarCode for Python via Java"
description: "Caption parameters."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/captionparameters/
---

## CaptionParameters class

**Module:** `aspose_barcode.generation.caption_parameters`


Caption parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__str__](#__str__) | `str` | No | String representation of the CaptionParameters object. |
| [font](#font) | `Optional[FontUnit]` | No | Caption font. Default value: Arial 8pt regular. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [alignment](#alignment) | `TextAlignment` | Caption test horizontal alignment. Default valueAlignment.Center. |
| [no_wrap](#no_wrap) | `bool` | Specify word wraps (line breaks) within text. |
| [padding](#padding) | `Optional[Padding]` | Captions paddings. Default value for CaptionAbove: 5pt 5pt 0 5pt. Default value for CaptionBelow: 0 5pt 5pt 5pt. |
| [text](#text) | `Optional[str]` | Caption text. Default value: empty string. |
| [text_color](#text_color) | `Tuple[int, int, int]` | Caption text color, representation of an RGB tuple. Default value (0,0,0). |
| [visible](#visible) | `bool` | Caption text visibility. Default value: false. |

### CaptionParameters Constructor {#constructor}

```python
__init__(self, _java_class)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `_java_class` | `` |  |

### CaptionParameters.__str__ {#__str__}

```python
__str__(self) -> str
```

String representation of the CaptionParameters object.

**Return Type:** `str`

### CaptionParameters.font {#font}

```python
font(self) -> Optional[FontUnit]
```

Caption font. Default value: Arial 8pt regular.

**Return Type:** `Optional[FontUnit]`

### CaptionParameters.alignment {#alignment}

**Type:** `TextAlignment`

Caption test horizontal alignment. Default valueAlignment.Center.

Caption test horizontal alignment. Default valueAlignment.Center.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `TextAlignment` |  |

### CaptionParameters.no_wrap {#no_wrap}

**Type:** `bool`

Specify word wraps (line breaks) within text.

**Returns:** bool

Specify word wraps (line breaks) within text.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `bool` |  |

### CaptionParameters.padding {#padding}

**Type:** `Optional[Padding]`

Captions paddings. Default value for CaptionAbove: 5pt 5pt 0 5pt. Default value for CaptionBelow: 0 5pt 5pt 5pt.

Captions paddings. Default value for CaptionAbove: 5pt 5pt 0 5pt. Default value for CaptionBelow: 0 5pt 5pt 5pt.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Padding` |  |

### CaptionParameters.text {#text}

**Type:** `Optional[str]`

Caption text. Default value: empty string.

Caption text. Default value: empty string.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### CaptionParameters.text_color {#text_color}

**Type:** `Tuple[int, int, int]`

Caption text color, representation of an RGB tuple. Default value (0,0,0).

Caption text color, representation of an RGB tuple. Default value (0,0,0).

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Tuple[int, int, int]` |  |

### CaptionParameters.visible {#visible}

**Type:** `bool`

Caption text visibility. Default value: false.

Caption text visibility. Default value: false.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `bool` |  |

