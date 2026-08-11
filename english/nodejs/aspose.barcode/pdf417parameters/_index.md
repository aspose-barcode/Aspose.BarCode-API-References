---
title: "Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "PDF417 parameters."
type: docs
weight: 770
url: /nodejs/aspose.barcode/pdf417parameters/
---

## Pdf417Parameters class

PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. MicroPDF417 in Structured Append mode (same as MacroPDF417 mode) requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. These samples show how to encode UCC/EAN-128 non Linked modes in GS1MicroPdf417

```js
new Pdf417Parameters()
```

**Example:**

```js
# Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log( result.getCodeText());
}
```

## Methods

| Name | Description |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Height/Width ratio of 2D BarCode module. |
| [getColumns()](#getcolumns) | Columns count. |
| [getECIEncoding()](#geteciencoding) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for |
| [getEncodeMode()](#getencodemode) | Identifies Pdf417 encode mode. Default value: Auto. |
| [getErrorLevel()](#geterrorlevel) | Gets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error corr |
| [getMacroCharacters()](#getmacrocharacters) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with Micro |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | MacroPdf417 barcode addressee name (optional field). MicroPDF417 barcode addressee name (optional field for Structured A |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | MacroPdf417 barcode checksum (optional field). MicroPDF417 barcode checksum (optional field for Structured Append mode)  |
| [getMacroPdf417ECIEncoding()](#getmacropdf417eciencoding) | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | MacroPdf417 barcode's file ID (Required field). MicroPDF417 barcode's file ID (Required field for Structured Append mode |
| [getMacroPdf417FileName()](#getmacropdf417filename) | MacroPdf417 barcode file name (optional field). MicroPDF417 barcode file name (optional field for Structured Append mode |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | MacroPdf417 file size (optional field). MicroPDF417 file size (optional field for Structured Append mode) The file size  |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. MicroPDF417 barcode's |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | MacroPdf417 barcode segments count (optional field). MicroPDF417 barcode segments count (optional field for Structured A |
| [getMacroPdf417Sender()](#getmacropdf417sender) | MacroPdf417 barcode sender name (optional field). MicroPDF417 barcode sender name (optional field for Structured Append  |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PD |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mo |
| [getPdf417CompactionMode()](#getpdf417compactionmode) | Pdf417 symbology type of BarCode's compaction mode. Default value: Pdf417CompactionMode.AUTO. |
| [getPdf417ECIEncoding()](#getpdf417eciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for |
| [getPdf417EncodeMode()](#getpdf417encodemode) | Identifies Pdf417 encode mode. Default value: Auto. |
| [getPdf417ErrorLevel()](#getpdf417errorlevel) ~~(deprecated)~~ | Gets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error corr |
| [getPdf417MacroAddressee()](#getpdf417macroaddressee) ~~(deprecated)~~ | Gets macro Pdf417 barcode addressee name. |
| [getPdf417MacroChecksum()](#getpdf417macrochecksum) ~~(deprecated)~~ | Gets macro Pdf417 barcode checksum. |
| [getPdf417MacroECIEncoding()](#getpdf417macroeciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [getPdf417MacroFileID()](#getpdf417macrofileid) ~~(deprecated)~~ | Getsmacro Pdf417 barcode's file ID. Used for MacroPdf417. |
| [getPdf417MacroFileName()](#getpdf417macrofilename) ~~(deprecated)~~ | Gets macro Pdf417 barcode file name. |
| [getPdf417MacroFileSize()](#getpdf417macrofilesize) ~~(deprecated)~~ | Gets macro Pdf417 file size. |
| [getPdf417MacroSegmentID()](#getpdf417macrosegmentid) ~~(deprecated)~~ | Gets macro Pdf417 barcode's segment ID, which starts from 0, to MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getpdf417macrosegmentscount) ~~(deprecated)~~ | Gets macro Pdf417 barcode segments count. |
| [getPdf417MacroSender()](#getpdf417macrosender) ~~(deprecated)~~ | Gets macro Pdf417 barcode sender name. |
| [getPdf417MacroTerminator()](#getpdf417macroterminator) ~~(deprecated)~~ | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PD |
| [getPdf417MacroTimeStamp()](#getpdf417macrotimestamp) ~~(deprecated)~~ | Gets macro Pdf417 barcode time stamp. |
| [getPdf417Truncate()](#getpdf417truncate) ~~(deprecated)~~ | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). |
| [getRows()](#getrows) | Rows count. |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes  |
| [getTruncate()](#gettruncate) | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). Also known as CompactPDF417. Rigth row indicato |
| [isCode128Emulation()](#iscode128emulation) | Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and  |
| [isLinked()](#islinked) | Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907 |
| [isReaderInitialization()](#isreaderinitialization) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization |
| [setAspectRatio()](#setaspectratio) | Height/Width ratio of 2D BarCode module. |
| [setCode128Emulation()](#setcode128emulation) | Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and  |
| [setColumns()](#setcolumns) | Columns count. |
| [setECIEncoding()](#seteciencoding) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for |
| [setEncodeMode()](#setencodemode) | Identifies Pdf417 encode mode. Default value: Auto. |
| [setErrorLevel(value)](#seterrorlevel) | Sets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error corr |
| [setLinked()](#setlinked) | Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907 |
| [setMacroCharacters()](#setmacrocharacters) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with Micro |
| [setMacroPdf417Addressee()](#setmacropdf417addressee) | MacroPdf417 barcode addressee name (optional field). MicroPDF417 barcode addressee name (optional field for Structured A |
| [setMacroPdf417Checksum()](#setmacropdf417checksum) | MacroPdf417 barcode checksum (optional field). MicroPDF417 barcode checksum (optional field for Structured Append mode)  |
| [setMacroPdf417ECIEncoding()](#setmacropdf417eciencoding) | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [setMacroPdf417FileID()](#setmacropdf417fileid) | MacroPdf417 barcode's file ID (Required field). MicroPDF417 barcode's file ID (Required field for Structured Append mode |
| [setMacroPdf417FileName()](#setmacropdf417filename) | MacroPdf417 barcode file name (optional field). MicroPDF417 barcode file name (optional field for Structured Append mode |
| [setMacroPdf417FileSize()](#setmacropdf417filesize) | MacroPdf417 file size (optional field). MicroPDF417 file size (optional field for Structured Append mode) The file size  |
| [setMacroPdf417SegmentID()](#setmacropdf417segmentid) | MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. MicroPDF417 barcode's |
| [setMacroPdf417SegmentsCount()](#setmacropdf417segmentscount) | MacroPdf417 barcode segments count (optional field). MicroPDF417 barcode segments count (optional field for Structured A |
| [setMacroPdf417Sender()](#setmacropdf417sender) | MacroPdf417 barcode sender name (optional field). MicroPDF417 barcode sender name (optional field for Structured Append  |
| [setMacroPdf417Terminator()](#setmacropdf417terminator) | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PD |
| [setMacroPdf417TimeStamp()](#setmacropdf417timestamp) | MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mo |
| [setPdf417CompactionMode()](#setpdf417compactionmode) | Pdf417 symbology type of BarCode's compaction mode. Default value: Pdf417CompactionMode.AUTO. |
| [setPdf417ECIEncoding()](#setpdf417eciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for |
| [setPdf417EncodeMode()](#setpdf417encodemode) ~~(deprecated)~~ | Identifies Pdf417 encode mode. Default value: Auto. |
| [setPdf417ErrorLevel()](#setpdf417errorlevel) ~~(deprecated)~~ | Sets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error corr |
| [setPdf417MacroAddressee()](#setpdf417macroaddressee) ~~(deprecated)~~ | Sets macro Pdf417 barcode addressee name. |
| [setPdf417MacroChecksum(value)](#setpdf417macrochecksum) ~~(deprecated)~~ | Sets macro Pdf417 barcode checksum. |
| [setPdf417MacroECIEncoding()](#setpdf417macroeciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [setPdf417MacroFileID()](#setpdf417macrofileid) ~~(deprecated)~~ | Sets macro Pdf417 barcode's file ID. Used for MacroPdf417. |
| [setPdf417MacroFileName()](#setpdf417macrofilename) ~~(deprecated)~~ | Sets macro Pdf417 barcode file name. |
| [setPdf417MacroFileSize(value)](#setpdf417macrofilesize) ~~(deprecated)~~ | Sets macro Pdf417 file size. |
| [setPdf417MacroSegmentID()](#setpdf417macrosegmentid) ~~(deprecated)~~ | Sets macro Pdf417 barcode's segment ID, which starts from 0, to MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount()](#setpdf417macrosegmentscount) ~~(deprecated)~~ | Sets macro Pdf417 barcode segments count. |
| [setPdf417MacroSender()](#setpdf417macrosender) ~~(deprecated)~~ | Sets macro Pdf417 barcode sender name. |
| [setPdf417MacroTerminator()](#setpdf417macroterminator) ~~(deprecated)~~ | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PD |
| [setPdf417MacroTimeStamp()](#setpdf417macrotimestamp) ~~(deprecated)~~ | Sets macro Pdf417 barcode time stamp. |
| [setPdf417Truncate()](#setpdf417truncate) ~~(deprecated)~~ | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). |
| [setReaderInitialization(value)](#setreaderinitialization) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization |
| [setRows()](#setrows) | Rows count. |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes  |
| [setTruncate()](#settruncate) | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). Also known as CompactPDF417. Rigth row indicato |
| [toString()](#tostring) | Returns a human-readable string representation of this Pdf417Parameters. |

### getAspectRatio() {#getaspectratio}

Height/Width ratio of 2D BarCode module.

### getColumns() {#getcolumns}

Columns count.

### getECIEncoding() {#geteciencoding}

Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Not applied for Macro PDF417 text fields. Current implementation consists all well known charset encodings.

### getEncodeMode() {#getencodemode}

Identifies Pdf417 encode mode. Default value: Auto.

### getErrorLevel() {#geterrorlevel}

Gets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

**Returns:** Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### getMacroCharacters() {#getmacrocharacters}

Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with MicroPdf417 and encodes 916 and 917 MicroPdf417 modes Default value: MacroCharacters.None. These samples show how to encode Macro Characters in MicroPdf417

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### getMacroPdf417Addressee() {#getmacropdf417addressee}

MacroPdf417 barcode addressee name (optional field). MicroPDF417 barcode addressee name (optional field for Structured Append mode)

### getMacroPdf417Checksum() {#getmacropdf417checksum}

MacroPdf417 barcode checksum (optional field). MicroPDF417 barcode checksum (optional field for Structured Append mode) The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial. x^16 + x^12 + x^5 + 1

### getMacroPdf417ECIEncoding() {#getmacropdf417eciencoding}

Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields.

### getMacroPdf417FileID() {#getmacropdf417fileid}

MacroPdf417 barcode's file ID (Required field). MicroPDF417 barcode's file ID (Required field for Structured Append mode)

### getMacroPdf417FileName() {#getmacropdf417filename}

MacroPdf417 barcode file name (optional field). MicroPDF417 barcode file name (optional field for Structured Append mode)

### getMacroPdf417FileSize() {#getmacropdf417filesize}

MacroPdf417 file size (optional field). MicroPDF417 file size (optional field for Structured Append mode) The file size field contains the size in bytes of the entire source file.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. MicroPDF417 barcode's segment ID (Required field for Structured Append mode)

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

MacroPdf417 barcode segments count (optional field). MicroPDF417 barcode segments count (optional field for Structured Append mode)

### getMacroPdf417Sender() {#getmacropdf417sender}

MacroPdf417 barcode sender name (optional field). MicroPDF417 barcode sender name (optional field for Structured Append mode)

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417.

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mode)

### getPdf417CompactionMode() {#getpdf417compactionmode}

Pdf417 symbology type of BarCode's compaction mode. Default value: Pdf417CompactionMode.AUTO.

### getPdf417ECIEncoding() {#getpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings.

### getPdf417EncodeMode() {#getpdf417encodemode}

Identifies Pdf417 encode mode. Default value: Auto.

### getPdf417ErrorLevel() {#getpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Gets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### getPdf417MacroAddressee() {#getpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Gets macro Pdf417 barcode addressee name.

### getPdf417MacroChecksum() {#getpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Gets macro Pdf417 barcode checksum.

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

### getPdf417MacroECIEncoding() {#getpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields.

### getPdf417MacroFileID() {#getpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Getsmacro Pdf417 barcode's file ID. Used for MacroPdf417.

### getPdf417MacroFileName() {#getpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Gets macro Pdf417 barcode file name.

### getPdf417MacroFileSize() {#getpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Gets macro Pdf417 file size.

**Returns:** The file size field contains the size in bytes of the entire source file.

### getPdf417MacroSegmentID() {#getpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Gets macro Pdf417 barcode's segment ID, which starts from 0, to MacroSegmentsCount - 1.

### getPdf417MacroSegmentsCount() {#getpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Gets macro Pdf417 barcode segments count.

### getPdf417MacroSender() {#getpdf417macrosender}

> **Deprecated.** See method description for replacement.

Gets macro Pdf417 barcode sender name.

### getPdf417MacroTerminator() {#getpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417.

### getPdf417MacroTimeStamp() {#getpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Gets macro Pdf417 barcode time stamp.

### getPdf417Truncate() {#getpdf417truncate}

> **Deprecated.** See method description for replacement.

Whether Pdf417 symbology type of BarCode is truncated (to reduce space).

### getRows() {#getrows}

Rows count.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1.

### getTruncate() {#gettruncate}

Whether Pdf417 symbology type of BarCode is truncated (to reduce space). Also known as CompactPDF417. Rigth row indicator and right stop pattern are removed in this mode.

### isCode128Emulation() {#iscode128emulation}

Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128 These samples show how to encode Code 128 emulation modes with FNC1 in second position and without. In this way MicroPdf417 can be decoded as Code 128 barcode

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### isLinked() {#islinked}

Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC These samples show how to encode "Linked" UCC/EAN-128 modes in GS1MicroPdf417 and Linkage Flag (918) in MicroPdf417 and Pdf417 barcodes

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### isReaderInitialization() {#isreaderinitialization}

Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization

**Returns:** boolean value

### setAspectRatio() {#setaspectratio}

Height/Width ratio of 2D BarCode module.

### setCode128Emulation() {#setcode128emulation}

Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128 These samples show how to encode Code 128 emulation modes with FNC1 in second position and without. In this way MicroPdf417 can be decoded as Code 128 barcode

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### setColumns() {#setcolumns}

Columns count.

### setECIEncoding() {#seteciencoding}

Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Not applied for Macro PDF417 text fields. Current implementation consists all well known charset encodings.

### setEncodeMode() {#setencodemode}

Identifies Pdf417 encode mode. Default value: Auto.

### setErrorLevel(value) {#seterrorlevel}

Sets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

| Parameter | Description |
| --- | --- |
| value | Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture. |

### setLinked() {#setlinked}

Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC These samples show how to encode "Linked" UCC/EAN-128 modes in GS1MicroPdf417 and Linkage Flag (918) in MicroPdf417 and Pdf417 barcodes

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### setMacroCharacters() {#setmacrocharacters}

Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with MicroPdf417 and encodes 916 and 917 MicroPdf417 modes Default value: MacroCharacters.None. These samples show how to encode Macro Characters in MicroPdf417

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### setMacroPdf417Addressee() {#setmacropdf417addressee}

MacroPdf417 barcode addressee name (optional field). MicroPDF417 barcode addressee name (optional field for Structured Append mode)

### setMacroPdf417Checksum() {#setmacropdf417checksum}

MacroPdf417 barcode checksum (optional field). MicroPDF417 barcode checksum (optional field for Structured Append mode) The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial. x^16 + x^12 + x^5 + 1

### setMacroPdf417ECIEncoding() {#setmacropdf417eciencoding}

Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields.

### setMacroPdf417FileID() {#setmacropdf417fileid}

MacroPdf417 barcode's file ID (Required field). MicroPDF417 barcode's file ID (Required field for Structured Append mode)

### setMacroPdf417FileName() {#setmacropdf417filename}

MacroPdf417 barcode file name (optional field). MicroPDF417 barcode file name (optional field for Structured Append mode)

### setMacroPdf417FileSize() {#setmacropdf417filesize}

MacroPdf417 file size (optional field). MicroPDF417 file size (optional field for Structured Append mode) The file size field contains the size in bytes of the entire source file.

### setMacroPdf417SegmentID() {#setmacropdf417segmentid}

MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. MicroPDF417 barcode's segment ID (Required field for Structured Append mode)

### setMacroPdf417SegmentsCount() {#setmacropdf417segmentscount}

MacroPdf417 barcode segments count (optional field). MicroPDF417 barcode segments count (optional field for Structured Append mode)

### setMacroPdf417Sender() {#setmacropdf417sender}

MacroPdf417 barcode sender name (optional field). MicroPDF417 barcode sender name (optional field for Structured Append mode)

### setMacroPdf417Terminator() {#setmacropdf417terminator}

Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417.

### setMacroPdf417TimeStamp() {#setmacropdf417timestamp}

MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mode)

### setPdf417CompactionMode() {#setpdf417compactionmode}

Pdf417 symbology type of BarCode's compaction mode. Default value: Pdf417CompactionMode.AUTO.

### setPdf417ECIEncoding() {#setpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings.

### setPdf417EncodeMode() {#setpdf417encodemode}

> **Deprecated.** See method description for replacement.

Identifies Pdf417 encode mode. Default value: Auto.

### setPdf417ErrorLevel() {#setpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Sets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### setPdf417MacroAddressee() {#setpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Sets macro Pdf417 barcode addressee name.

### setPdf417MacroChecksum(value) {#setpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Sets macro Pdf417 barcode checksum.

| Parameter | Description |
| --- | --- |
| value | The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial. |

### setPdf417MacroECIEncoding() {#setpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields.

### setPdf417MacroFileID() {#setpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Sets macro Pdf417 barcode's file ID. Used for MacroPdf417.

### setPdf417MacroFileName() {#setpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Sets macro Pdf417 barcode file name.

### setPdf417MacroFileSize(value) {#setpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Sets macro Pdf417 file size.

| Parameter | Description |
| --- | --- |
| value | The file size field contains the size in bytes of the entire source file. |

### setPdf417MacroSegmentID() {#setpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Sets macro Pdf417 barcode's segment ID, which starts from 0, to MacroSegmentsCount - 1.

### setPdf417MacroSegmentsCount() {#setpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Sets macro Pdf417 barcode segments count.

### setPdf417MacroSender() {#setpdf417macrosender}

> **Deprecated.** See method description for replacement.

Sets macro Pdf417 barcode sender name.

### setPdf417MacroTerminator() {#setpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417.

### setPdf417MacroTimeStamp() {#setpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Sets macro Pdf417 barcode time stamp.

### setPdf417Truncate() {#setpdf417truncate}

> **Deprecated.** See method description for replacement.

Whether Pdf417 symbology type of BarCode is truncated (to reduce space).

### setReaderInitialization(value) {#setreaderinitialization}

Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization

| Parameter | Description |
| --- | --- |
| value |  |

### setRows() {#setrows}

Rows count.

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1.

### setTruncate() {#settruncate}

Whether Pdf417 symbology type of BarCode is truncated (to reduce space). Also known as CompactPDF417. Rigth row indicator and right stop pattern are removed in this mode.

### toString() {#tostring}

Returns a human-readable string representation of this Pdf417Parameters.

**Returns:** A string that represents this Pdf417Parameters.
