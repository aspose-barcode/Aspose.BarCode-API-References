---
title: "BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode for Python via Java"
description: "Stores recognized barcode data like SingleDecodeType type,. codetext, BarCodeRegionParameters region and other parameters This sample shows how to obtain BarCod"
type: docs
weight: 10
url: /python-java/aspose_barcode.recognition/barcoderesult/
---

## BarCodeResult class

**Module:** `aspose_barcode.recognition.barcode_result`


Stores recognized barcode data like SingleDecodeType type,. codetext, BarCodeRegionParameters region and other parameters This sample shows how to obtain BarCodeResult.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__eq__](#__eq__) | `bool` | No | Returns a value indicating whether this instance is equal to a specified BarCodeResult value. |
| [__hash__](#__hash__) | `int` | No | Returns the hash code for the current instance. |
| [__str__](#__str__) | `str` | No | Returns a human-readable string representation of this BarCodeResult. |
| [code_bytes](#code_bytes) | `List[str]` | No |  |
| [code_text](#code_text) | `Optional[str]` | No |  |
| [code_type](#code_type) | `DecodeType` | No |  |
| [code_type_name](#code_type_name) | `Optional[str]` | No |  |
| [confidence](#confidence) | `BarCodeConfidence` | No |  |
| [extended](#extended) | `Optional[BarCodeExtendedParameters]` | No |  |
| [reading_quality](#reading_quality) | `float` | No |  |
| [region](#region) | `Optional[BarCodeRegionParameters]` | No |  |

### BarCodeResult Constructor {#constructor}

```python
__init__(self, _java_class) -> def
```

| Parameter | Type | Description |
| --- | --- | --- |
| `_java_class` | `` |  |

### BarCodeResult.__eq__ {#__eq__}

```python
__eq__(self, BarCodeResult other) -> bool
```

Returns a value indicating whether this instance is equal to a specified BarCodeResult value.

| Parameter | Type | Description |
| --- | --- | --- |
| `other` | `BarCodeResult` |  |

**Return Type:** `bool` — true if obj has the same value as this instance otherwise, false.

### BarCodeResult.__hash__ {#__hash__}

```python
__hash__(self) -> int
```

Returns the hash code for the current instance.

**Return Type:** `int` — A hash code for the current object.

### BarCodeResult.__str__ {#__str__}

```python
__str__(self) -> str
```

Returns a human-readable string representation of this BarCodeResult.

**Return Type:** `str` — A string that represents this BarCodeResult.

### BarCodeResult.code_bytes {#code_bytes}

```python
code_bytes(self) -> List[str]
```

**Return Type:** `List[str]`

### BarCodeResult.code_text {#code_text}

```python
code_text(self, Optional[str] encoding) -> Optional[str]
```

| Parameter | Type | Description |
| --- | --- | --- |
| `encoding` | `Optional[str]` |  |

**Return Type:** `Optional[str]`

### BarCodeResult.code_type {#code_type}

```python
code_type(self) -> DecodeType
```

**Return Type:** `DecodeType`

### BarCodeResult.code_type_name {#code_type_name}

```python
code_type_name(self) -> Optional[str]
```

**Return Type:** `Optional[str]`

### BarCodeResult.confidence {#confidence}

```python
confidence(self) -> BarCodeConfidence
```

**Return Type:** `BarCodeConfidence`

### BarCodeResult.extended {#extended}

```python
extended(self) -> Optional[BarCodeExtendedParameters]
```

**Return Type:** `Optional[BarCodeExtendedParameters]`

### BarCodeResult.reading_quality {#reading_quality}

```python
reading_quality(self) -> float
```

**Return Type:** `float`

### BarCodeResult.region {#region}

```python
region(self) -> Optional[BarCodeRegionParameters]
```

**Return Type:** `Optional[BarCodeRegionParameters]`

