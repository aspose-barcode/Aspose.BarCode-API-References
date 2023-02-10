---
title: OneDRecFilter
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 14
url: /java/com.aspose.barcode.barcoderecognition.barcode1d/onedrecfilter/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.recognition.recognitioncontroller.RecognitionFilter](../../com.aspose.barcode.barcoderecognition.recognition.recognitioncontroller/recognitionfilter), [com.aspose.barcode.barcoderecognition.recognition.recognitioncontroller.MTRegionRecFilter](../../com.aspose.barcode.barcoderecognition.recognition.recognitioncontroller/mtregionrecfilter)
```
public class OneDRecFilter extends MTRegionRecFilter
```
## Constructors

| Constructor | Description |
| --- | --- |
| [OneDRecFilter()](#OneDRecFilter--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute()](#execute--) |  |
| [getBitmapServer()](#getBitmapServer--) |  |
| [getClass()](#getClass--) |  |
| [getOptions()](#getOptions--) |  |
| [getPostprocessRegister()](#getPostprocessRegister--) |  |
| [getRequiredBitmapFilters()](#getRequiredBitmapFilters--) |  |
| [getTerminationCheck()](#getTerminationCheck--) |  |
| [hashCode()](#hashCode--) |  |
| [isApply(BaseDecodeType aReadType)](#isApply-com.aspose.barcode.barcoderecognition.BaseDecodeType-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitmapServer(IBitmapServer value)](#setBitmapServer-com.aspose.barcode.barcoderecognition.recognition.bitmapserver.IBitmapServer-) |  |
| [setOptions(RecognitionOptions value)](#setOptions-com.aspose.barcode.barcoderecognition.internal.RecognitionOptions-) |  |
| [setPostprocessRegister(IRegisterPostprocessFilter value)](#setPostprocessRegister-com.aspose.barcode.barcoderecognition.recognition.postprocesscontroller.IRegisterPostprocessFilter-) |  |
| [setTerminationCheck(ITerminationCheck value)](#setTerminationCheck-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OneDRecFilter() {#OneDRecFilter--}
```
public OneDRecFilter()
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
### execute() {#execute--}
```
public List<CodeResult> execute()
```




**Returns:**
[List](../../java.util/list)
### getBitmapServer() {#getBitmapServer--}
```
public final IBitmapServer getBitmapServer()
```




**Returns:**
[IBitmapServer](../../com.aspose.barcode.barcoderecognition.recognition.bitmapserver/ibitmapserver)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOptions() {#getOptions--}
```
public final RecognitionOptions getOptions()
```




**Returns:**
[RecognitionOptions](../../com.aspose.barcode.barcoderecognition.internal/recognitionoptions)
### getPostprocessRegister() {#getPostprocessRegister--}
```
public final IRegisterPostprocessFilter getPostprocessRegister()
```




**Returns:**
[IRegisterPostprocessFilter](../../com.aspose.barcode.barcoderecognition.recognition.postprocesscontroller/iregisterpostprocessfilter)
### getRequiredBitmapFilters() {#getRequiredBitmapFilters--}
```
public List<BitmapFilterType> getRequiredBitmapFilters()
```




**Returns:**
[List](../../java.util/list)
### getTerminationCheck() {#getTerminationCheck--}
```
public final ITerminationCheck getTerminationCheck()
```




**Returns:**
[ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isApply(BaseDecodeType aReadType) {#isApply-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public boolean isApply(BaseDecodeType aReadType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aReadType | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

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




### setBitmapServer(IBitmapServer value) {#setBitmapServer-com.aspose.barcode.barcoderecognition.recognition.bitmapserver.IBitmapServer-}
```
public final void setBitmapServer(IBitmapServer value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBitmapServer](../../com.aspose.barcode.barcoderecognition.recognition.bitmapserver/ibitmapserver) |  |

### setOptions(RecognitionOptions value) {#setOptions-com.aspose.barcode.barcoderecognition.internal.RecognitionOptions-}
```
public final void setOptions(RecognitionOptions value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RecognitionOptions](../../com.aspose.barcode.barcoderecognition.internal/recognitionoptions) |  |

### setPostprocessRegister(IRegisterPostprocessFilter value) {#setPostprocessRegister-com.aspose.barcode.barcoderecognition.recognition.postprocesscontroller.IRegisterPostprocessFilter-}
```
public final void setPostprocessRegister(IRegisterPostprocessFilter value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IRegisterPostprocessFilter](../../com.aspose.barcode.barcoderecognition.recognition.postprocesscontroller/iregisterpostprocessfilter) |  |

### setTerminationCheck(ITerminationCheck value) {#setTerminationCheck-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public final void setTerminationCheck(ITerminationCheck value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

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

