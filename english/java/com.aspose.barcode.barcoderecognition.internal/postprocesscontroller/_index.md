---
title: PostprocessController
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 33
url: /java/com.aspose.barcode.barcoderecognition.internal/postprocesscontroller/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.recognition.postprocesscontroller.IRegisterPostprocessFilter](../../com.aspose.barcode.barcoderecognition.recognition.postprocesscontroller/iregisterpostprocessfilter)
```
public class PostprocessController implements IRegisterPostprocessFilter
```
## Constructors

| Constructor | Description |
| --- | --- |
| [PostprocessController(IBitmapServer aBitmapServer, RecognitionOptions aRecognitionOptions, ITerminationCheck aTerminationCheck)](#PostprocessController-com.aspose.barcode.barcoderecognition.recognition.bitmapserver.IBitmapServer-com.aspose.barcode.barcoderecognition.internal.RecognitionOptions-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(List<CodeResult> ResultList)](#execute-java.util.List-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult--) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerFirst(PostprocessFilter aFilter)](#registerFirst-com.aspose.barcode.barcoderecognition.internal.PostprocessFilter-) |  |
| [registerLast(PostprocessFilter aFilter)](#registerLast-com.aspose.barcode.barcoderecognition.internal.PostprocessFilter-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PostprocessController(IBitmapServer aBitmapServer, RecognitionOptions aRecognitionOptions, ITerminationCheck aTerminationCheck) {#PostprocessController-com.aspose.barcode.barcoderecognition.recognition.bitmapserver.IBitmapServer-com.aspose.barcode.barcoderecognition.internal.RecognitionOptions-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public PostprocessController(IBitmapServer aBitmapServer, RecognitionOptions aRecognitionOptions, ITerminationCheck aTerminationCheck)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmapServer | [IBitmapServer](../../com.aspose.barcode.barcoderecognition.recognition.bitmapserver/ibitmapserver) |  |
| aRecognitionOptions | [RecognitionOptions](../../com.aspose.barcode.barcoderecognition.internal/recognitionoptions) |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

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
### execute(List<CodeResult> ResultList) {#execute-java.util.List-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult--}
```
public List<CodeResult> execute(List<CodeResult> ResultList)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ResultList | java.util.List<com.aspose.barcode.barcoderecognition.recognition.recognitionsession.coderesult.CodeResult> |  |

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




### registerFirst(PostprocessFilter aFilter) {#registerFirst-com.aspose.barcode.barcoderecognition.internal.PostprocessFilter-}
```
public void registerFirst(PostprocessFilter aFilter)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFilter | [PostprocessFilter](../../com.aspose.barcode.barcoderecognition.internal/postprocessfilter) |  |

### registerLast(PostprocessFilter aFilter) {#registerLast-com.aspose.barcode.barcoderecognition.internal.PostprocessFilter-}
```
public void registerLast(PostprocessFilter aFilter)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFilter | [PostprocessFilter](../../com.aspose.barcode.barcoderecognition.internal/postprocessfilter) |  |

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

