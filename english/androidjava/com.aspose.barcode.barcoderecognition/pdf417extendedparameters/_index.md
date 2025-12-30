---
title: Pdf417ExtendedParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Stores a MacroPdf417 metadata information of recognized barcode
type: docs
weight: 39
url: /androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

Stores a MacroPdf417 metadata information of recognized barcode

--------------------

> ```
> This sample shows how to get Macro Pdf417 metadata
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MACRO_PDF_417);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
>      System.out.println("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
>      System.out.println("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
>  }
> ```
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified  Pdf417ExtendedParameters  value. |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Macro PDF417 addressee name (optional). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Macro PDF417 checksum (optional). |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Gets the file ID of the barcode, only available with MacroPdf417. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Macro PDF417 file name (optional). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Macro PDF417 file size (optional). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Gets the segment ID of the barcode,only available with MacroPdf417. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Gets macro pdf417 barcode segments count. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Macro PDF417 sender name (optional). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Indicates whether the segment is the last segment of a Macro PDF417 file. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Macro PDF417 time stamp (optional). |
| [hashCode()](#hashCode--) | Returns the hash code for this instance. |
| [isCode128Emulation()](#isCode128Emulation--) | Flag that indicates that the MicroPdf417 barcode encoded with 908, 909, 910 or 911 Code 128 emulation codewords. |
| [isEmpty()](#isEmpty--) | Tests whether all parameters has only default values |
| [isLinked()](#isLinked--) | Flag that indicates that the barcode must be linked to 1D barcode. |
| [isReaderInitialization()](#isReaderInitialization--) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returns a human-readable string representation of this  Pdf417ExtendedParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns a value indicating whether this instance is equal to a specified  Pdf417ExtendedParameters  value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | An System.Object value to compare to this instance. |

**Returns:**
boolean -  **true**  if obj has the same value as this instance; otherwise,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public String getMacroPdf417Addressee()
```


Macro PDF417 addressee name (optional).

**Returns:**
java.lang.String - Addressee name.
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


Macro PDF417 checksum (optional).

**Returns:**
int - Checksum.
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


Gets the file ID of the barcode, only available with MacroPdf417.

Value: The file ID for MacroPdf417

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


Macro PDF417 file name (optional).

**Returns:**
java.lang.String - File name.
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


Macro PDF417 file size (optional).

**Returns:**
int - File size.
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


Gets the segment ID of the barcode,only available with MacroPdf417.

Value: The segment ID of the barcode.

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


Gets macro pdf417 barcode segments count. Default value is -1.

Value: Segments count.

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


Macro PDF417 sender name (optional).

**Returns:**
java.lang.String - Sender name
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


Indicates whether the segment is the last segment of a Macro PDF417 file.

**Returns:**
boolean - Terminator.
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


Macro PDF417 time stamp (optional).

**Returns:**
java.time.LocalDateTime - Time stamp.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code for this instance.

**Returns:**
int - A 32-bit signed integer hash code.
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


Flag that indicates that the MicroPdf417 barcode encoded with 908, 909, 910 or 911 Code 128 emulation codewords.

**Returns:**
boolean - Code 128 emulation flag
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Tests whether all parameters has only default values

Value: Returns  **true**  if all parameters has only default values; otherwise,  **false** .

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


Flag that indicates that the barcode must be linked to 1D barcode.

Value: Linkage flag

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization.

Value: Reader initialization flag

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




### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this  Pdf417ExtendedParameters .

**Returns:**
java.lang.String - A string that represents this  Pdf417ExtendedParameters .
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

