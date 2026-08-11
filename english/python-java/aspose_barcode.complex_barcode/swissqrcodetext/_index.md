---
title: "SwissQRCodetext"
linktitle: "SwissQRCodetext"
second_title: "Aspose.BarCode for Python via Java"
description: "Class for encoding and decoding the text embedded in the SwissQR code."
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/swissqrcodetext/
---

## SwissQRCodetext class

**Module:** `aspose_barcode.complex_barcode.swiss_qr_codetext`

**Inherits:** `IComplexCodetext`


Class for encoding and decoding the text embedded in the SwissQR code.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) | Creates an instance of SwissQRCodetext. |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [barcode_type](#barcode_type) | `EncodeTypes` | No | Gets barcode type. |
| [bill](#bill) | `Optional[SwissQRBill]` | No | SwissQR bill data. |
| [constructed_codetext](#constructed_codetext) | `Optional[str]` | No | Construct codetext from SwissQR bill data. |
| [init_from_string](#init_from_string) | `None` | No | Initializes Bill with constructed codetext. |

### SwissQRCodetext Constructor {#constructor}

```python
__init__(self, Optional[SwissQRBill] bill)
```

Creates an instance of SwissQRCodetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `bill` | `Optional[SwissQRBill]` | SwissQR bill data |

### SwissQRCodetext.barcode_type {#barcode_type}

```python
barcode_type(self) -> EncodeTypes
```

Gets barcode type.

**Return Type:** `EncodeTypes` — Barcode type.

### SwissQRCodetext.bill {#bill}

```python
bill(self) -> Optional[SwissQRBill]
```

SwissQR bill data.

**Return Type:** `Optional[SwissQRBill]`

### SwissQRCodetext.constructed_codetext {#constructed_codetext}

```python
constructed_codetext(self) -> Optional[str]
```

Construct codetext from SwissQR bill data.

**Return Type:** `Optional[str]` — Constructed codetext

### SwissQRCodetext.init_from_string {#init_from_string}

```python
init_from_string(self, str constructed_codetext)
```

Initializes Bill with constructed codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `constructed_codetext` | `str` |  |

