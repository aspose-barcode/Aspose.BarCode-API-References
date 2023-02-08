---
title: MicroPDF417CodeWordsParser
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding/micropdf417codewordsparser/
---
**Inheritance:**
java.lang.Object
```
public class MicroPDF417CodeWordsParser
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MicroPDF417CodeWordsParser(int columns, int rows, Int32List codeWords)](#MicroPDF417CodeWordsParser-int-int-com.aspose.barcode.common.generic.list.Int32List-) |  |
## Methods

| Method | Description |
| --- | --- |
| [decode(Int32List codewords)](#decode-com.aspose.barcode.common.generic.list.Int32List-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [modeSwitcher(Int32List codewords, int[] iPosition, IMicroPdf417ModeParser currentParser)](#modeSwitcher-com.aspose.barcode.common.generic.list.Int32List-int---com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding.IMicroPdf417ModeParser-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse()](#parse--) |  |
| [readEciId(Int32List codewords, int[] offset)](#readEciId-com.aspose.barcode.common.generic.list.Int32List-int---) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MicroPDF417CodeWordsParser(int columns, int rows, Int32List codeWords) {#MicroPDF417CodeWordsParser-int-int-com.aspose.barcode.common.generic.list.Int32List-}
```
public MicroPDF417CodeWordsParser(int columns, int rows, Int32List codeWords)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columns | int |  |
| rows | int |  |
| codeWords | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) |  |

### decode(Int32List codewords) {#decode-com.aspose.barcode.common.generic.list.Int32List-}
```
public MicroPdf417RecognitionResult decode(Int32List codewords)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codewords | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) |  |

**Returns:**
[MicroPdf417RecognitionResult](../../com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding/micropdf417recognitionresult)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### modeSwitcher(Int32List codewords, int[] iPosition, IMicroPdf417ModeParser currentParser) {#modeSwitcher-com.aspose.barcode.common.generic.list.Int32List-int---com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding.IMicroPdf417ModeParser-}
```
public static IMicroPdf417ModeParser modeSwitcher(Int32List codewords, int[] iPosition, IMicroPdf417ModeParser currentParser)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codewords | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) |  |
| iPosition | int[] |  |
| currentParser | [IMicroPdf417ModeParser](../../com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding/imicropdf417modeparser) |  |

**Returns:**
[IMicroPdf417ModeParser](../../com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding/imicropdf417modeparser)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parse() {#parse--}
```
public MicroPdf417RecognitionResult parse()
```




**Returns:**
[MicroPdf417RecognitionResult](../../com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding/micropdf417recognitionresult)
### readEciId(Int32List codewords, int[] offset) {#readEciId-com.aspose.barcode.common.generic.list.Int32List-int---}
```
public static int readEciId(Int32List codewords, int[] offset)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codewords | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) |  |
| offset | int[] |  |

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

