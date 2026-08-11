---
title: "BarCodeException"
linktitle: "BarCodeException"
second_title: "Aspose.BarCode for Python via Java"
description: "Represents the exception for creating barcode image."
type: docs
weight: 10
url: /python-java/aspose_barcode.core/barcodeexception/
---

## BarCodeException class

**Module:** `aspose_barcode.core.exceptions`

**Inherits:** `Exception`


Represents the exception for creating barcode image.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) | Initializes a new instance of the BarCodeException class with specified error message. |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [getMessage](#getmessage) | `Optional[str]` | No | Gets message. |
| [MAX_LINES](#max_lines) | `int` | Yes |  |
| [setMessage](#setmessage) | `None` | No | Sets message. |

### BarCodeException Constructor {#constructor}

```python
__init__(self, Union[str, Exception] exc)
```

Initializes a new instance of the BarCodeException class with specified error message.

| Parameter | Type | Description |
| --- | --- | --- |
| `exc` | `Union[str, Exception]` |  |

### BarCodeException.getMessage {#getmessage}

```python
getMessage(self) -> Optional[str]
```

Gets message.

**Return Type:** `Optional[str]`

### BarCodeException.MAX_LINES (static) {#max_lines}

```python
MAX_LINES() -> int
```

**Return Type:** `int`

### BarCodeException.setMessage {#setmessage}

```python
setMessage(self, str message)
```

Sets message.

| Parameter | Type | Description |
| --- | --- | --- |
| `message` | `str` |  |

