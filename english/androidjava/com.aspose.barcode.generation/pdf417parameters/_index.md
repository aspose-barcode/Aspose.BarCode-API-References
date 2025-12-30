---
title: Pdf417Parameters
second_title: Aspose.BarCode for Android via Java API Reference
description: PDF417 parameters.
type: docs
weight: 60
url: /androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. MicroPDF417 in Structured Append mode (same as MacroPDF417 mode) requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional.

```
These samples show how to encode UCC/EAN-128 non Linked modes in GS1MicroPdf417
 

 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
     for (BarCodeResult result : reader.readBarCodes())
         System.out.println(result.getCodeText());

 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(241)123456789012345(241)ABCD123456789012345");
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
     for (BarCodeResult result : reader.readBarCodes())
         System.out.println(result.getCodeText());
```
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Height/Width ratio of 2D BarCode module. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Columns count. |
| [getMacroCharacters()](#getMacroCharacters--) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. |
| [getPdf417CompactionMode()](#getPdf417CompactionMode--) | Pdf417 symbology type of BarCode's compaction mode. |
| [getPdf417ECIEncoding()](#getPdf417ECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getPdf417EncodeMode()](#getPdf417EncodeMode--) | Identifies Pdf417 encode mode. |
| [getPdf417ErrorLevel()](#getPdf417ErrorLevel--) | Gets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture. |
| [getPdf417MacroAddressee()](#getPdf417MacroAddressee--) | MacroPdf417 barcode addressee name (optional field). |
| [getPdf417MacroChecksum()](#getPdf417MacroChecksum--) | MacroPdf417 barcode checksum (optional field). |
| [getPdf417MacroECIEncoding()](#getPdf417MacroECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getPdf417MacroFileID()](#getPdf417MacroFileID--) | MacroPdf417 barcode's file ID (Required field). |
| [getPdf417MacroFileName()](#getPdf417MacroFileName--) | MacroPdf417 barcode file name (optional field). |
| [getPdf417MacroFileSize()](#getPdf417MacroFileSize--) | MacroPdf417 file size (optional field). |
| [getPdf417MacroSegmentID()](#getPdf417MacroSegmentID--) | MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getPdf417MacroSegmentsCount--) | MacroPdf417 barcode segments count (optional field). |
| [getPdf417MacroSender()](#getPdf417MacroSender--) | MacroPdf417 barcode sender name (optional field). |
| [getPdf417MacroTerminator()](#getPdf417MacroTerminator--) | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. |
| [getPdf417MacroTimeStamp()](#getPdf417MacroTimeStamp--) | MacroPdf417 barcode time stamp (optional field). |
| [getPdf417Truncate()](#getPdf417Truncate--) | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). |
| [getRows()](#getRows--) | Rows count. |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128 |
| [isLinked()](#isLinked--) | Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC |
| [isReaderInitialization()](#isReaderInitialization--) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Height/Width ratio of 2D BarCode module. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128 |
| [setColumns(int value)](#setColumns-int-) | Columns count. |
| [setLinked(boolean value)](#setLinked-boolean-) | Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. |
| [setPdf417CompactionMode(Pdf417CompactionMode value)](#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-) | Pdf417 symbology type of BarCode's compaction mode. |
| [setPdf417ECIEncoding(int value)](#setPdf417ECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setPdf417EncodeMode(Pdf417EncodeMode pdf417EncodeMode)](#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Identifies Pdf417 encode mode. |
| [setPdf417ErrorLevel(Pdf417ErrorLevel value)](#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Sets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture. |
| [setPdf417MacroAddressee(String value)](#setPdf417MacroAddressee-java.lang.String-) | MacroPdf417 barcode addressee name (optional field). |
| [setPdf417MacroChecksum(int value)](#setPdf417MacroChecksum-int-) | Sets macro Pdf417 barcode checksum. |
| [setPdf417MacroECIEncoding(int value)](#setPdf417MacroECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setPdf417MacroFileID(int value)](#setPdf417MacroFileID-int-) | MacroPdf417 barcode's file ID (Required field). |
| [setPdf417MacroFileName(String value)](#setPdf417MacroFileName-java.lang.String-) | MacroPdf417 barcode file name (optional field). |
| [setPdf417MacroFileSize(int value)](#setPdf417MacroFileSize-int-) | MacroPdf417 file size (optional field). |
| [setPdf417MacroSegmentID(int value)](#setPdf417MacroSegmentID-int-) | MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount(int value)](#setPdf417MacroSegmentsCount-int-) | MacroPdf417 barcode segments count (optional field). |
| [setPdf417MacroSender(String value)](#setPdf417MacroSender-java.lang.String-) | MacroPdf417 barcode sender name (optional field). |
| [setPdf417MacroTerminator(Pdf417MacroTerminator value)](#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. |
| [setPdf417MacroTimeStamp(LocalDateTime value)](#setPdf417MacroTimeStamp-java.time.LocalDateTime-) | MacroPdf417 barcode time stamp (optional field). |
| [setPdf417MacroTimeStamp(Date value)](#setPdf417MacroTimeStamp-java.util.Date-) | MacroPdf417 barcode time stamp (optional field). |
| [setPdf417Truncate(boolean value)](#setPdf417Truncate-boolean-) | Whether Pdf417 symbology type of BarCode is truncated (to reduce space). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [setRows(int value)](#setRows-int-) | Rows count. |
| [toString()](#toString--) | Returns a human-readable String representation of this  Pdf417Parameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public float getAspectRatio()
```


Height/Width ratio of 2D BarCode module.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public int getColumns()
```


Columns count.

**Returns:**
int
### getMacroCharacters() {#getMacroCharacters--}
```
public MacroCharacter getMacroCharacters()
```


Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with MicroPdf417 and encodes 916 and 917 MicroPdf417 modes Default value: MacroCharacters.None.

--------------------

> ```
> These samples show how to encode Macro Characters in MicroPdf417
>  
>  //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
>  generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
>      BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
>        for (BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
>  generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_06);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
> ```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getPdf417CompactionMode() {#getPdf417CompactionMode--}
```
public Pdf417CompactionMode getPdf417CompactionMode()
```


Pdf417 symbology type of BarCode's compaction mode. Default value: Pdf417CompactionMode.AUTO.

**Returns:**
[Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode)
### getPdf417ECIEncoding() {#getPdf417ECIEncoding--}
```
public int getPdf417ECIEncoding()
```


Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Not applied for Macro PDF417 text fields. Current implementation consists all well known charset encodings.

**Returns:**
int
### getPdf417EncodeMode() {#getPdf417EncodeMode--}
```
public Pdf417EncodeMode getPdf417EncodeMode()
```


Identifies Pdf417 encode mode. Default value: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getPdf417ErrorLevel() {#getPdf417ErrorLevel--}
```
public Pdf417ErrorLevel getPdf417ErrorLevel()
```


Gets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel)
### getPdf417MacroAddressee() {#getPdf417MacroAddressee--}
```
public String getPdf417MacroAddressee()
```


MacroPdf417 barcode addressee name (optional field). MicroPDF417 barcode addressee name (optional field for Structured Append mode)

**Returns:**
java.lang.String
### getPdf417MacroChecksum() {#getPdf417MacroChecksum--}
```
public int getPdf417MacroChecksum()
```


MacroPdf417 barcode checksum (optional field). MicroPDF417 barcode checksum (optional field for Structured Append mode) The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getPdf417MacroECIEncoding() {#getPdf417MacroECIEncoding--}
```
public int getPdf417MacroECIEncoding()
```


Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields.

**Returns:**
int
### getPdf417MacroFileID() {#getPdf417MacroFileID--}
```
public int getPdf417MacroFileID()
```


MacroPdf417 barcode's file ID (Required field). MicroPDF417 barcode's file ID (Required field for Structured Append mode).

**Returns:**
int
### getPdf417MacroFileName() {#getPdf417MacroFileName--}
```
public String getPdf417MacroFileName()
```


MacroPdf417 barcode file name (optional field). MicroPDF417 barcode file name (optional field for Structured Append mode)

**Returns:**
java.lang.String
### getPdf417MacroFileSize() {#getPdf417MacroFileSize--}
```
public int getPdf417MacroFileSize()
```


MacroPdf417 file size (optional field). MicroPDF417 file size (optional field for Structured Append mode) The file size field contains the size in bytes of the entire source file.

**Returns:**
int
### getPdf417MacroSegmentID() {#getPdf417MacroSegmentID--}
```
public int getPdf417MacroSegmentID()
```


MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. MicroPDF417 barcode's segment ID (Required field for Structured Append mode)

**Returns:**
int
### getPdf417MacroSegmentsCount() {#getPdf417MacroSegmentsCount--}
```
public int getPdf417MacroSegmentsCount()
```


MacroPdf417 barcode segments count (optional field). MicroPDF417 barcode segments count (optional field for Structured Append mode)

**Returns:**
int
### getPdf417MacroSender() {#getPdf417MacroSender--}
```
public String getPdf417MacroSender()
```


MacroPdf417 barcode sender name (optional field). MicroPDF417 barcode sender name (optional field for Structured Append mode)

**Returns:**
java.lang.String
### getPdf417MacroTerminator() {#getPdf417MacroTerminator--}
```
public Pdf417MacroTerminator getPdf417MacroTerminator()
```


Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getPdf417MacroTimeStamp() {#getPdf417MacroTimeStamp--}
```
public LocalDateTime getPdf417MacroTimeStamp()
```


MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mode)

**Returns:**
java.time.LocalDateTime
### getPdf417Truncate() {#getPdf417Truncate--}
```
public boolean getPdf417Truncate()
```


Whether Pdf417 symbology type of BarCode is truncated (to reduce space). Also known as CompactPDF417. Rigth row indicator and right stop pattern are removed in this mode.

**Returns:**
boolean
### getRows() {#getRows--}
```
public int getRows()
```


Rows count.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128

--------------------

> ```
> These samples show how to encode Code 128 emulation modes with FNC1 in second position and without. In this way MicroPdf417 can be decoded as Code 128 barcode
>  
> 
>  //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a1222322323");
>  generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsCode128Emulation:" + Boolean.parseBoolean(result.getExtended().getPdf417().isCode128Emulation()));
>  //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "991222322323");
>  generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsCode128Emulation:" + Boolean.parseBoolean(result.getExtended().getPdf417().isCode128Emulation()));
>  //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "123456789012345678");
>  generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation().toString());
> ```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC

--------------------

> ```
> These samples show how to encode "Linked" UCC/EAN-128 modes in GS1MicroPdf417 and Linkage Flag (918) in MicroPdf417 and Pdf417 barcodes
>  
> 
>  //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
>  //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(13)991231(21)ABCD");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
>  //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(15)991231(10)ABCD");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
>  //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(17)991231(21)ABCD");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
>  //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(10)ABCD12345");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
>  //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(21)ABCD12345");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
>  //Encodes GS1 Linked modes 906, 907 with any AI
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(240)123456789012345");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
>  //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "ABCDE123456789012345678");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
>  //Encodes Pdf417 NON EAN.UCC Linked mode 918
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.PDF_417, "ABCDE123456789012345678");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
> ```

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public void setAspectRatio(float value)
```


Height/Width ratio of 2D BarCode module.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public void setCode128Emulation(boolean value)
```


Can be used only with MicroPdf417 and encodes Code 128 emulation modes Can encode FNC1 in second position modes 908 and 909, also can encode 910 and 911 which just indicate that recognized MicroPdf417 can be interpret as Code 128

--------------------

> ```
> These samples show how to encode Code 128 emulation modes with FNC1 in second position and without. In this way MicroPdf417 can be decoded as Code 128 barcode
>  
> 
>  //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a1222322323");
>  generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.Extended.Pdf417.IisCode128Emulation().toString());
>  //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "991222322323");
>  generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsCode128Emulation:" + Boolean.parseBoolean(result.getExtended().getPdf417().isCode128Emulation()));
>  //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "123456789012345678");
>  generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsCode128Emulation:" + Boolean.parseBoolean(result.getExtended().getPdf417().isCode128Emulation()));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public void setColumns(int value)
```


Columns count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public void setLinked(boolean value)
```


Defines linked modes with GS1MicroPdf417, MicroPdf417 and Pdf417 barcodes With GS1MicroPdf417 symbology encodes 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128 modes With MicroPdf417 and Pdf417 symbologies encodes 918 linkage flag to associated linear component other than an EAN.UCC

--------------------

> ```
> These samples show how to encode "Linked" UCC/EAN-128 modes in GS1MicroPdf417 and Linkage Flag (918) in MicroPdf417 and Pdf417 barcodes
>  
> 
>  //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
>  //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(13)991231(21)ABCD");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
>  //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(15)991231(10)ABCD");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
>  //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(17)991231(21)ABCD");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
>  //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(10)ABCD12345");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
>  //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(21)ABCD12345");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
>  //Encodes GS1 Linked modes 906, 907 with any AI
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(240)123456789012345");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
>  //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "ABCDE123456789012345678");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
>  //Encodes Pdf417 NON EAN.UCC Linked mode 918
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.PDF_417, "ABCDE123456789012345678");
>  generator.getParameters().getBarcode().getPdf417().setLinked(true);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText() + " IsLinked:" + Boolean.parseBoolean(result.getExtended().getPdf417().isLinked()));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public void setMacroCharacters(MacroCharacter value)
```


Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with MicroPdf417 and encodes 916 and 917 MicroPdf417 modes Default value: MacroCharacters.None.

--------------------

> ```
> These samples show how to encode Macro Characters in MicroPdf417
>  
> 
>  //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
>  generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
>      BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
>        for (BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
>  generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_06);
>  BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setPdf417CompactionMode(Pdf417CompactionMode value) {#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-}
```
public void setPdf417CompactionMode(Pdf417CompactionMode value)
```


Pdf417 symbology type of BarCode's compaction mode. Default value: Pdf417CompactionMode.AUTO.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode) |  |

### setPdf417ECIEncoding(int value) {#setPdf417ECIEncoding-int-}
```
public void setPdf417ECIEncoding(int value)
```


Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Not applied for Macro PDF417 text fields. Current implementation consists all well known charset encodings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPdf417EncodeMode(Pdf417EncodeMode pdf417EncodeMode) {#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public void setPdf417EncodeMode(Pdf417EncodeMode pdf417EncodeMode)
```


Identifies Pdf417 encode mode. Default value: Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdf417EncodeMode | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setPdf417ErrorLevel(Pdf417ErrorLevel value) {#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public void setPdf417ErrorLevel(Pdf417ErrorLevel value)
```


Sets Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) |  |

### setPdf417MacroAddressee(String value) {#setPdf417MacroAddressee-java.lang.String-}
```
public void setPdf417MacroAddressee(String value)
```


MacroPdf417 barcode addressee name (optional field). MicroPDF417 barcode addressee name (optional field for Structured Append mode)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPdf417MacroChecksum(int value) {#setPdf417MacroChecksum-int-}
```
public void setPdf417MacroChecksum(int value)
```


Sets macro Pdf417 barcode checksum.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial. |

### setPdf417MacroECIEncoding(int value) {#setPdf417MacroECIEncoding-int-}
```
public void setPdf417MacroECIEncoding(int value)
```


Extended Channel Interpretation Identifiers. Applies for Macro PDF417 text fields.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPdf417MacroFileID(int value) {#setPdf417MacroFileID-int-}
```
public void setPdf417MacroFileID(int value)
```


MacroPdf417 barcode's file ID (Required field). MicroPDF417 barcode's file ID (Required field for Structured Append mode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPdf417MacroFileName(String value) {#setPdf417MacroFileName-java.lang.String-}
```
public void setPdf417MacroFileName(String value)
```


MacroPdf417 barcode file name (optional field). MicroPDF417 barcode file name (optional field for Structured Append mode)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPdf417MacroFileSize(int value) {#setPdf417MacroFileSize-int-}
```
public void setPdf417MacroFileSize(int value)
```


MacroPdf417 file size (optional field). MicroPDF417 file size (optional field for Structured Append mode) The file size field contains the size in bytes of the entire source file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPdf417MacroSegmentID(int value) {#setPdf417MacroSegmentID-int-}
```
public void setPdf417MacroSegmentID(int value)
```


MacroPdf417 barcode's segment ID (Required field), which starts from 0, to MacroSegmentsCount - 1. MicroPDF417 barcode's segment ID (Required field for Structured Append mode)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPdf417MacroSegmentsCount(int value) {#setPdf417MacroSegmentsCount-int-}
```
public void setPdf417MacroSegmentsCount(int value)
```


MacroPdf417 barcode segments count (optional field). MicroPDF417 barcode segments count (optional field for Structured Append mode)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPdf417MacroSender(String value) {#setPdf417MacroSender-java.lang.String-}
```
public void setPdf417MacroSender(String value)
```


MacroPdf417 barcode sender name (optional field). MicroPDF417 barcode sender name (optional field for Structured Append mode)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPdf417MacroTerminator(Pdf417MacroTerminator value) {#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public void setPdf417MacroTerminator(Pdf417MacroTerminator value)
```


Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setPdf417MacroTimeStamp(LocalDateTime value) {#setPdf417MacroTimeStamp-java.time.LocalDateTime-}
```
public void setPdf417MacroTimeStamp(LocalDateTime value)
```


MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mode)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.time.LocalDateTime |  |

### setPdf417MacroTimeStamp(Date value) {#setPdf417MacroTimeStamp-java.util.Date-}
```
public void setPdf417MacroTimeStamp(Date value)
```


MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mode)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### setPdf417Truncate(boolean value) {#setPdf417Truncate-boolean-}
```
public void setPdf417Truncate(boolean value)
```


Whether Pdf417 symbology type of BarCode is truncated (to reduce space). Also known as CompactPDF417. Rigth row indicator and right stop pattern are removed in this mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public void setReaderInitialization(boolean value)
```


Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRows(int value) {#setRows-int-}
```
public void setRows(int value)
```


Rows count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable String representation of this  Pdf417Parameters .

**Returns:**
java.lang.String - A String that represents this  Pdf417Parameters .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

