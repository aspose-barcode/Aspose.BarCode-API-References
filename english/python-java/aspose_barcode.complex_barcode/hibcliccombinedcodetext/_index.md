---
title: "HIBCLICCombinedCodetext"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode for Python via Java"
description: "Class for encoding and decoding the text embedded in the HIBC LIC code which stores primary and secodary data. This sample shows how to encode and decode HIBC L"
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/hibcliccombinedcodetext/
---

## HIBCLICCombinedCodetext class

**Module:** `aspose_barcode.complex_barcode.hibc_lic_combined_codetext`

**Inherits:** `HIBCLICComplexCodetext`


Class for encoding and decoding the text embedded in the HIBC LIC code which stores primary and secodary data. This sample shows how to encode and decode HIBC LIC using HIBCLICCombinedCodetext.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__eq__](#__eq__) | `bool` | No | Returns a value indicating whether this instance is equal to a specified HIBCLICCombinedCodetext value. |
| [__hash__](#__hash__) | `int` | No | Returns the hash code for the current instance. |
| [constructed_codetext](#constructed_codetext) | `Optional[str]` | No | Constructs codetext. |
| [init_from_string](#init_from_string) | `None` | No | Initializes instance from constructed codetext. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [primary_data](#primary_data) | `Optional[PrimaryData]` | Identifies primary data. |
| [secondary_and_additional_data](#secondary_and_additional_data) | `Optional[SecondaryAndAdditionalData]` | Identifies secondary and additional supplemental data. |

### HIBCLICCombinedCodetext Constructor {#constructor}

```python
__init__(self)
```

### HIBCLICCombinedCodetext.__eq__ {#__eq__}

```python
__eq__(self, HIBCLICCombinedCodetext other) -> bool
```

Returns a value indicating whether this instance is equal to a specified HIBCLICCombinedCodetext value.

| Parameter | Type | Description |
| --- | --- | --- |
| `other` | `HIBCLICCombinedCodetext` |  |

**Return Type:** `bool` — True if obj has the same value as this instance; otherwise, False.

### HIBCLICCombinedCodetext.__hash__ {#__hash__}

```python
__hash__(self) -> int
```

Returns the hash code for the current instance.

**Return Type:** `int` — A hash code for the current object.

### HIBCLICCombinedCodetext.constructed_codetext {#constructed_codetext}

```python
constructed_codetext(self) -> Optional[str]
```

Constructs codetext.

**Return Type:** `Optional[str]` — Constructed codetext

### HIBCLICCombinedCodetext.init_from_string {#init_from_string}

```python
init_from_string(self, str constructed_codetext)
```

Initializes instance from constructed codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `constructed_codetext` | `str` |  |

### HIBCLICCombinedCodetext.primary_data {#primary_data}

**Type:** `Optional[PrimaryData]`

Identifies primary data.

Identifies primary data.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `PrimaryData` |  |

### HIBCLICCombinedCodetext.secondary_and_additional_data {#secondary_and_additional_data}

**Type:** `Optional[SecondaryAndAdditionalData]`

Identifies secondary and additional supplemental data.

Identifies secondary and additional supplemental data.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `SecondaryAndAdditionalData` |  |

