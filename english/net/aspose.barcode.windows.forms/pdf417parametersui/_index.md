---
title: Class Pdf417ParametersUI
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Windows.Forms.Pdf417ParametersUI class. UI wrapper for Pdf417Parameters class
type: docs
weight: 1570
url: /net/aspose.barcode.windows.forms/pdf417parametersui/
---
## Pdf417ParametersUI class

UI wrapper for [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/) class.

```csharp
public class Pdf417ParametersUI
```

## Properties

| Name | Description |
| --- | --- |
| [AspectRatio](../../aspose.barcode.windows.forms/pdf417parametersui/aspectratio/) { get; set; } | Height/Width ratio of 2D BarCode module. |
| [CodeTextEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/codetextencoding/) { get; set; } | Gets or sets the encoding of codetext. |
| [Columns](../../aspose.barcode.windows.forms/pdf417parametersui/columns/) { get; set; } | Columns count. |
| [IsCode128Emulation](../../aspose.barcode.windows.forms/pdf417parametersui/iscode128emulation/) { get; set; } | Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128 |
| [IsLinked](../../aspose.barcode.windows.forms/pdf417parametersui/islinked/) { get; set; } | Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC |
| [IsReaderInitialization](../../aspose.barcode.windows.forms/pdf417parametersui/isreaderinitialization/) { get; set; } | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [MacroCharacters](../../aspose.barcode.windows.forms/pdf417parametersui/macrocharacters/) { get; set; } | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with MicroPdf417 and encodes 916 and 917 MicroPdf417 modes Default value: MacroCharacters.None. |
| [Pdf417CompactionMode](../../aspose.barcode.windows.forms/pdf417parametersui/pdf417compactionmode/) { get; set; } | Pdf417 symbology type of BarCode's compaction mode. Default value: Pdf417CompactionMode.Auto. |
| [Pdf417ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/pdf417eciencoding/) { get; set; } | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Not applied for Macro PDF417 text fields. Current implementation consists all well known charset encodings. |
| [Pdf417ErrorLevel](../../aspose.barcode.windows.forms/pdf417parametersui/pdf417errorlevel/) { get; set; } | Gets or sets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture. |
| [Pdf417MacroAddressee](../../aspose.barcode.windows.forms/pdf417parametersui/pdf417macroaddressee/) { get; set; } | MacroPdf417 barcode addressee name (optional field). MicroPDF417 barcode addressee name (optional field for Structured Append mode) |
| [Pdf417MacroChecksum](../../aspose.barcode.windows.forms/pdf417parametersui/pdf417macrochecksum/) { get; set; } | MacroPdf417 barcode checksum (optional field). MicroPDF417 barcode checksum (optional field for Structured Append mode) The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial. x^16 + x^12 + x^5 + 1 |
| [Pdf417MacroECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/pdf417macroeciencoding/) { get; set; } | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [Pdf417MacroFileID](../../aspose.barcode.windows.forms/pdf417parametersui/pdf417macrofileid/) { get; set; } | Gets or sets macro Pdf417 barcode's file ID. Used for MacroPdf417. |
| [Pdf417MacroFileName](../../aspose.barcode.windows.forms/pdf417parametersui/pdf417macrofilename/) { get; set; } | MacroPdf417 barcode file name (optional field). MicroPDF417 barcode file name (optional field for Structured Append mode) |
| [Pdf417MacroFileSize](../../aspose.barcode.windows.forms/pdf417parametersui/pdf417macrofilesize/) { get; set; } | MacroPdf417 file size (optional field). MicroPDF417 file size (optional field for Structured Append mode) The file size field contains the size in bytes of the entire source file. |
| [Pdf417MacroSegmentID](../../aspose.barcode.windows.forms/pdf417parametersui/pdf417macrosegmentid/) { get; set; } | Gets or sets macro Pdf417 barcode's segment ID, which starts from 0, to MacroSegmentsCount - 1. |
| [Pdf417MacroSegmentsCount](../../aspose.barcode.windows.forms/pdf417parametersui/pdf417macrosegmentscount/) { get; set; } | Gets or sets macro Pdf417 barcode segments count. |
| [Pdf417MacroSender](../../aspose.barcode.windows.forms/pdf417parametersui/pdf417macrosender/) { get; set; } | MacroPdf417 barcode sender name (optional field). MicroPDF417 barcode sender name (optional field for Structured Append mode) |
| [Pdf417MacroTerminator](../../aspose.barcode.windows.forms/pdf417parametersui/pdf417macroterminator/) { get; set; } | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417. |
| [Pdf417MacroTimeStamp](../../aspose.barcode.windows.forms/pdf417parametersui/pdf417macrotimestamp/) { get; set; } | MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mode) |
| [Pdf417Truncate](../../aspose.barcode.windows.forms/pdf417parametersui/pdf417truncate/) { get; set; } | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). |
| [Rows](../../aspose.barcode.windows.forms/pdf417parametersui/rows/) { get; set; } | Rows count. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/pdf417parametersui/tostring/)() | Returns a human-readable string representation of this [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/). |

### See Also

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


