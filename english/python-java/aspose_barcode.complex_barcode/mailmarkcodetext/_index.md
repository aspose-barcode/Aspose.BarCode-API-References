---
title: "MailmarkCodetext"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode for Python via Java"
description: "Class for encoding and decoding the text embedded in the 4-state Royal Mailmark code."
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/mailmarkcodetext/
---

## MailmarkCodetext class

**Module:** `aspose_barcode.complex_barcode.mailmark_codetext`

**Inherits:** `IComplexCodetext`


Class for encoding and decoding the text embedded in the 4-state Royal Mailmark code.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) | Initializes a new instance of the MailmarkCodetext class. |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [barcode_type](#barcode_type) | `EncodeTypes` | No | Gets barcode type. |
| [constructed_codetext](#constructed_codetext) | `Optional[str]` | No | Construct codetext from Mailmark data. |
| [init_from_string](#init_from_string) | `None` | No | Initializes Mailmark data from constructed codetext. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [class_](#class_) | `str` | "0" - None or Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Retail) "6" - Air (Retail) (for potential future use) "7" - Surface (Retail) (for potential future use) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [destination_post_code_plus_dps](#destination_post_code_plus_dps) | `str` | The PC and DP must comply with a PAF format. Nine character string denoting international "XY11 " (note the 5 trailing spaces) or a pattern of characters denoting a domestic sorting code. A domestic sorting code consists of an outward postcode, an inward postcode, and a Delivery Point Suffix. |
| [format](#format) | `int` | "0" – None or Test "1" – Letter "2" – Large Letter |
| [item_id](#item_id) | `int` | Maximum value is 99999999. |
| [supplychain_id](#supplychain_id) | `int` | Maximum values are 99 for Barcode C and 999999 for Barcode L. |
| [version_id](#version_id) | `int` | Currently "1" – For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use) |

### MailmarkCodetext Constructor {#constructor}

```python
__init__(self)
```

Initializes a new instance of the MailmarkCodetext class.

### MailmarkCodetext.barcode_type {#barcode_type}

```python
barcode_type(self) -> EncodeTypes
```

Gets barcode type.

**Return Type:** `EncodeTypes` — Barcode type.

### MailmarkCodetext.constructed_codetext {#constructed_codetext}

```python
constructed_codetext(self) -> Optional[str]
```

Construct codetext from Mailmark data.

**Return Type:** `Optional[str]` — Constructed codetext

### MailmarkCodetext.init_from_string {#init_from_string}

```python
init_from_string(self, str constructed_codetext)
```

Initializes Mailmark data from constructed codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `constructed_codetext` | `str` |  |

### MailmarkCodetext.class_ {#class_}

**Type:** `str`

"0" - None or Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Retail) "6" - Air (Retail) (for potential future use) "7" - Surface (Retail) (for potential future use) "8" - Premium (Network Access) "9" - Standard (Network Access)

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### MailmarkCodetext.destination_post_code_plus_dps {#destination_post_code_plus_dps}

**Type:** `str`

The PC and DP must comply with a PAF format. Nine character string denoting international "XY11 " (note the 5 trailing spaces) or a pattern of characters denoting a domestic sorting code. A domestic sorting code consists of an outward postcode, an inward postcode, and a Delivery Point Suffix.

The PC and DP must comply with a PAF format. Nine character string denoting international "XY11 " (note the 5 trailing spaces) or a pattern of characters denoting a domestic sorting code. A domestic sorting code consists of an outward postcode, an inward postcode, and a Delivery Point Suffix.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### MailmarkCodetext.format {#format}

**Type:** `int`

"0" – None or Test "1" – Letter "2" – Large Letter

"0" – None or Test "1" – LetterN "2" – Large Letter

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### MailmarkCodetext.item_id {#item_id}

**Type:** `int`

Maximum value is 99999999.

Maximum value is 99999999.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### MailmarkCodetext.supplychain_id {#supplychain_id}

**Type:** `int`

Maximum values are 99 for Barcode C and 999999 for Barcode L.

Maximum values are 99 for Barcode C and 999999 for Barcode L.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### MailmarkCodetext.version_id {#version_id}

**Type:** `int`

Currently "1" – For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use)

Currently "1" – For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use)

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

