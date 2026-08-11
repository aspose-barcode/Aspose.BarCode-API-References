---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for Python via Java"
description: "ComplexCodetextReader decodes codetext to specified complex barcode type. This sample shows how to recognize and decode SwissQR image."
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/complexcodetextreader/
---

## ComplexCodetextReader class

**Module:** `aspose_barcode.complex_barcode.complex_codetext_reader`


ComplexCodetextReader decodes codetext to specified complex barcode type. This sample shows how to recognize and decode SwissQR image.


## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [try_decode_hibc_lic](#try_decode_hibc_lic) | `Optional[ Union[HIBCLICSecondaryAndAdditionalDataCodetext, HIBCLICPrimaryDataCodetext, HIBCLICCombinedCodetext]]` | Yes |  |
| [try_decode_hibc_pas](#try_decode_hibc_pas) | `Optional[HIBCPASCodetext]` | Yes |  |
| [try_decode_mailmark](#try_decode_mailmark) | `Optional[MailmarkCodetext]` | Yes |  |
| [try_decode_mailmark_2d](#try_decode_mailmark_2d) | `Optional[Mailmark2DCodetext]` | Yes |  |
| [try_decode_maxi_code](#try_decode_maxi_code) | `Optional[ Union[MaxiCodeCodetextMode2, MaxiCodeCodetextMode3, MaxiCodeStandardCodetext]]` | Yes |  |
| [try_decode_swiss_qr](#try_decode_swiss_qr) | `Optional[SwissQRCodetext]` | Yes |  |
| [try_decode_usa_drive_id](#try_decode_usa_drive_id) | `def` | Yes | Decodes USADriveId codetext. |
### ComplexCodetextReader.try_decode_hibc_lic (static) {#try_decode_hibc_lic}

```python
try_decode_hibc_lic(Union[str | None] encoded_codetext) -> Optional[ Union[HIBCLICSecondaryAndAdditionalDataCodetext, HIBCLICPrimaryDataCodetext, HIBCLICCombinedCodetext]]
```

| Parameter | Type | Description |
| --- | --- | --- |
| `encoded_codetext` | `Union[str \| None]` |  |

**Return Type:** `Optional[ Union[HIBCLICSecondaryAndAdditionalDataCodetext, HIBCLICPrimaryDataCodetext, HIBCLICCombinedCodetext]]`

### ComplexCodetextReader.try_decode_hibc_pas (static) {#try_decode_hibc_pas}

```python
try_decode_hibc_pas(str encoded_codetext) -> Optional[HIBCPASCodetext]
```

| Parameter | Type | Description |
| --- | --- | --- |
| `encoded_codetext` | `str` |  |

**Return Type:** `Optional[HIBCPASCodetext]`

### ComplexCodetextReader.try_decode_mailmark (static) {#try_decode_mailmark}

```python
try_decode_mailmark(str encoded_codetext) -> Optional[MailmarkCodetext]
```

| Parameter | Type | Description |
| --- | --- | --- |
| `encoded_codetext` | `str` |  |

**Return Type:** `Optional[MailmarkCodetext]`

### ComplexCodetextReader.try_decode_mailmark_2d (static) {#try_decode_mailmark_2d}

```python
try_decode_mailmark_2d(str encoded_codetext) -> Optional[Mailmark2DCodetext]
```

| Parameter | Type | Description |
| --- | --- | --- |
| `encoded_codetext` | `str` |  |

**Return Type:** `Optional[Mailmark2DCodetext]`

### ComplexCodetextReader.try_decode_maxi_code (static) {#try_decode_maxi_code}

```python
try_decode_maxi_code(MaxiCodeMode maxicode_mode, Union[str | None] encoded_codetext) -> Optional[ Union[MaxiCodeCodetextMode2, MaxiCodeCodetextMode3, MaxiCodeStandardCodetext]]
```

| Parameter | Type | Description |
| --- | --- | --- |
| `maxicode_mode` | `MaxiCodeMode` |  |
| `encoded_codetext` | `Union[str \| None]` |  |

**Return Type:** `Optional[ Union[MaxiCodeCodetextMode2, MaxiCodeCodetextMode3, MaxiCodeStandardCodetext]]`

### ComplexCodetextReader.try_decode_swiss_qr (static) {#try_decode_swiss_qr}

```python
try_decode_swiss_qr(str encoded_codetext) -> Optional[SwissQRCodetext]
```

| Parameter | Type | Description |
| --- | --- | --- |
| `encoded_codetext` | `str` |  |

**Return Type:** `Optional[SwissQRCodetext]`

### ComplexCodetextReader.try_decode_usa_drive_id (static) {#try_decode_usa_drive_id}

```python
try_decode_usa_drive_id(encodedCodetext) -> def
```

Decodes USADriveId codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `encodedCodetext` | `` | Encoded codetext |

**Return Type:** `def` — Decoded USADriveId or null.

