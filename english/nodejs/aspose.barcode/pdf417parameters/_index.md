---
title: "Pdf417Parameters Class"
linktitle: "Pdf417Parameters"
articleTitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for Node.js via Java"
description: "PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fields: Pdf417MacroFileID and Pdf417Macr..."
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
| [getAspectRatio()](./getaspectratio/) | Height/Width ratio of 2D BarCode module. |
| [getColumns()](./getcolumns/) | Columns count. |
| [getECIEncoding()](./geteciencoding/) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for |
| [getEncodeMode()](./getencodemode/) | Identifies Pdf417 encode mode. Default value: Auto. |
| [getErrorLevel()](./geterrorlevel/) | Gets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error corr |
| [getMacroCharacters()](./getmacrocharacters/) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with Micro |
| [getMacroPdf417Addressee()](./getmacropdf417addressee/) | MacroPdf417 barcode addressee name (optional field). MicroPDF417 barcode addressee name (optional field for Structured A |
| [getMacroPdf417Checksum()](./getmacropdf417checksum/) | MacroPdf417 barcode checksum (optional field). MicroPDF417 barcode checksum (optional field for Structured Append mode)  |
| [getMacroPdf417ECIEncoding()](./getmacropdf417eciencoding/) | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [getMacroPdf417FileID()](./getmacropdf417fileid/) | MacroPdf417 barcode's file ID (Required field). MicroPDF417 barcode's file ID (Required field for Structured Append mode |
| [getMacroPdf417FileName()](./getmacropdf417filename/) | MacroPdf417 barcode file name (optional field). MicroPDF417 barcode file name (optional field for Structured Append mode |
| [getMacroPdf417FileSize()](./getmacropdf417filesize/) | MacroPdf417 file size (optional field). MicroPDF417 file size (optional field for Structured Append mode) The file size  |
| [getMacroPdf417SegmentID()](./getmacropdf417segmentid/) | MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. MicroPDF417 barcode's |
| [getMacroPdf417SegmentsCount()](./getmacropdf417segmentscount/) | MacroPdf417 barcode segments count (optional field). MicroPDF417 barcode segments count (optional field for Structured A |
| [getMacroPdf417Sender()](./getmacropdf417sender/) | MacroPdf417 barcode sender name (optional field). MicroPDF417 barcode sender name (optional field for Structured Append  |
| [getMacroPdf417Terminator()](./getmacropdf417terminator/) | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PD |
| [getMacroPdf417TimeStamp()](./getmacropdf417timestamp/) | MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mo |
| [getPdf417CompactionMode()](./getpdf417compactionmode/) | Pdf417 symbology type of BarCode's compaction mode. Default value: Pdf417CompactionMode.AUTO. |
| [getPdf417ECIEncoding()](./getpdf417eciencoding/) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for |
| [getPdf417EncodeMode()](./getpdf417encodemode/) | Identifies Pdf417 encode mode. Default value: Auto. |
| [getPdf417ErrorLevel()](./getpdf417errorlevel/) ~~(deprecated)~~ | Gets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error corr |
| [getPdf417MacroAddressee()](./getpdf417macroaddressee/) ~~(deprecated)~~ | Gets macro Pdf417 barcode addressee name. |
| [getPdf417MacroChecksum()](./getpdf417macrochecksum/) ~~(deprecated)~~ | Gets macro Pdf417 barcode checksum. |
| [getPdf417MacroECIEncoding()](./getpdf417macroeciencoding/) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [getPdf417MacroFileID()](./getpdf417macrofileid/) ~~(deprecated)~~ | Getsmacro Pdf417 barcode's file ID. Used for MacroPdf417. |
| [getPdf417MacroFileName()](./getpdf417macrofilename/) ~~(deprecated)~~ | Gets macro Pdf417 barcode file name. |
| [getPdf417MacroFileSize()](./getpdf417macrofilesize/) ~~(deprecated)~~ | Gets macro Pdf417 file size. |
| [getPdf417MacroSegmentID()](./getpdf417macrosegmentid/) ~~(deprecated)~~ | Gets macro Pdf417 barcode's segment ID, which starts from 0, to MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](./getpdf417macrosegmentscount/) ~~(deprecated)~~ | Gets macro Pdf417 barcode segments count. |
| [getPdf417MacroSender()](./getpdf417macrosender/) ~~(deprecated)~~ | Gets macro Pdf417 barcode sender name. |
| [getPdf417MacroTerminator()](./getpdf417macroterminator/) ~~(deprecated)~~ | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PD |
| [getPdf417MacroTimeStamp()](./getpdf417macrotimestamp/) ~~(deprecated)~~ | Gets macro Pdf417 barcode time stamp. |
| [getPdf417Truncate()](./getpdf417truncate/) ~~(deprecated)~~ | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). |
| [getRows()](./getrows/) | Rows count. |
| [getStructuredAppendModeBarcodeId()](./getstructuredappendmodebarcodeid/) | Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes  |
| [getTruncate()](./gettruncate/) | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). Also known as CompactPDF417. Rigth row indicato |
| [isCode128Emulation()](./iscode128emulation/) | Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and  |
| [isLinked()](./islinked/) | Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907 |
| [isReaderInitialization()](./isreaderinitialization/) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization |
| [setAspectRatio()](./setaspectratio/) | Height/Width ratio of 2D BarCode module. |
| [setCode128Emulation()](./setcode128emulation/) | Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and  |
| [setColumns()](./setcolumns/) | Columns count. |
| [setECIEncoding()](./seteciencoding/) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for |
| [setEncodeMode()](./setencodemode/) | Identifies Pdf417 encode mode. Default value: Auto. |
| [setErrorLevel(value)](./seterrorlevel/) | Sets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error corr |
| [setLinked()](./setlinked/) | Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907 |
| [setMacroCharacters()](./setmacrocharacters/) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with Micro |
| [setMacroPdf417Addressee()](./setmacropdf417addressee/) | MacroPdf417 barcode addressee name (optional field). MicroPDF417 barcode addressee name (optional field for Structured A |
| [setMacroPdf417Checksum()](./setmacropdf417checksum/) | MacroPdf417 barcode checksum (optional field). MicroPDF417 barcode checksum (optional field for Structured Append mode)  |
| [setMacroPdf417ECIEncoding()](./setmacropdf417eciencoding/) | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [setMacroPdf417FileID()](./setmacropdf417fileid/) | MacroPdf417 barcode's file ID (Required field). MicroPDF417 barcode's file ID (Required field for Structured Append mode |
| [setMacroPdf417FileName()](./setmacropdf417filename/) | MacroPdf417 barcode file name (optional field). MicroPDF417 barcode file name (optional field for Structured Append mode |
| [setMacroPdf417FileSize()](./setmacropdf417filesize/) | MacroPdf417 file size (optional field). MicroPDF417 file size (optional field for Structured Append mode) The file size  |
| [setMacroPdf417SegmentID()](./setmacropdf417segmentid/) | MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. MicroPDF417 barcode's |
| [setMacroPdf417SegmentsCount()](./setmacropdf417segmentscount/) | MacroPdf417 barcode segments count (optional field). MicroPDF417 barcode segments count (optional field for Structured A |
| [setMacroPdf417Sender()](./setmacropdf417sender/) | MacroPdf417 barcode sender name (optional field). MicroPDF417 barcode sender name (optional field for Structured Append  |
| [setMacroPdf417Terminator()](./setmacropdf417terminator/) | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PD |
| [setMacroPdf417TimeStamp()](./setmacropdf417timestamp/) | MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mo |
| [setPdf417CompactionMode()](./setpdf417compactionmode/) | Pdf417 symbology type of BarCode's compaction mode. Default value: Pdf417CompactionMode.AUTO. |
| [setPdf417ECIEncoding()](./setpdf417eciencoding/) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for |
| [setPdf417EncodeMode()](./setpdf417encodemode/) ~~(deprecated)~~ | Identifies Pdf417 encode mode. Default value: Auto. |
| [setPdf417ErrorLevel()](./setpdf417errorlevel/) ~~(deprecated)~~ | Sets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error corr |
| [setPdf417MacroAddressee()](./setpdf417macroaddressee/) ~~(deprecated)~~ | Sets macro Pdf417 barcode addressee name. |
| [setPdf417MacroChecksum(value)](./setpdf417macrochecksum/) ~~(deprecated)~~ | Sets macro Pdf417 barcode checksum. |
| [setPdf417MacroECIEncoding()](./setpdf417macroeciencoding/) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [setPdf417MacroFileID()](./setpdf417macrofileid/) ~~(deprecated)~~ | Sets macro Pdf417 barcode's file ID. Used for MacroPdf417. |
| [setPdf417MacroFileName()](./setpdf417macrofilename/) ~~(deprecated)~~ | Sets macro Pdf417 barcode file name. |
| [setPdf417MacroFileSize(value)](./setpdf417macrofilesize/) ~~(deprecated)~~ | Sets macro Pdf417 file size. |
| [setPdf417MacroSegmentID()](./setpdf417macrosegmentid/) ~~(deprecated)~~ | Sets macro Pdf417 barcode's segment ID, which starts from 0, to MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount()](./setpdf417macrosegmentscount/) ~~(deprecated)~~ | Sets macro Pdf417 barcode segments count. |
| [setPdf417MacroSender()](./setpdf417macrosender/) ~~(deprecated)~~ | Sets macro Pdf417 barcode sender name. |
| [setPdf417MacroTerminator()](./setpdf417macroterminator/) ~~(deprecated)~~ | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PD |
| [setPdf417MacroTimeStamp()](./setpdf417macrotimestamp/) ~~(deprecated)~~ | Sets macro Pdf417 barcode time stamp. |
| [setPdf417Truncate()](./setpdf417truncate/) ~~(deprecated)~~ | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). |
| [setReaderInitialization(value)](./setreaderinitialization/) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization |
| [setRows()](./setrows/) | Rows count. |
| [setStructuredAppendModeBarcodeId()](./setstructuredappendmodebarcodeid/) | Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes  |
| [setTruncate()](./settruncate/) | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). Also known as CompactPDF417. Rigth row indicato |
| [toString()](./tostring/) | Returns a human-readable string representation of this Pdf417Parameters. |
