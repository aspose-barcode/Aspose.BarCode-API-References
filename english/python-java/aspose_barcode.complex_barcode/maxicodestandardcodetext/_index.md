---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for Python via Java"
description: "Class for encoding and decoding MaxiCode codetext for modes 4, 5 and 6."
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

**Module:** `aspose_barcode.complex_barcode.maxi_code_standard_codetext`

**Inherits:** `MaxiCodeCodetext`


Class for encoding and decoding MaxiCode codetext for modes 4, 5 and 6.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__eq__](#__eq__) | `bool` | No | Returns a value indicating whether this instance is equal to a specified MaxiCodeStandardCodetext value. |
| [__hash__](#__hash__) | `int` | No | Returns the hash code for this instance. |
| [constructed_codetext](#constructed_codetext) | `Optional[str]` | No | Constructs codetext. |
| [init_from_string](#init_from_string) | `None` | No | Initializes instance from constructed codetext. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [message](#message) | `Optional[str]` | Gets message. |
| [mode](#mode) | `MaxiCodeMode` | Gets MaxiCode mode. |

### MaxiCodeStandardCodetext Constructor {#constructor}

```python
__init__(self)
```

### MaxiCodeStandardCodetext.__eq__ {#__eq__}

```python
__eq__(self, MaxiCodeStandardCodetext other) -> bool
```

Returns a value indicating whether this instance is equal to a specified MaxiCodeStandardCodetext value.

| Parameter | Type | Description |
| --- | --- | --- |
| `other` | `MaxiCodeStandardCodetext` |  |

**Return Type:** `bool` — True if obj has the same value as this instance; otherwise, False.

### MaxiCodeStandardCodetext.__hash__ {#__hash__}

```python
__hash__(self) -> int
```

Returns the hash code for this instance.

**Return Type:** `int` — A 32-bit signed integer hash code.

### MaxiCodeStandardCodetext.constructed_codetext {#constructed_codetext}

```python
constructed_codetext(self) -> Optional[str]
```

Constructs codetext.

**Return Type:** `Optional[str]` — Constructed codetext

### MaxiCodeStandardCodetext.init_from_string {#init_from_string}

```python
init_from_string(self, str constructed_codetext)
```

Initializes instance from constructed codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `constructed_codetext` | `str` |  |

### MaxiCodeStandardCodetext.message {#message}

**Type:** `Optional[str]`

Gets message.

Sets message.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### MaxiCodeStandardCodetext.mode {#mode}

**Type:** `MaxiCodeMode`

Gets MaxiCode mode.

**Returns:** MaxiCode mode

Sets MaxiCode mode. Standart codetext can be used only with modes 4, 5 and 6.

| Parameter | Type | Description |
| --- | --- | --- |
| `mode` | `MaxiCodeMode` |  |

