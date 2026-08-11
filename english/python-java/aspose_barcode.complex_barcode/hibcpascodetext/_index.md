---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode for Python via Java"
description: "Class for encoding and decoding the text embedded in the HIBC PAS code. This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext."
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/hibcpascodetext/
---

## HIBCPASCodetext class

**Module:** `aspose_barcode.complex_barcode.hibc_pas_codetext`

**Inherits:** `IComplexCodetext`


Class for encoding and decoding the text embedded in the HIBC PAS code. This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__eq__](#__eq__) | `bool` | No | Returns a value indicating whether this instance is equal to a specified HIBCPASCodetext value. |
| [__hash__](#__hash__) | `int` | No | Returns the hash code for the current instance. |
| [add_hibc_pas_record](#add_hibc_pas_record) | `None` | No | Adds new record. |
| [add_record](#add_record) | `None` | No | Adds new record. |
| [clear](#clear) | `None` | No | Clears records list. |
| [constructed_codetext](#constructed_codetext) | `Optional[str]` | No | Constructs codetext. |
| [init_from_string](#init_from_string) | `None` | No | Initializes instance from constructed codetext. |
| [records](#records) | `List[HIBCPASRecord]` | No | Gets records list. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [barcode_type](#barcode_type) | `EncodeTypes` | Reimplemented from IComplexCodetext. |
| [data_location](#data_location) | `HIBCPASDataLocation` | Identifies data location. |

### HIBCPASCodetext Constructor {#constructor}

```python
__init__(self)
```

### HIBCPASCodetext.__eq__ {#__eq__}

```python
__eq__(self, HIBCPASCodetext other) -> bool
```

Returns a value indicating whether this instance is equal to a specified HIBCPASCodetext value.

| Parameter | Type | Description |
| --- | --- | --- |
| `other` | `HIBCPASCodetext` |  |

**Return Type:** `bool` — True if obj has the same value as this instance; otherwise, False.

### HIBCPASCodetext.__hash__ {#__hash__}

```python
__hash__(self) -> int
```

Returns the hash code for the current instance.

**Return Type:** `int` — A hash code for the current object.

### HIBCPASCodetext.add_hibc_pas_record {#add_hibc_pas_record}

```python
add_hibc_pas_record(self, HIBCPASRecord record)
```

Adds new record.

| Parameter | Type | Description |
| --- | --- | --- |
| `record` | `HIBCPASRecord` |  |

### HIBCPASCodetext.add_record {#add_record}

```python
add_record(self, HIBCPASDataType data_type, str data)
```

Adds new record.

| Parameter | Type | Description |
| --- | --- | --- |
| `data_type` | `HIBCPASDataType` |  |
| `data` | `str` |  |

### HIBCPASCodetext.clear {#clear}

```python
clear(self)
```

Clears records list.

### HIBCPASCodetext.constructed_codetext {#constructed_codetext}

```python
constructed_codetext(self) -> Optional[str]
```

Constructs codetext.

**Return Type:** `Optional[str]` — Constructed codetext.

### HIBCPASCodetext.init_from_string {#init_from_string}

```python
init_from_string(self, str constructed_codetext)
```

Initializes instance from constructed codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `constructed_codetext` | `str` |  |

### HIBCPASCodetext.records {#records}

```python
records(self) -> List[HIBCPASRecord]
```

Gets records list.

**Return Type:** `List[HIBCPASRecord]` — List of records

### HIBCPASCodetext.barcode_type {#barcode_type}

**Type:** `EncodeTypes`

Reimplemented from IComplexCodetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `EncodeTypes` |  |

### HIBCPASCodetext.data_location {#data_location}

**Type:** `HIBCPASDataLocation`

Identifies data location.

Identifies data location.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `HIBCPASDataLocation` |  |

