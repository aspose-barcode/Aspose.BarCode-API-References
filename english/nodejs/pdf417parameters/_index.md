---
title: "Pdf417Parameters Class"
linktitle: "Pdf417Parameters"
articleTitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for Node.js via Java"
description: "PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fields: Pdf417MacroFileID and Pdf417Macr..."
type: docs
weight: 630
url: /nodejs/pdf417parameters/
---
## Pdf417Parameters class

PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. MicroPDF417 in Structured Append mode (same as MacroPDF417 mode) requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional.

```javascript
public class Pdf417Parameters : joint.BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [Pdf417Parameters](./pdf417parameters/#constructor)(*object*) | Initializes a new instance of the Pdf417Parameters class. |

## Methods

| Name | Description |
| --- | --- |
| [getAspectRatio](./getaspectratio/) | Height/Width ratio of 2D BarCode module. |
| [getColumns](./getcolumns/) | Columns count. |
| [getECIEncoding](./geteciencoding/) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Not applied for Macro PDF417 text fields. Current implementation consists all well known charset encodings. |
| [getEncodeMode](./getencodemode/) | Identifies Pdf417 encode mode. Default value: Auto. |
| [getErrorLevel](./geterrorlevel/) | Gets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture. |
| [getMacroCharacters](./getmacrocharacters/) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with MicroPdf417 and encodes 916 and 917 MicroPdf417 modes Default value: MacroCharacters.None. |
| [getMacroPdf417Addressee](./getmacropdf417addressee/) | MacroPdf417 barcode addressee name (optional field). MicroPDF417 barcode addressee name (optional field for Structured Append mode). |
| [getMacroPdf417Checksum](./getmacropdf417checksum/) | MacroPdf417 barcode checksum (optional field). MicroPDF417 barcode checksum (optional field for Structured Append mode) The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial. x^16 + x^12 + x^5 + 1. |
| [getMacroPdf417ECIEncoding](./getmacropdf417eciencoding/) | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [getMacroPdf417FileID](./getmacropdf417fileid/) | MacroPdf417 barcode's file ID (Required field). MicroPDF417 barcode's file ID (Required field for Structured Append mode). |
| [getMacroPdf417FileName](./getmacropdf417filename/) | MacroPdf417 barcode file name (optional field). MicroPDF417 barcode file name (optional field for Structured Append mode). |
| [getMacroPdf417FileSize](./getmacropdf417filesize/) | MacroPdf417 file size (optional field). MicroPDF417 file size (optional field for Structured Append mode) The file size field contains the size in bytes of the entire source file. |
| [getMacroPdf417SegmentID](./getmacropdf417segmentid/) | MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. MicroPDF417 barcode's segment ID (Required field for Structured Append mode). |
| [getMacroPdf417SegmentsCount](./getmacropdf417segmentscount/) | MacroPdf417 barcode segments count (optional field). MicroPDF417 barcode segments count (optional field for Structured Append mode). |
| [getMacroPdf417Sender](./getmacropdf417sender/) | MacroPdf417 barcode sender name (optional field). MicroPDF417 barcode sender name (optional field for Structured Append mode). |
| [getMacroPdf417Terminator](./getmacropdf417terminator/) | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417. |
| [getMacroPdf417TimeStamp](./getmacropdf417timestamp/) | MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mode). |
| [getPdf417CompactionMode](./getpdf417compactionmode/) | Pdf417 symbology type of BarCode's compaction mode. Default value: Pdf417CompactionMode.AUTO. |
| [getPdf417ECIEncoding](./getpdf417eciencoding/) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. |
| [getPdf417EncodeMode](./getpdf417encodemode/) | Identifies Pdf417 encode mode. Default value: Auto. |
| [getPdf417ErrorLevel](./getpdf417errorlevel/) | Gets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture. |
| [getPdf417MacroAddressee](./getpdf417macroaddressee/) | Gets macro Pdf417 barcode addressee name. |
| [getPdf417MacroChecksum](./getpdf417macrochecksum/) | Gets macro Pdf417 barcode checksum. |
| [getPdf417MacroECIEncoding](./getpdf417macroeciencoding/) | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [getPdf417MacroFileID](./getpdf417macrofileid/) | Getsmacro Pdf417 barcode's file ID. Used for MacroPdf417. |
| [getPdf417MacroFileName](./getpdf417macrofilename/) | Gets macro Pdf417 barcode file name. |
| [getPdf417MacroFileSize](./getpdf417macrofilesize/) | Gets macro Pdf417 file size. |
| [getPdf417MacroSegmentID](./getpdf417macrosegmentid/) | Gets macro Pdf417 barcode's segment ID, which starts from 0, to MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount](./getpdf417macrosegmentscount/) | Gets macro Pdf417 barcode segments count. |
| [getPdf417MacroSender](./getpdf417macrosender/) | Gets macro Pdf417 barcode sender name. |
| [getPdf417MacroTerminator](./getpdf417macroterminator/) | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417. |
| [getPdf417MacroTimeStamp](./getpdf417macrotimestamp/) | Gets macro Pdf417 barcode time stamp. |
| [getPdf417Truncate](./getpdf417truncate/) | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). |
| [getRows](./getrows/) | Rows count. |
| [getStructuredAppendModeBarcodeId](./getstructuredappendmodebarcodeid/) | Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. |
| [getTruncate](./gettruncate/) | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). Also known as CompactPDF417. Rigth row indicator and right stop pattern are removed in this mode. |
| [init](./init/) |  |
| [isCode128Emulation](./iscode128emulation/) | Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128. |
| [isLinked](./islinked/) | Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC. |
| [isReaderInitialization](./isreaderinitialization/) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [setAspectRatio](./setaspectratio/)(*object*) | Height/Width ratio of 2D BarCode module. |
| [setCode128Emulation](./setcode128emulation/)(*object*) | Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128. |
| [setColumns](./setcolumns/)(*object*) | Columns count. |
| [setECIEncoding](./seteciencoding/)(*object*) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Not applied for Macro PDF417 text fields. Current implementation consists all well known charset encodings. |
| [setEncodeMode](./setencodemode/)(*object*) | Identifies Pdf417 encode mode. Default value: Auto. |
| [setErrorLevel](./seterrorlevel/)(*object*) | Sets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture. |
| [setLinked](./setlinked/)(*object*) | Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC. |
| [setMacroCharacters](./setmacrocharacters/)(*object*) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with MicroPdf417 and encodes 916 and 917 MicroPdf417 modes Default value: MacroCharacters.None. |
| [setMacroPdf417Addressee](./setmacropdf417addressee/)(*object*) | MacroPdf417 barcode addressee name (optional field). MicroPDF417 barcode addressee name (optional field for Structured Append mode). |
| [setMacroPdf417Checksum](./setmacropdf417checksum/)(*object*) | MacroPdf417 barcode checksum (optional field). MicroPDF417 barcode checksum (optional field for Structured Append mode) The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial. x^16 + x^12 + x^5 + 1. |
| [setMacroPdf417ECIEncoding](./setmacropdf417eciencoding/)(*object*) | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [setMacroPdf417FileID](./setmacropdf417fileid/)(*object*) | MacroPdf417 barcode's file ID (Required field). MicroPDF417 barcode's file ID (Required field for Structured Append mode). |
| [setMacroPdf417FileName](./setmacropdf417filename/)(*object*) | MacroPdf417 barcode file name (optional field). MicroPDF417 barcode file name (optional field for Structured Append mode). |
| [setMacroPdf417FileSize](./setmacropdf417filesize/)(*object*) | MacroPdf417 file size (optional field). MicroPDF417 file size (optional field for Structured Append mode) The file size field contains the size in bytes of the entire source file. |
| [setMacroPdf417SegmentID](./setmacropdf417segmentid/)(*object*) | MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. MicroPDF417 barcode's segment ID (Required field for Structured Append mode). |
| [setMacroPdf417SegmentsCount](./setmacropdf417segmentscount/)(*object*) | MacroPdf417 barcode segments count (optional field). MicroPDF417 barcode segments count (optional field for Structured Append mode). |
| [setMacroPdf417Sender](./setmacropdf417sender/)(*object*) | MacroPdf417 barcode sender name (optional field). MicroPDF417 barcode sender name (optional field for Structured Append mode). |
| [setMacroPdf417Terminator](./setmacropdf417terminator/)(*object*) | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417. |
| [setMacroPdf417TimeStamp](./setmacropdf417timestamp/)(*object*) | MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mode). |
| [setPdf417CompactionMode](./setpdf417compactionmode/)(*object*) | Pdf417 symbology type of BarCode's compaction mode. Default value: Pdf417CompactionMode.AUTO. |
| [setPdf417ECIEncoding](./setpdf417eciencoding/)(*object*) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. |
| [setPdf417EncodeMode](./setpdf417encodemode/)(*object*) | Identifies Pdf417 encode mode. Default value: Auto. |
| [setPdf417ErrorLevel](./setpdf417errorlevel/)(*object*) | Sets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture. |
| [setPdf417MacroAddressee](./setpdf417macroaddressee/)(*object*) | Sets macro Pdf417 barcode addressee name. |
| [setPdf417MacroChecksum](./setpdf417macrochecksum/)(*object*) | Sets macro Pdf417 barcode checksum. |
| [setPdf417MacroECIEncoding](./setpdf417macroeciencoding/)(*object*) | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [setPdf417MacroFileID](./setpdf417macrofileid/)(*object*) | Sets macro Pdf417 barcode's file ID. Used for MacroPdf417. |
| [setPdf417MacroFileName](./setpdf417macrofilename/)(*object*) | Sets macro Pdf417 barcode file name. |
| [setPdf417MacroFileSize](./setpdf417macrofilesize/)(*object*) | Sets macro Pdf417 file size. |
| [setPdf417MacroSegmentID](./setpdf417macrosegmentid/)(*object*) | Sets macro Pdf417 barcode's segment ID, which starts from 0, to MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount](./setpdf417macrosegmentscount/)(*object*) | Sets macro Pdf417 barcode segments count. |
| [setPdf417MacroSender](./setpdf417macrosender/)(*object*) | Sets macro Pdf417 barcode sender name. |
| [setPdf417MacroTerminator](./setpdf417macroterminator/)(*object*) | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417. |
| [setPdf417MacroTimeStamp](./setpdf417macrotimestamp/)(*object*) | Sets macro Pdf417 barcode time stamp. |
| [setPdf417Truncate](./setpdf417truncate/)(*object*) | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). |
| [setReaderInitialization](./setreaderinitialization/)(*object*) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [setRows](./setrows/)(*object*) | Rows count. |
| [setStructuredAppendModeBarcodeId](./setstructuredappendmodebarcodeid/)(*object*) | Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. |
| [setTruncate](./settruncate/)(*object*) | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). Also known as CompactPDF417. Rigth row indicator and right stop pattern are removed in this mode. |
| [toString](./tostring/) | Returns a human-readable string representation of this Pdf417Parameters. |

## Examples

# Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)

```javascript
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log( result.getCodeText());
}
```

# Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI

```javascript
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(241)123456789012345(241)ABCD123456789012345");
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log( result.getCodeText());
}
</pre>
</pre>
</p>
```

### See Also

* assembly [Aspose.BarCode](../)

