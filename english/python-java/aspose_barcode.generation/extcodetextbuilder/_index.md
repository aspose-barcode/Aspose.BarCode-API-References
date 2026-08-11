---
title: "ExtCodetextBuilder"
linktitle: "ExtCodetextBuilder"
second_title: "Aspose.BarCode for Python via Java"
description: "Helper class for automatic codetext generation of the Extended Codetext Mode."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/extcodetextbuilder/
---

## ExtCodetextBuilder class

**Module:** `aspose_barcode.generation.ext_codetext_builder`


Helper class for automatic codetext generation of the Extended Codetext Mode.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [add_eci_codetext](#add_eci_codetext) | `None` | No | Adds codetext with Extended Channel Identifier. Args: eci_encoding (ECIEncodings): Extended Channel Identifier. codetext (str): Codetext in unicode to add as an extended codetext item with Extended Channel Identifier. |
| [add_plain_codetext](#add_plain_codetext) | `None` | No | Adds plain codetext to the extended codetext items. Args: codetext (str): Codetext in unicode to add as an extended codetext item. |
| [clear](#clear) | `None` | No | Clears extended codetext items. Reimplemented in QrExtCodetextBuilder. |
| [extended_codetext](#extended_codetext) | `Optional[str]` | No | Generates extended codetext from the generation items list. Returns: Optional[str]: The generated extended codetext string, or None if not set. Reimplemented in QrExtCodetextBuilder, MaxiCodeExtCodetextBuilder, DotCodeExtCodetextBuilder, DataMatrixExtCodetextBuilder, and AztecExtCodetextBuilder. |

### ExtCodetextBuilder Constructor {#constructor}

```python
__init__(self, _java_class)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `_java_class` | `` |  |

### ExtCodetextBuilder.add_eci_codetext {#add_eci_codetext}

```python
add_eci_codetext(self, ECIEncodings eci_encoding, str codetext)
```

Adds codetext with Extended Channel Identifier. Args: eci_encoding (ECIEncodings): Extended Channel Identifier. codetext (str): Codetext in unicode to add as an extended codetext item with Extended Channel Identifier.

| Parameter | Type | Description |
| --- | --- | --- |
| `eci_encoding` | `ECIEncodings` |  |
| `codetext` | `str` |  |

### ExtCodetextBuilder.add_plain_codetext {#add_plain_codetext}

```python
add_plain_codetext(self, str codetext)
```

Adds plain codetext to the extended codetext items. Args: codetext (str): Codetext in unicode to add as an extended codetext item.

| Parameter | Type | Description |
| --- | --- | --- |
| `codetext` | `str` |  |

### ExtCodetextBuilder.clear {#clear}

```python
clear(self)
```

Clears extended codetext items. Reimplemented in QrExtCodetextBuilder.

### ExtCodetextBuilder.extended_codetext {#extended_codetext}

```python
extended_codetext(self) -> Optional[str]
```

Generates extended codetext from the generation items list. Returns: Optional[str]: The generated extended codetext string, or None if not set. Reimplemented in QrExtCodetextBuilder, MaxiCodeExtCodetextBuilder, DotCodeExtCodetextBuilder, DataMatrixExtCodetextBuilder, and AztecExtCodetextBuilder.

**Return Type:** `Optional[str]`

