---
title: "Pdf417Parameters Class"
linktitle: "Pdf417Parameters"
articleTitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for PHP via Java"
description: "PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. "
type: docs
weight: 10
url: /php/aspose/barcode/generation/pdf417parameters/
---

## Pdf417Parameters class

**Namespace:** `Aspose.Barcode.Generation`


PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. MicroPDF417 in Structured Append mode (same as MacroPDF417 mode) requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](./pdf417parameters/) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [isCode128Emulation](./iscode128emulation/) | No | Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128 |
| [isLinked](./islinked/) | No | Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 "Linked" UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC |
| [isReaderInitialization](./isreaderinitialization/) | No | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization |
| [setCode128Emulation](./setcode128emulation/) | No | Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128 |
| [setLinked](./setlinked/) | No | Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 "Linked" UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC |
| [setReaderInitialization](./setreaderinitialization/) | No | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [AspectRatio](./aspectratio/) | Read/Write | Height/Width ratio of 2D BarCode module. |
| [Columns](./columns/) | Read/Write | Columns count. |
| [ECIEncoding](./eciencoding/) | Read/Write | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Not applied for Macro PDF417 text fields. Current implementation consists all well known charset encodings. |
| [EncodeMode](./encodemode/) | Read/Write | Identifies Pdf417 encode mode. Default value: Auto. |
| [ErrorLevel](./errorlevel/) | Read/Write | Gets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture. |
| [MacroCharacters](./macrocharacters/) | Read/Write | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with MicroPdf417 and encodes 916 and 917 MicroPdf417 modes Default value: MacroCharacters.None. |
| [MacroPdf417Addressee](./macropdf417addressee/) | Read/Write | MacroPdf417 barcode addressee name (optional field). MicroPDF417 barcode addressee name (optional field for Structured Append mode) |
| [MacroPdf417Checksum](./macropdf417checksum/) | Read/Write | MacroPdf417 barcode checksum (optional field). MicroPDF417 barcode checksum (optional field for Structured Append mode) The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial. x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](./macropdf417eciencoding/) | Read/Write | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [MacroPdf417FileID](./macropdf417fileid/) | Read/Write | MacroPdf417 barcode's file ID (Required field). MicroPDF417 barcode's file ID (Required field for Structured Append mode) |
| [MacroPdf417FileName](./macropdf417filename/) | Read/Write | MacroPdf417 barcode file name (optional field). MicroPDF417 barcode file name (optional field for Structured Append mode) |
| [MacroPdf417FileSize](./macropdf417filesize/) | Read/Write | MacroPdf417 file size (optional field). MicroPDF417 file size (optional field for Structured Append mode) The file size field contains the size in bytes of the entire source file. |
| [MacroPdf417SegmentID](./macropdf417segmentid/) | Read/Write | MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. MicroPDF417 barcode's segment ID (Required field for Structured Append mode) |
| [MacroPdf417SegmentsCount](./macropdf417segmentscount/) | Read/Write | MacroPdf417 barcode segments count (optional field). MicroPDF417 barcode segments count (optional field for Structured Append mode) |
| [MacroPdf417Sender](./macropdf417sender/) | Read/Write | MacroPdf417 barcode sender name (optional field). MicroPDF417 barcode sender name (optional field for Structured Append mode) |
| [MacroPdf417Terminator](./macropdf417terminator/) | Read/Write | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417. |
| [MacroPdf417TimeStamp](./macropdf417timestamp/) | Read/Write | MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mode) |
| [Pdf417CompactionMode](./pdf417compactionmode/) | Read/Write | Pdf417 symbology type of BarCode's compaction mode. Default value: Pdf417CompactionMode::AUTO. |
| [Pdf417ECIEncoding](./pdf417eciencoding/) | Read/Write | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Not applied for Macro PDF417 text fields. Current implementation consists all well known charset encodings. |
| [Pdf417EncodeMode](./pdf417encodemode/) | Read/Write | Identifies Pdf417 encode mode. Default value: Auto. |
| [Pdf417ErrorLevel](./pdf417errorlevel/) | Read/Write | Gets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture. |
| [Pdf417MacroAddressee](./pdf417macroaddressee/) | Read/Write | Gets macro Pdf417 barcode addressee name. |
| [Pdf417MacroChecksum](./pdf417macrochecksum/) | Read/Write | Gets macro Pdf417 barcode checksum. |
| [Pdf417MacroECIEncoding](./pdf417macroeciencoding/) | Read/Write | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [Pdf417MacroFileID](./pdf417macrofileid/) | Read/Write | Getsmacro Pdf417 barcode's file ID. Used for MacroPdf417. |
| [Pdf417MacroFileName](./pdf417macrofilename/) | Read/Write | Gets macro Pdf417 barcode file name. |
| [Pdf417MacroFileSize](./pdf417macrofilesize/) | Read/Write | Gets macro Pdf417 file size. |
| [Pdf417MacroSegmentID](./pdf417macrosegmentid/) | Read/Write | Gets macro Pdf417 barcode's segment ID, which starts from 0, to MacroSegmentsCount - 1. |
| [Pdf417MacroSegmentsCount](./pdf417macrosegmentscount/) | Read/Write | Gets macro Pdf417 barcode segments count. |
| [Pdf417MacroSender](./pdf417macrosender/) | Read/Write | Gets macro Pdf417 barcode sender name. |
| [Pdf417MacroTerminator](./pdf417macroterminator/) | Read/Write | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417. |
| [Pdf417MacroTimeStamp](./pdf417macrotimestamp/) | Read/Write | Gets macro Pdf417 barcode time stamp. |
| [Pdf417Truncate](./pdf417truncate/) | Read/Write | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). |
| [Rows](./rows/) | Read/Write | Rows count. |
| [Truncate](./truncate/) | Read/Write | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). Also known as CompactPDF417. Rigth row indicator and right stop pattern are removed in this mode. |
