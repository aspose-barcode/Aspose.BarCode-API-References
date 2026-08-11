---
title: "DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for Python via Java"
description: "Extended codetext generator for 2D DataMatrix barcodes for ExtendedCodetext Mode of DataMatrixEncodeMode."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/datamatrixextcodetextbuilder/
---

## DataMatrixExtCodetextBuilder class

**Module:** `aspose_barcode.generation.data_matrix_ext_codetext_builder`

**Inherits:** `ExtCodetextBuilder`


Extended codetext generator for 2D DataMatrix barcodes for ExtendedCodetext Mode of DataMatrixEncodeMode.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [add_codetext_with_encode_mode](#add_codetext_with_encode_mode) | `None` | No | Adds codetext with defined encode mode to the extended codetext items. Args: encode_mode (DataMatrixEncodeMode): Encode mode value. codetext (str): Codetext in unicode to add. |
| [add_eci_codetext_with_encode_mode](#add_eci_codetext_with_encode_mode) | `None` | No | Adds codetext with Extended Channel Identifier and defined encode mode. Args: eci_encoding (ECIEncodings): Extended Channel Identifier. encode_mode (DataMatrixEncodeMode): Encode mode value. codetext (str): Codetext in unicode to add. |
| [extended_codetext](#extended_codetext) | `Optional[str]` | No | Generates extended codetext from the extended codetext list. Returns: Optional[str]: Extended codetext as string, or None if not set. Reimplemented from ExtCodetextBuilder. |

### DataMatrixExtCodetextBuilder Constructor {#constructor}

```python
__init__(self)
```

### DataMatrixExtCodetextBuilder.add_codetext_with_encode_mode {#add_codetext_with_encode_mode}

```python
add_codetext_with_encode_mode(self, DataMatrixEncodeMode encode_mode, str codetext)
```

Adds codetext with defined encode mode to the extended codetext items. Args: encode_mode (DataMatrixEncodeMode): Encode mode value. codetext (str): Codetext in unicode to add.

| Parameter | Type | Description |
| --- | --- | --- |
| `encode_mode` | `DataMatrixEncodeMode` |  |
| `codetext` | `str` |  |

### DataMatrixExtCodetextBuilder.add_eci_codetext_with_encode_mode {#add_eci_codetext_with_encode_mode}

```python
add_eci_codetext_with_encode_mode(self, ECIEncodings eci_encoding, DataMatrixEncodeMode encode_mode, str codetext)
```

Adds codetext with Extended Channel Identifier and defined encode mode. Args: eci_encoding (ECIEncodings): Extended Channel Identifier. encode_mode (DataMatrixEncodeMode): Encode mode value. codetext (str): Codetext in unicode to add.

| Parameter | Type | Description |
| --- | --- | --- |
| `eci_encoding` | `ECIEncodings` |  |
| `encode_mode` | `DataMatrixEncodeMode` |  |
| `codetext` | `str` |  |

### DataMatrixExtCodetextBuilder.extended_codetext {#extended_codetext}

```python
extended_codetext(self) -> Optional[str]
```

Generates extended codetext from the extended codetext list. Returns: Optional[str]: Extended codetext as string, or None if not set. Reimplemented from ExtCodetextBuilder.

**Return Type:** `Optional[str]`

