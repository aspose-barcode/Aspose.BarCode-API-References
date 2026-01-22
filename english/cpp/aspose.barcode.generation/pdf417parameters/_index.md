---
title: Aspose::BarCode::Generation::Pdf417Parameters class
linktitle: Pdf417Parameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::Pdf417Parameters class. PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. MicroPDF417 in Structured Append mode (same as MacroPDF417 mode) requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional in C++.'
type: docs
weight: 3600
url: /cpp/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class


PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. MicroPDF417 in Structured Append mode (same as MacroPDF417 mode) requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional.

```cpp
class Pdf417Parameters : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() | Height/Width ratio of 2D [BarCode](../../aspose.barcode/) module. |
| [get_Columns](./get_columns/)() const | Columns count. |
| [get_ECIEncoding](./get_eciencoding/)() const | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Not applied for Macro PDF417 text fields. Current implementation consists all well known charset encodings. |
| [get_EncodeMode](./get_encodemode/)() const | Identifies Pdf417 encode mode. Default value: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Gets Pdf417 symbology type of [BarCode](../../aspose.barcode/)'s error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture. |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128 |
| [get_IsLinked](./get_islinked/)() const | Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [get_MacroCharacters](./get_macrocharacters/)() const | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with MicroPdf417 and encodes 916 and 917 MicroPdf417 modes Default value: [MacroCharacters.None](../barcodeclassifications/). |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | MacroPdf417 barcode addressee name (optional field). MicroPDF417 barcode addressee name (optional field for Structured Append mode) |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | MacroPdf417 barcode checksum (optional field). MicroPDF417 barcode checksum (optional field for Structured Append mode) The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial. x^16 + x^12 + x^5 + 1 |
| [get_MacroPdf417ECIEncoding](./get_macropdf417eciencoding/)() const | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | MacroPdf417 barcode's file ID (Required field). MicroPDF417 barcode's file ID (Required field for Structured Append mode) |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | MacroPdf417 barcode file name (optional field). MicroPDF417 barcode file name (optional field for Structured Append mode) |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | MacroPdf417 file size (optional field). MicroPDF417 file size (optional field for Structured Append mode) The file size field contains the size in bytes of the entire source file. |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. MicroPDF417 barcode's segment ID (Required field for Structured Append mode) |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | MacroPdf417 barcode segments count (optional field). MicroPDF417 barcode segments count (optional field for Structured Append mode) |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | MacroPdf417 barcode sender name (optional field). MicroPDF417 barcode sender name (optional field for Structured Append mode) |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mode) |
| [get_Pdf417CompactionMode](./get_pdf417compactionmode/)() const | Pdf417 symbology type of [BarCode](../../aspose.barcode/)'s compaction mode. Default value: [Pdf417CompactionMode.Auto](../aztecencodemode/). |
| [get_Pdf417ECIEncoding](./get_pdf417eciencoding/)() | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Not applied for Macro PDF417 text fields. Current implementation consists all well known charset encodings. |
| [get_Pdf417EncodeMode](./get_pdf417encodemode/)() | Identifies Pdf417 encode mode. Default value: Auto. |
| [get_Pdf417ErrorLevel](./get_pdf417errorlevel/)() | Gets Pdf417 symbology type of [BarCode](../../aspose.barcode/)'s error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture. |
| [get_Pdf417MacroAddressee](./get_pdf417macroaddressee/)() | MacroPdf417 barcode addressee name (optional field). MicroPDF417 barcode addressee name (optional field for Structured Append mode) |
| [get_Pdf417MacroChecksum](./get_pdf417macrochecksum/)() | MacroPdf417 barcode checksum (optional field). MicroPDF417 barcode checksum (optional field for Structured Append mode) The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial. x^16 + x^12 + x^5 + 1 |
| [get_Pdf417MacroECIEncoding](./get_pdf417macroeciencoding/)() | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [get_Pdf417MacroFileID](./get_pdf417macrofileid/)() | MacroPdf417 barcode's file ID (Required field). MicroPDF417 barcode's file ID (Required field for Structured Append mode) |
| [get_Pdf417MacroFileName](./get_pdf417macrofilename/)() | MacroPdf417 barcode file name (optional field). MicroPDF417 barcode file name (optional field for Structured Append mode) |
| [get_Pdf417MacroFileSize](./get_pdf417macrofilesize/)() | MacroPdf417 file size (optional field). MicroPDF417 file size (optional field for Structured Append mode) The file size field contains the size in bytes of the entire source file. |
| [get_Pdf417MacroSegmentID](./get_pdf417macrosegmentid/)() | MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. MicroPDF417 barcode's segment ID (Required field for Structured Append mode) |
| [get_Pdf417MacroSegmentsCount](./get_pdf417macrosegmentscount/)() | MacroPdf417 barcode segments count (optional field). MicroPDF417 barcode segments count (optional field for Structured Append mode) |
| [get_Pdf417MacroSender](./get_pdf417macrosender/)() | MacroPdf417 barcode sender name (optional field). MicroPDF417 barcode sender name (optional field for Structured Append mode) |
| [get_Pdf417MacroTerminator](./get_pdf417macroterminator/)() | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417. |
| [get_Pdf417MacroTimeStamp](./get_pdf417macrotimestamp/)() | MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mode) |
| [get_Pdf417Truncate](./get_pdf417truncate/)() | Whether Pdf417 symbology type of [BarCode](../../aspose.barcode/) is truncated (to reduce space). Also known as CompactPDF417. Rigth row indicator and right stop pattern are removed in this mode. |
| [get_Rows](./get_rows/)() const | Rows count. |
| [get_Truncate](./get_truncate/)() const | Whether Pdf417 symbology type of [BarCode](../../aspose.barcode/) is truncated (to reduce space). Also known as CompactPDF417. Rigth row indicator and right stop pattern are removed in this mode. |
| [set_AspectRatio](./set_aspectratio/)(float) | Height/Width ratio of 2D [BarCode](../../aspose.barcode/) module. |
| [set_Columns](./set_columns/)(int32_t) | Columns count. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Not applied for Macro PDF417 text fields. Current implementation consists all well known charset encodings. |
| [set_EncodeMode](./set_encodemode/)(Aspose::BarCode::Generation::Pdf417EncodeMode) | Identifies Pdf417 encode mode. Default value: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(Aspose::BarCode::Generation::Pdf417ErrorLevel) | Sets Pdf417 symbology type of [BarCode](../../aspose.barcode/)'s error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture. |
| [set_IsCode128Emulation](./set_iscode128emulation/)(bool) | Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128 |
| [set_IsLinked](./set_islinked/)(bool) | Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with MicroPdf417 and encodes 916 and 917 MicroPdf417 modes Default value: [MacroCharacters.None](../barcodeclassifications/). |
| [set_MacroPdf417Addressee](./set_macropdf417addressee/)(System::String) | MacroPdf417 barcode addressee name (optional field). MicroPDF417 barcode addressee name (optional field for Structured Append mode) |
| [set_MacroPdf417Checksum](./set_macropdf417checksum/)(int32_t) | MacroPdf417 barcode checksum (optional field). MicroPDF417 barcode checksum (optional field for Structured Append mode) The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial. x^16 + x^12 + x^5 + 1 |
| [set_MacroPdf417ECIEncoding](./set_macropdf417eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [set_MacroPdf417FileID](./set_macropdf417fileid/)(int32_t) | MacroPdf417 barcode's file ID (Required field). MicroPDF417 barcode's file ID (Required field for Structured Append mode) |
| [set_MacroPdf417FileName](./set_macropdf417filename/)(System::String) | MacroPdf417 barcode file name (optional field). MicroPDF417 barcode file name (optional field for Structured Append mode) |
| [set_MacroPdf417FileSize](./set_macropdf417filesize/)(int32_t) | MacroPdf417 file size (optional field). MicroPDF417 file size (optional field for Structured Append mode) The file size field contains the size in bytes of the entire source file. |
| [set_MacroPdf417SegmentID](./set_macropdf417segmentid/)(int32_t) | MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. MicroPDF417 barcode's segment ID (Required field for Structured Append mode) |
| [set_MacroPdf417SegmentsCount](./set_macropdf417segmentscount/)(int32_t) | MacroPdf417 barcode segments count (optional field). MicroPDF417 barcode segments count (optional field for Structured Append mode) |
| [set_MacroPdf417Sender](./set_macropdf417sender/)(System::String) | MacroPdf417 barcode sender name (optional field). MicroPDF417 barcode sender name (optional field for Structured Append mode) |
| [set_MacroPdf417Terminator](./set_macropdf417terminator/)(Aspose::BarCode::Generation::Pdf417MacroTerminator) | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417. |
| [set_MacroPdf417TimeStamp](./set_macropdf417timestamp/)(System::DateTime) | MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mode) |
| [set_Pdf417CompactionMode](./set_pdf417compactionmode/)(Aspose::BarCode::Generation::Pdf417CompactionMode) | Pdf417 symbology type of [BarCode](../../aspose.barcode/)'s compaction mode. Default value: [Pdf417CompactionMode.Auto](../aztecencodemode/). |
| [set_Pdf417ECIEncoding](./set_pdf417eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Not applied for Macro PDF417 text fields. Current implementation consists all well known charset encodings. |
| [set_Pdf417EncodeMode](./set_pdf417encodemode/)(Aspose::BarCode::Generation::Pdf417EncodeMode) | Identifies Pdf417 encode mode. Default value: Auto. |
| [set_Pdf417ErrorLevel](./set_pdf417errorlevel/)(Aspose::BarCode::Generation::Pdf417ErrorLevel) | Sets Pdf417 symbology type of [BarCode](../../aspose.barcode/)'s error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture. |
| [set_Pdf417MacroAddressee](./set_pdf417macroaddressee/)(System::String) | MacroPdf417 barcode addressee name (optional field). MicroPDF417 barcode addressee name (optional field for Structured Append mode) |
| [set_Pdf417MacroChecksum](./set_pdf417macrochecksum/)(int32_t) | MacroPdf417 barcode checksum (optional field). MicroPDF417 barcode checksum (optional field for Structured Append mode) The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial. x^16 + x^12 + x^5 + 1 |
| [set_Pdf417MacroECIEncoding](./set_pdf417macroeciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields. |
| [set_Pdf417MacroFileID](./set_pdf417macrofileid/)(int32_t) | MacroPdf417 barcode's file ID (Required field). MicroPDF417 barcode's file ID (Required field for Structured Append mode) |
| [set_Pdf417MacroFileName](./set_pdf417macrofilename/)(System::String) | MacroPdf417 barcode file name (optional field). MicroPDF417 barcode file name (optional field for Structured Append mode) |
| [set_Pdf417MacroFileSize](./set_pdf417macrofilesize/)(int32_t) | MacroPdf417 file size (optional field). MicroPDF417 file size (optional field for Structured Append mode) The file size field contains the size in bytes of the entire source file. |
| [set_Pdf417MacroSegmentID](./set_pdf417macrosegmentid/)(int32_t) | MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. MicroPDF417 barcode's segment ID (Required field for Structured Append mode) |
| [set_Pdf417MacroSegmentsCount](./set_pdf417macrosegmentscount/)(int32_t) | MacroPdf417 barcode segments count (optional field). MicroPDF417 barcode segments count (optional field for Structured Append mode) |
| [set_Pdf417MacroSender](./set_pdf417macrosender/)(System::String) | MacroPdf417 barcode sender name (optional field). MicroPDF417 barcode sender name (optional field for Structured Append mode) |
| [set_Pdf417MacroTerminator](./set_pdf417macroterminator/)(Aspose::BarCode::Generation::Pdf417MacroTerminator) | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417. |
| [set_Pdf417MacroTimeStamp](./set_pdf417macrotimestamp/)(System::DateTime) | MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mode) |
| [set_Pdf417Truncate](./set_pdf417truncate/)(bool) | Whether Pdf417 symbology type of [BarCode](../../aspose.barcode/) is truncated (to reduce space). Also known as CompactPDF417. Rigth row indicator and right stop pattern are removed in this mode. |
| [set_Rows](./set_rows/)(int32_t) | Rows count. |
| [set_Truncate](./set_truncate/)(bool) | Whether Pdf417 symbology type of [BarCode](../../aspose.barcode/) is truncated (to reduce space). Also known as CompactPDF417. Rigth row indicator and right stop pattern are removed in this mode. |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [Pdf417Parameters](./). |
## Remarks


These samples show how to encode UCC/EAN-128 non Linked modes in GS1MicroPdf417 
```cpp
[C#]
//Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
