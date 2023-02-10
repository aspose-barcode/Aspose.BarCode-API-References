---
title: DMRecognitionAlgorithm
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix/dmrecognitionalgorithm/
---
**Inheritance:**
java.lang.Object
```
public class DMRecognitionAlgorithm
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DMRecognitionAlgorithm()](#DMRecognitionAlgorithm--) |  |
## Methods

| Method | Description |
| --- | --- |
| [convert2GS1(String codetext)](#convert2GS1-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fixDecreasedList(List<DMResult> aResults, int ShiftX, int ShiftY, int DecreasedSize)](#fixDecreasedList-java.util.List-com.aspose.barcode.barcoderecognition.recognition.datamatrix.DMResult--int-int-int-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [recognizeDataMatrixesStandard(ByteBitmap aBitmap, ITerminationCheck aTerminationCheck)](#recognizeDataMatrixesStandard-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DMRecognitionAlgorithm() {#DMRecognitionAlgorithm--}
```
public DMRecognitionAlgorithm()
```


### convert2GS1(String codetext) {#convert2GS1-java.lang.String-}
```
public static Tup<String,Boolean> convert2GS1(String codetext)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codetext | java.lang.String |  |

**Returns:**
[Tup](../../com.aspose.barcode.common.generic.types/tup)
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
### fixDecreasedList(List<DMResult> aResults, int ShiftX, int ShiftY, int DecreasedSize) {#fixDecreasedList-java.util.List-com.aspose.barcode.barcoderecognition.recognition.datamatrix.DMResult--int-int-int-}
```
public static List<DMResult> fixDecreasedList(List<DMResult> aResults, int ShiftX, int ShiftY, int DecreasedSize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aResults | java.util.List<com.aspose.barcode.barcoderecognition.recognition.datamatrix.DMResult> |  |
| ShiftX | int |  |
| ShiftY | int |  |
| DecreasedSize | int |  |

**Returns:**
[List](../../java.util/list)
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




### recognizeDataMatrixesStandard(ByteBitmap aBitmap, ITerminationCheck aTerminationCheck) {#recognizeDataMatrixesStandard-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<DMResult> recognizeDataMatrixesStandard(ByteBitmap aBitmap, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[List](../../java.util/list)
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

