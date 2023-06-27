---
title: Pdf417Parameters
second_title: Aspose.BarCode for Java API Reference
description: PDF417 parameters.
type: docs
weight: 50
url: /java/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

PDF417 parameters. Contains PDF417, MacroPDF417 and MicroPDF417 parameters. MacroPDF417 requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. MicroPDF417 in Structured Append mode (same as MacroPDF417 mode) requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Height/Width ratio of 2D BarCode module. |
| [getClass()](#getClass--) |  |
| [getCode128Emulation()](#getCode128Emulation--) | Function codeword for Code 128 emulation. |
| [getCodeTextEncoding()](#getCodeTextEncoding--) | Gets the encoding of codetext. |
| [getColumns()](#getColumns--) | Columns count. |
| [getPdf417CompactionMode()](#getPdf417CompactionMode--) | Pdf417 symbology type of BarCode's compaction mode. |
| [getPdf417ECIEncoding()](#getPdf417ECIEncoding--) | Extended Channel Interpretation Identifiers. |
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
| [isReaderInitialization()](#isReaderInitialization--) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Height/Width ratio of 2D BarCode module. |
| [setCode128Emulation(Code128Emulation value)](#setCode128Emulation-com.aspose.barcode.generation.Code128Emulation-) | Function codeword for Code 128 emulation. |
| [setCodeTextEncoding(Charset value)](#setCodeTextEncoding-java.nio.charset.Charset-) | Sets the encoding of codetext. |
| [setColumns(int value)](#setColumns-int-) | Columns count. |
| [setPdf417CompactionMode(Pdf417CompactionMode value)](#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-) | Pdf417 symbology type of BarCode's compaction mode. |
| [setPdf417ECIEncoding(int value)](#setPdf417ECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
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
### getCode128Emulation() {#getCode128Emulation--}
```
public Code128Emulation getCode128Emulation()
```


Function codeword for Code 128 emulation. Applied for MicroPDF417 only. Ignored for PDF417 and MacroPDF417 barcodes.

**Returns:**
[Code128Emulation](../../com.aspose.barcode.generation/code128emulation)
### getCodeTextEncoding() {#getCodeTextEncoding--}
```
public Charset getCodeTextEncoding()
```


Gets the encoding of codetext. Default value: UTF-8

**Returns:**
java.nio.charset.Charset
### getColumns() {#getColumns--}
```
public int getColumns()
```


Columns count.

**Returns:**
int
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
public Date getPdf417MacroTimeStamp()
```


MacroPdf417 barcode time stamp (optional field). MicroPDF417 barcode time stamp (optional field for Structured Append mode)

**Returns:**
java.util.Date
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

### setCode128Emulation(Code128Emulation value) {#setCode128Emulation-com.aspose.barcode.generation.Code128Emulation-}
```
public void setCode128Emulation(Code128Emulation value)
```


Function codeword for Code 128 emulation. Applied for MicroPDF417 only. Ignored for PDF417 and MacroPDF417 barcodes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Code128Emulation](../../com.aspose.barcode.generation/code128emulation) |  |

### setCodeTextEncoding(Charset value) {#setCodeTextEncoding-java.nio.charset.Charset-}
```
public void setCodeTextEncoding(Charset value)
```


Sets the encoding of codetext. Default value: UTF-8

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setColumns(int value) {#setColumns-int-}
```
public void setColumns(int value)
```


Columns count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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
public final native void wait(long arg0)
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

