---
title: "IComplexCodetext"
linktitle: "IComplexCodetext"
second_title: "Aspose.BarCode for Python via Java"
description: "Interface for complex codetext used with ComplexBarcodeGenerator."
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/icomplexcodetext/
---

## IComplexCodetext class

**Module:** `aspose_barcode.complex_barcode.i_complex_codetext`


Interface for complex codetext used with ComplexBarcodeGenerator.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) | Reimplemented in USADriveIdCodetext, MaxiCodeStructuredCodetext, and HIBCLICComplexCodetext. |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [barcode_type](#barcode_type) | `EncodeTypes` | No | Gets barcode type. |
| [constructed_codetext](#constructed_codetext) | `Optional[str]` | No | Construct codetext for complex barcode. |
| [init_from_string](#init_from_string) | `None` | No | Initializes instance with constructed codetext. |

### IComplexCodetext Constructor {#constructor}

```python
__init__(self, _java_class) -> def
```

Reimplemented in USADriveIdCodetext, MaxiCodeStructuredCodetext, and HIBCLICComplexCodetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `_java_class` | `` |  |

### IComplexCodetext.barcode_type {#barcode_type}

```python
barcode_type(self) -> EncodeTypes
```

Gets barcode type.

**Return Type:** `EncodeTypes` — Barcode type.

### IComplexCodetext.constructed_codetext {#constructed_codetext}

```python
constructed_codetext(self) -> Optional[str]
```

Construct codetext for complex barcode.

**Return Type:** `Optional[str]` — Constructed codetext

### IComplexCodetext.init_from_string {#init_from_string}

```python
init_from_string(self, str constructed_codetext)
```

Initializes instance with constructed codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `constructed_codetext` | `str` |  |

