---
title: pdf417MetadataRecognition
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 16
url: /java/com.aspose.barcode.barcoderecognition.pdf417.codeword/pdf417metadatarecognition/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417CodewordRecognizerBase, com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417CodewordRecognizerSplit
```
public class pdf417MetadataRecognition extends pdf417CodewordRecognizerSplit
```
## Constructors

| Constructor | Description |
| --- | --- |
| [pdf417MetadataRecognition()](#pdf417MetadataRecognition--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMetadata(pdf417DataRegion aDReg, boolean isExtractRight, ITerminationCheck aTerminationCheck)](#getMetadata-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Recognizes metadata from whole dataregion(pdf417 and compactpdf417 version) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### pdf417MetadataRecognition() {#pdf417MetadataRecognition--}
```
public pdf417MetadataRecognition()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMetadata(pdf417DataRegion aDReg, boolean isExtractRight, ITerminationCheck aTerminationCheck) {#getMetadata-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static pdf417Metadata getMetadata(pdf417DataRegion aDReg, boolean isExtractRight, ITerminationCheck aTerminationCheck)
```


Recognizes metadata from whole dataregion(pdf417 and compactpdf417 version)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aDReg | [pdf417DataRegion](../../com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregion) | extracted dataregion |
| isExtractRight | boolean | if value is false we extract only left metadata column/ no right column in compactpdf417 |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[pdf417Metadata](../../com.aspose.barcode.barcoderecognition.pdf417.codeword/pdf417metadata) - recognized metadata, cannot be null
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

