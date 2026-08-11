---
title: "MaxiCodeCodetext"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode for Python via Java"
description: "Base class for encoding and decoding the text embedded in the MaxiCode code. This sample shows how to decode raw MaxiCode codetext to MaxiCodeCodetext instance."
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/maxicodecodetext/
---

## MaxiCodeCodetext class

**Module:** `aspose_barcode.complex_barcode.maxi_code_codetext`

**Inherits:** `IComplexCodetext`


Base class for encoding and decoding the text embedded in the MaxiCode code. This sample shows how to decode raw MaxiCode codetext to MaxiCodeCodetext instance.


## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [barcode_type](#barcode_type) | `EncodeTypes` | No | Gets barcode type. |
| [mode](#mode) | `Optional[MaxiCodeMode]` | No | Gets MaxiCode mode. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [eci_encoding](#eci_encoding) | `ECIEncodings` | Gets ECI encoding. Used when MaxiCodeEncodeMode is AUTO. |
| [encode_mode](#encode_mode) | `MaxiCodeEncodeMode` |  |
| [maxi_code_encode_mode](#maxi_code_encode_mode) | `MaxiCodeEncodeMode` | Gets a MaxiCode encode mode. |
### MaxiCodeCodetext.barcode_type {#barcode_type}

```python
barcode_type(self) -> EncodeTypes
```

Gets barcode type.

**Return Type:** `EncodeTypes` — Barcode type.

### MaxiCodeCodetext.mode {#mode}

```python
mode(self) -> Optional[MaxiCodeMode]
```

Gets MaxiCode mode.

**Return Type:** `Optional[MaxiCodeMode]` — MaxiCode mode or None if not set.

### MaxiCodeCodetext.eci_encoding {#eci_encoding}

**Type:** `ECIEncodings`

Gets ECI encoding. Used when MaxiCodeEncodeMode is AUTO.

Sets ECI encoding. Used when MaxiCodeEncodeMode is AUTO.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `ECIEncodings` |  |

### MaxiCodeCodetext.encode_mode {#encode_mode}

**Type:** `MaxiCodeEncodeMode`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `MaxiCodeEncodeMode` |  |

### MaxiCodeCodetext.maxi_code_encode_mode {#maxi_code_encode_mode}

**Type:** `MaxiCodeEncodeMode`

Gets a MaxiCode encode mode.

Sets a MaxiCode encode mode.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `MaxiCodeEncodeMode` |  |

