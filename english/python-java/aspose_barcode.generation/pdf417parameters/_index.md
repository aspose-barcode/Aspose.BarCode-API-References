---
title: "Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for Python via Java"
description: "PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fields: Pdf417MacroFileID and Pdf417MacroSe"
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/pdf417parameters/
---

## Pdf417Parameters class

**Module:** `aspose_barcode.generation.pdf_417_parameters`


PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. MicroPDF417 in Structured Append mode (same as MacroPDF417 mode) requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. These samples show how to encode UCC/EAN-128 non Linked modes in GS1MicroPdf417


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__str__](#__str__) | `str` | No | Returns a human-readable string representation of this Pdf417Parameters. |
| [macro_pdf_417_eci_encoding](#macro_pdf_417_eci_encoding) | `int` | No |  |
| [macro_pdf_417_eci_encoding](#macro_pdf_417_eci_encoding-1) | `int` | No | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [macro_pdf_417_eci_encoding](#macro_pdf_417_eci_encoding-2) | `None` | No |  |
| [macro_pdf_417_eci_encoding](#macro_pdf_417_eci_encoding-3) | `None` | No | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [aspect_ratio](#aspect_ratio) | `float` | Height/Width ratio of 2D BarCode module. |
| [code_128_emulation](#code_128_emulation) | `bool` | Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128. |
| [columns](#columns) | `int` | Columns count. |
| [eci_encoding](#eci_encoding) | `int` |  |
| [encode_mode](#encode_mode) | `int` |  |
| [error_level](#error_level) | `Pdf417ErrorLevel` |  |
| [linked](#linked) | `bool` | Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC. |
| [macro_characters](#macro_characters) | `int` | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with MicroPdf417 and encodes 916 and 917 MicroPdf417 modes Default value: MacroCharacters.None. |
| [macro_pdf_417_addressee](#macro_pdf_417_addressee) | `Optional[str]` | Gets macro Pdf417 barcode addressee name. |
| [macro_pdf_417_checksum](#macro_pdf_417_checksum) | `int` | Gets macro Pdf417 barcode checksum. |
| [macro_pdf_417_file_id](#macro_pdf_417_file_id) | `int` | Gets macro Pdf417 barcode's file ID. Used for MacroPdf417. |
| [macro_pdf_417_file_name](#macro_pdf_417_file_name) | `Optional[str]` | Gets macro Pdf417 barcode file name. |
| [macro_pdf_417_file_size](#macro_pdf_417_file_size) | `int` | Gets macro Pdf417 file size. |
| [macro_pdf_417_segment_id](#macro_pdf_417_segment_id) | `int` | Gets macro Pdf417 barcode's segment ID. |
| [macro_pdf_417_segments_count](#macro_pdf_417_segments_count) | `int` | Gets macro Pdf417 barcode segments count. |
| [macro_pdf_417_sender](#macro_pdf_417_sender) | `Optional[str]` | Gets macro Pdf417 barcode sender name. |
| [macro_pdf_417_terminator](#macro_pdf_417_terminator) | `Pdf417MacroTerminator` | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417. |
| [macro_pdf_417_time_stamp](#macro_pdf_417_time_stamp) | `datetime` | Gets macro Pdf417 barcode time stamp. |
| [pdf_417_compaction_mode](#pdf_417_compaction_mode) | `Pdf417CompactionMode` | Pdf417 symbology type of BarCode's compaction mode. Default value: Pdf417CompactionMode.AUTO. |
| [pdf_417_eci_encoding](#pdf_417_eci_encoding) | `int` | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. |
| [pdf_417_encode_mode](#pdf_417_encode_mode) | `Pdf417EncodeMode` | Gets Pdf417 encode mode. Default value: Auto. |
| [pdf_417_error_level](#pdf_417_error_level) | `Pdf417ErrorLevel` | Gets Pdf417 symbology type of BarCode's error correction level. |
| [pdf_417_macro_addressee](#pdf_417_macro_addressee) | `Optional[str]` | Gets macro Pdf417 barcode addressee name. |
| [pdf_417_macro_checksum](#pdf_417_macro_checksum) | `int` | Gets macro Pdf417 barcode checksum. |
| [pdf_417_macro_eci_encoding](#pdf_417_macro_eci_encoding) | `int` | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [pdf_417_macro_file_id](#pdf_417_macro_file_id) | `int` | Gets macro Pdf417 barcode's file ID. Used for MacroPdf417. |
| [pdf_417_macro_file_name](#pdf_417_macro_file_name) | `Optional[str]` | Gets macro Pdf417 barcode file name. |
| [pdf_417_macro_file_size](#pdf_417_macro_file_size) | `int` | Gets macro Pdf417 file size. |
| [pdf_417_macro_segment_id](#pdf_417_macro_segment_id) | `int` | Gets macro Pdf417 barcode's segment ID. |
| [pdf_417_macro_segments_count](#pdf_417_macro_segments_count) | `int` | Gets macro Pdf417 barcode segments count. |
| [pdf_417_macro_sender](#pdf_417_macro_sender) | `Optional[str]` | Gets macro Pdf417 barcode sender name. |
| [pdf_417_macro_terminator](#pdf_417_macro_terminator) | `int` | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417. |
| [pdf_417_macro_time_stamp](#pdf_417_macro_time_stamp) | `datetime` | Gets macro Pdf417 barcode time stamp. |
| [pdf_417_truncate](#pdf_417_truncate) | `bool` | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). |
| [reader_initialization](#reader_initialization) | `bool` | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [rows](#rows) | `int` | Rows count. |
| [structured_append_mode_barcode_id](#structured_append_mode_barcode_id) | `int` |  |
| [truncate](#truncate) | `bool` |  |

### Pdf417Parameters Constructor {#constructor}

```python
__init__(self, _java_class)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `_java_class` | `` |  |

### Pdf417Parameters.__str__ {#__str__}

```python
__str__(self) -> str
```

Returns a human-readable string representation of this Pdf417Parameters.

**Return Type:** `str` — string that represents this Pdf417Parameters.

### Pdf417Parameters.macro_pdf_417_eci_encoding {#macro_pdf_417_eci_encoding}

```python
macro_pdf_417_eci_encoding(self) -> int
```

**Return Type:** `int`

### Pdf417Parameters.macro_pdf_417_eci_encoding {#macro_pdf_417_eci_encoding-1}

```python
macro_pdf_417_eci_encoding(self) -> int
```

Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields.

**Return Type:** `int` — pdf417MacroECIEncoding int value

### Pdf417Parameters.macro_pdf_417_eci_encoding {#macro_pdf_417_eci_encoding-2}

```python
macro_pdf_417_eci_encoding(self, int value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### Pdf417Parameters.macro_pdf_417_eci_encoding {#macro_pdf_417_eci_encoding-3}

```python
macro_pdf_417_eci_encoding(self, int value)
```

Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` | int value |

### Pdf417Parameters.aspect_ratio {#aspect_ratio}

**Type:** `float`

Height/Width ratio of 2D BarCode module.

Height/Width ratio of 2D BarCode module.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `float` |  |

### Pdf417Parameters.code_128_emulation {#code_128_emulation}

**Type:** `bool`

Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128.

**Returns:** boolean value

Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `bool` |  |

### Pdf417Parameters.columns {#columns}

**Type:** `int`

Columns count.

Columns count.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### Pdf417Parameters.eci_encoding {#eci_encoding}

**Type:** `int`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### Pdf417Parameters.encode_mode {#encode_mode}

**Type:** `int`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### Pdf417Parameters.error_level {#error_level}

**Type:** `Pdf417ErrorLevel`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Pdf417ErrorLevel` |  |

### Pdf417Parameters.linked {#linked}

**Type:** `bool`

Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC.

**Returns:** boolean value

Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `bool` |  |

### Pdf417Parameters.macro_characters {#macro_characters}

**Type:** `int`

Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with MicroPdf417 and encodes 916 and 917 MicroPdf417 modes Default value: MacroCharacters.None.

**Returns:** MacroCharacters int value

Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with MicroPdf417 and encodes 916 and 917 MicroPdf417 modes Default value: MacroCharacters.None.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `MacroCharacter` |  |

### Pdf417Parameters.macro_pdf_417_addressee {#macro_pdf_417_addressee}

**Type:** `Optional[str]`

Gets macro Pdf417 barcode addressee name.

Sets macro Pdf417 barcode addressee name.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### Pdf417Parameters.macro_pdf_417_checksum {#macro_pdf_417_checksum}

**Type:** `int`

Gets macro Pdf417 barcode checksum.

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

Sets macro Pdf417 barcode checksum.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` | The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial. |

### Pdf417Parameters.macro_pdf_417_file_id {#macro_pdf_417_file_id}

**Type:** `int`

Gets macro Pdf417 barcode's file ID. Used for MacroPdf417.

Sets macro Pdf417 barcode's file ID. Used for MacroPdf417.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### Pdf417Parameters.macro_pdf_417_file_name {#macro_pdf_417_file_name}

**Type:** `Optional[str]`

Gets macro Pdf417 barcode file name.

Sets macro Pdf417 barcode file name.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### Pdf417Parameters.macro_pdf_417_file_size {#macro_pdf_417_file_size}

**Type:** `int`

Gets macro Pdf417 file size.

**Returns:** The file size field contains the size in bytes of the entire source file.

Sets macro Pdf417 file size.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` | The file size field contains the size in bytes of the entire source file. |

### Pdf417Parameters.macro_pdf_417_segment_id {#macro_pdf_417_segment_id}

**Type:** `int`

Gets macro Pdf417 barcode's segment ID.

Sets macro Pdf417 barcode's segment ID.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### Pdf417Parameters.macro_pdf_417_segments_count {#macro_pdf_417_segments_count}

**Type:** `int`

Gets macro Pdf417 barcode segments count.

Sets macro Pdf417 barcode segments count.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### Pdf417Parameters.macro_pdf_417_sender {#macro_pdf_417_sender}

**Type:** `Optional[str]`

Gets macro Pdf417 barcode sender name.

Sets macro Pdf417 barcode sender name.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### Pdf417Parameters.macro_pdf_417_terminator {#macro_pdf_417_terminator}

**Type:** `Pdf417MacroTerminator`

Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417.

**Returns:** Pdf417MacroTerminator int value

Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Pdf417MacroTerminator` | int value |

### Pdf417Parameters.macro_pdf_417_time_stamp {#macro_pdf_417_time_stamp}

**Type:** `datetime`

Gets macro Pdf417 barcode time stamp.

Sets macro Pdf417 barcode time stamp.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `datetime` |  |

### Pdf417Parameters.pdf_417_compaction_mode {#pdf_417_compaction_mode}

**Type:** `Pdf417CompactionMode`

Pdf417 symbology type of BarCode's compaction mode. Default value: Pdf417CompactionMode.AUTO.

Pdf417 symbology type of BarCode's compaction mode. Default value: Pdf417CompactionMode.AUTO.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Pdf417CompactionMode` |  |

### Pdf417Parameters.pdf_417_eci_encoding {#pdf_417_eci_encoding}

**Type:** `int`

Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings.

**Returns:** pdf417ECIEncoding int value

Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings.

| Parameter | Type | Description |
| --- | --- | --- |
| `pdf417ECIEncoding` | `int` | int value |

### Pdf417Parameters.pdf_417_encode_mode {#pdf_417_encode_mode}

**Type:** `Pdf417EncodeMode`

Gets Pdf417 encode mode. Default value: Auto.

**Returns:** Pdf417EncodeMode

Sets Pdf417 encode mode. Default value: Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Pdf417EncodeMode` |  |

### Pdf417Parameters.pdf_417_error_level {#pdf_417_error_level}

**Type:** `Pdf417ErrorLevel`

Gets Pdf417 symbology type of BarCode's error correction level.

Sets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means the best error correction which means a larger picture.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Pdf417ErrorLevel` |  |

### Pdf417Parameters.pdf_417_macro_addressee {#pdf_417_macro_addressee}

**Type:** `Optional[str]`

Gets macro Pdf417 barcode addressee name.

Sets macro Pdf417 barcode addressee name.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### Pdf417Parameters.pdf_417_macro_checksum {#pdf_417_macro_checksum}

**Type:** `int`

Gets macro Pdf417 barcode checksum.

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

Sets macro Pdf417 barcode checksum.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` | The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial. |

### Pdf417Parameters.pdf_417_macro_eci_encoding {#pdf_417_macro_eci_encoding}

**Type:** `int`

Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields.

**Returns:** pdf417MacroECIEncoding int value

Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields.

| Parameter | Type | Description |
| --- | --- | --- |
| `pdf417MacroECIEncoding` | `int` | int value |

### Pdf417Parameters.pdf_417_macro_file_id {#pdf_417_macro_file_id}

**Type:** `int`

Gets macro Pdf417 barcode's file ID. Used for MacroPdf417.

Sets macro Pdf417 barcode's file ID. Used for MacroPdf417.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### Pdf417Parameters.pdf_417_macro_file_name {#pdf_417_macro_file_name}

**Type:** `Optional[str]`

Gets macro Pdf417 barcode file name.

Sets macro Pdf417 barcode file name.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### Pdf417Parameters.pdf_417_macro_file_size {#pdf_417_macro_file_size}

**Type:** `int`

Gets macro Pdf417 file size.

**Returns:** The file size field contains the size in bytes of the entire source file.

Sets macro Pdf417 file size.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` | The file size field contains the size in bytes of the entire source file. |

### Pdf417Parameters.pdf_417_macro_segment_id {#pdf_417_macro_segment_id}

**Type:** `int`

Gets macro Pdf417 barcode's segment ID.

Sets macro Pdf417 barcode's segment ID.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### Pdf417Parameters.pdf_417_macro_segments_count {#pdf_417_macro_segments_count}

**Type:** `int`

Gets macro Pdf417 barcode segments count.

Sets macro Pdf417 barcode segments count.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### Pdf417Parameters.pdf_417_macro_sender {#pdf_417_macro_sender}

**Type:** `Optional[str]`

Gets macro Pdf417 barcode sender name.

Sets macro Pdf417 barcode sender name.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### Pdf417Parameters.pdf_417_macro_terminator {#pdf_417_macro_terminator}

**Type:** `int`

Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417.

**Returns:** Pdf417MacroTerminator int value

Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417.

| Parameter | Type | Description |
| --- | --- | --- |
| `pdf417MacroTerminator` | `int` |  |

### Pdf417Parameters.pdf_417_macro_time_stamp {#pdf_417_macro_time_stamp}

**Type:** `datetime`

Gets macro Pdf417 barcode time stamp.

Sets macro Pdf417 barcode time stamp.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `datetime` |  |

### Pdf417Parameters.pdf_417_truncate {#pdf_417_truncate}

**Type:** `bool`

Whether Pdf417 symbology type of BarCode is truncated (to reduce space).

Whether Pdf417 symbology type of BarCode is truncated.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `bool` |  |

### Pdf417Parameters.reader_initialization {#reader_initialization}

**Type:** `bool`

Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization.

**Returns:** readerInitialization boolean value

Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization.

| Parameter | Type | Description |
| --- | --- | --- |
| `readerInitialization` | `bool` | boolean value |

### Pdf417Parameters.rows {#rows}

**Type:** `int`

Rows count.

Rows count.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### Pdf417Parameters.structured_append_mode_barcode_id {#structured_append_mode_barcode_id}

**Type:** `int`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### Pdf417Parameters.truncate {#truncate}

**Type:** `bool`

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `bool` |  |

