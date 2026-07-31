---
title: "Pdf417Parameters Class"
linktitle: "Pdf417Parameters"
articleTitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for Python via Java"
description: "PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fields: Pdf417MacroFileID and Pdf417MacroSe"
type: docs
weight: 10
url: /python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/
---

## Pdf417Parameters class

**Module:** `aspose_barcode.generation.pdf_417_parameters`


PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. MicroPDF417 in Structured Append mode (same as MacroPDF417 mode) requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. These samples show how to encode UCC/EAN-128 non Linked modes in GS1MicroPdf417


## Constructors

| Name | Description |
| --- | --- |
| [__init__](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf417parameters/) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__str__](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/__str__/) | `str` | No | Returns a human-readable string representation of this Pdf417Parameters. |
| [macro_pdf_417_eci_encoding](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/macro_pdf_417_eci_encoding/) | `int` | No |  |
| [macro_pdf_417_eci_encoding](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/macro_pdf_417_eci_encoding/) | `int` | No | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [macro_pdf_417_eci_encoding](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/macro_pdf_417_eci_encoding/) | `None` | No |  |
| [macro_pdf_417_eci_encoding](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/macro_pdf_417_eci_encoding/) | `None` | No | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [aspect_ratio](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/aspect_ratio/) | `float` | Height/Width ratio of 2D BarCode module. |
| [code_128_emulation](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/code_128_emulation/) | `bool` | Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128. |
| [columns](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/columns/) | `int` | Columns count. |
| [eci_encoding](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/eci_encoding/) | `int` |  |
| [encode_mode](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/encode_mode/) | `int` |  |
| [error_level](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/error_level/) | `Pdf417ErrorLevel` |  |
| [linked](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/linked/) | `bool` | Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC. |
| [macro_characters](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/macro_characters/) | `int` | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with MicroPdf417 and encodes 916 and 917 MicroPdf417 modes Default value: MacroCharacters.None. |
| [macro_pdf_417_addressee](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/macro_pdf_417_addressee/) | `Optional[str]` | Gets macro Pdf417 barcode addressee name. |
| [macro_pdf_417_checksum](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/macro_pdf_417_checksum/) | `int` | Gets macro Pdf417 barcode checksum. |
| [macro_pdf_417_file_id](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/macro_pdf_417_file_id/) | `int` | Gets macro Pdf417 barcode's file ID. Used for MacroPdf417. |
| [macro_pdf_417_file_name](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/macro_pdf_417_file_name/) | `Optional[str]` | Gets macro Pdf417 barcode file name. |
| [macro_pdf_417_file_size](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/macro_pdf_417_file_size/) | `int` | Gets macro Pdf417 file size. |
| [macro_pdf_417_segment_id](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/macro_pdf_417_segment_id/) | `int` | Gets macro Pdf417 barcode's segment ID. |
| [macro_pdf_417_segments_count](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/macro_pdf_417_segments_count/) | `int` | Gets macro Pdf417 barcode segments count. |
| [macro_pdf_417_sender](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/macro_pdf_417_sender/) | `Optional[str]` | Gets macro Pdf417 barcode sender name. |
| [macro_pdf_417_terminator](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/macro_pdf_417_terminator/) | `Pdf417MacroTerminator` | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417. |
| [macro_pdf_417_time_stamp](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/macro_pdf_417_time_stamp/) | `datetime` | Gets macro Pdf417 barcode time stamp. |
| [pdf_417_compaction_mode](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf_417_compaction_mode/) | `Pdf417CompactionMode` | Pdf417 symbology type of BarCode's compaction mode. Default value: Pdf417CompactionMode.AUTO. |
| [pdf_417_eci_encoding](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf_417_eci_encoding/) | `int` | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. |
| [pdf_417_encode_mode](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf_417_encode_mode/) | `Pdf417EncodeMode` | Gets Pdf417 encode mode. Default value: Auto. |
| [pdf_417_error_level](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf_417_error_level/) | `Pdf417ErrorLevel` | Gets Pdf417 symbology type of BarCode's error correction level. |
| [pdf_417_macro_addressee](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf_417_macro_addressee/) | `Optional[str]` | Gets macro Pdf417 barcode addressee name. |
| [pdf_417_macro_checksum](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf_417_macro_checksum/) | `int` | Gets macro Pdf417 barcode checksum. |
| [pdf_417_macro_eci_encoding](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf_417_macro_eci_encoding/) | `int` | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [pdf_417_macro_file_id](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf_417_macro_file_id/) | `int` | Gets macro Pdf417 barcode's file ID. Used for MacroPdf417. |
| [pdf_417_macro_file_name](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf_417_macro_file_name/) | `Optional[str]` | Gets macro Pdf417 barcode file name. |
| [pdf_417_macro_file_size](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf_417_macro_file_size/) | `int` | Gets macro Pdf417 file size. |
| [pdf_417_macro_segment_id](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf_417_macro_segment_id/) | `int` | Gets macro Pdf417 barcode's segment ID. |
| [pdf_417_macro_segments_count](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf_417_macro_segments_count/) | `int` | Gets macro Pdf417 barcode segments count. |
| [pdf_417_macro_sender](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf_417_macro_sender/) | `Optional[str]` | Gets macro Pdf417 barcode sender name. |
| [pdf_417_macro_terminator](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf_417_macro_terminator/) | `int` | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417. |
| [pdf_417_macro_time_stamp](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf_417_macro_time_stamp/) | `datetime` | Gets macro Pdf417 barcode time stamp. |
| [pdf_417_truncate](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/pdf_417_truncate/) | `bool` | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). |
| [reader_initialization](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/reader_initialization/) | `bool` | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [rows](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/rows/) | `int` | Rows count. |
| [structured_append_mode_barcode_id](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/structured_append_mode_barcode_id/) | `int` |  |
| [truncate](/python-java/aspose_barcode.generation.pdf_417_parameters/pdf417parameters/truncate/) | `bool` |  |
