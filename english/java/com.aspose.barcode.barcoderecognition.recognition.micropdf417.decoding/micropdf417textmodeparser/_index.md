---
title: MicroPdf417TextModeParser
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 19
url: /java/com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding/micropdf417textmodeparser/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding.IMicroPdf417ModeParser](../../com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding/imicropdf417modeparser)
```
public class MicroPdf417TextModeParser implements IMicroPdf417ModeParser
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MicroPdf417TextModeParser(ShiftLatch modeSL, IMicroPdf417ModeParser previosModeParser)](#MicroPdf417TextModeParser-com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding.ShiftLatch-com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding.IMicroPdf417ModeParser-) |  |
## Methods

| Method | Description |
| --- | --- |
| [decode(Int32List codewords, int[] iPosition, StringBuilder[] outputSB)](#decode-com.aspose.barcode.common.generic.list.Int32List-int---java.lang.StringBuilder---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MicroPdf417TextModeParser(ShiftLatch modeSL, IMicroPdf417ModeParser previosModeParser) {#MicroPdf417TextModeParser-com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding.ShiftLatch-com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding.IMicroPdf417ModeParser-}
```
public MicroPdf417TextModeParser(ShiftLatch modeSL, IMicroPdf417ModeParser previosModeParser)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| modeSL | [ShiftLatch](../../com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding/shiftlatch) |  |
| previosModeParser | [IMicroPdf417ModeParser](../../com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding/imicropdf417modeparser) |  |

### decode(Int32List codewords, int[] iPosition, StringBuilder[] outputSB) {#decode-com.aspose.barcode.common.generic.list.Int32List-int---java.lang.StringBuilder---}
```
public IMicroPdf417ModeParser decode(Int32List codewords, int[] iPosition, StringBuilder[] outputSB)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codewords | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) |  |
| iPosition | int[] |  |
| outputSB | java.lang.StringBuilder[] |  |

**Returns:**
[IMicroPdf417ModeParser](../../com.aspose.barcode.barcoderecognition.recognition.micropdf417.decoding/imicropdf417modeparser)
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

