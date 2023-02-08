---
title: QRCodeRecognitionAlgorithm
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.recognition.qr/qrcoderecognitionalgorithm/
---
**Inheritance:**
java.lang.Object
```
public class QRCodeRecognitionAlgorithm
```
## Constructors

| Constructor | Description |
| --- | --- |
| [QRCodeRecognitionAlgorithm()](#QRCodeRecognitionAlgorithm--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filterRecognitionResultFromIncorrectedSamePlace(List<BaseQrRecognitionResult> aList, ITerminationCheck aTerminationCheck)](#filterRecognitionResultFromIncorrectedSamePlace-java.util.List-com.aspose.barcode.barcoderecognition.recognition.qr.BaseQrRecognitionResult--com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [fixDecreasedList(List<BaseQrRecognitionResult> aResults, int ShiftX, int ShiftY, int DecreasedSize)](#fixDecreasedList-java.util.List-com.aspose.barcode.barcoderecognition.recognition.qr.BaseQrRecognitionResult--int-int-int-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [recognizeQRCodes(ByteBitmap aBitmap, QRScanParams ScanParams)](#recognizeQRCodes-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.qr.QRScanParams-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QRCodeRecognitionAlgorithm() {#QRCodeRecognitionAlgorithm--}
```
public QRCodeRecognitionAlgorithm()
```


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
### filterRecognitionResultFromIncorrectedSamePlace(List<BaseQrRecognitionResult> aList, ITerminationCheck aTerminationCheck) {#filterRecognitionResultFromIncorrectedSamePlace-java.util.List-com.aspose.barcode.barcoderecognition.recognition.qr.BaseQrRecognitionResult--com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<BaseQrRecognitionResult> filterRecognitionResultFromIncorrectedSamePlace(List<BaseQrRecognitionResult> aList, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.barcoderecognition.recognition.qr.BaseQrRecognitionResult> |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[List](../../java.util/list)
### fixDecreasedList(List<BaseQrRecognitionResult> aResults, int ShiftX, int ShiftY, int DecreasedSize) {#fixDecreasedList-java.util.List-com.aspose.barcode.barcoderecognition.recognition.qr.BaseQrRecognitionResult--int-int-int-}
```
public static void fixDecreasedList(List<BaseQrRecognitionResult> aResults, int ShiftX, int ShiftY, int DecreasedSize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aResults | java.util.List<com.aspose.barcode.barcoderecognition.recognition.qr.BaseQrRecognitionResult> |  |
| ShiftX | int |  |
| ShiftY | int |  |
| DecreasedSize | int |  |

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




### recognizeQRCodes(ByteBitmap aBitmap, QRScanParams ScanParams) {#recognizeQRCodes-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.qr.QRScanParams-}
```
public static List<BaseQrRecognitionResult> recognizeQRCodes(ByteBitmap aBitmap, QRScanParams ScanParams)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| ScanParams | com.aspose.barcode.barcoderecognition.recognition.qr.QRScanParams |  |

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

