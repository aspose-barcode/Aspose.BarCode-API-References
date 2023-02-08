---
title: RecognitionController
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 37
url: /java/com.aspose.barcode.barcoderecognition.internal/recognitioncontroller/
---
**Inheritance:**
java.lang.Object
```
public class RecognitionController
```
## Constructors

| Constructor | Description |
| --- | --- |
| [RecognitionController(IBitmapServer aBitmapServer, RecognitionOptions aRecognitionOptions, ITerminationCheck aTerminationCheck, IRegisterPostprocessFilter PostprocessRegister)](#RecognitionController-com.aspose.barcode.barcoderecognition.recognition.bitmapserver.IBitmapServer-com.aspose.barcode.barcoderecognition.internal.RecognitionOptions-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-com.aspose.barcode.barcoderecognition.recognition.postprocesscontroller.IRegisterPostprocessFilter-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute()](#execute--) |  |
| [getClass()](#getClass--) |  |
| [getRequiredBitmapFilters()](#getRequiredBitmapFilters--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RecognitionController(IBitmapServer aBitmapServer, RecognitionOptions aRecognitionOptions, ITerminationCheck aTerminationCheck, IRegisterPostprocessFilter PostprocessRegister) {#RecognitionController-com.aspose.barcode.barcoderecognition.recognition.bitmapserver.IBitmapServer-com.aspose.barcode.barcoderecognition.internal.RecognitionOptions-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-com.aspose.barcode.barcoderecognition.recognition.postprocesscontroller.IRegisterPostprocessFilter-}
```
public RecognitionController(IBitmapServer aBitmapServer, RecognitionOptions aRecognitionOptions, ITerminationCheck aTerminationCheck, IRegisterPostprocessFilter PostprocessRegister)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmapServer | [IBitmapServer](../../com.aspose.barcode.barcoderecognition.recognition.bitmapserver/ibitmapserver) |  |
| aRecognitionOptions | [RecognitionOptions](../../com.aspose.barcode.barcoderecognition.internal/recognitionoptions) |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |
| PostprocessRegister | [IRegisterPostprocessFilter](../../com.aspose.barcode.barcoderecognition.recognition.postprocesscontroller/iregisterpostprocessfilter) |  |

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
### execute() {#execute--}
```
public final List<CodeResult> execute()
```




**Returns:**
[List](../../java.util/list)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getRequiredBitmapFilters() {#getRequiredBitmapFilters--}
```
public final List<BitmapFilterType> getRequiredBitmapFilters()
```




**Returns:**
[List](../../java.util/list)
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

